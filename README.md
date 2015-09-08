storcli_show_slots
==================

**Summary**

Display LSI storcli command output in a pictorial grid on your terminal.

**Features**

- light-weight tool for displaying LSI array data using Perl5, not Java or a web server.
- ANSI color codes for failed pdisks and vdisks.
- No firewall changes needed.

**Technical Details**

- Perl5. Tested on a Dell 2950 with PERC6i and PERC6e controllers and several MD1000 disk arrays running CentOS5.

`usage: storcli_show_slots`

    storcli_show_slots version 0.1. Collecting data ...
    
    0: 32: OK BACKPLANE 86O02YR O/0 O/0 O/1 O/1 O/1 S/1
    1: 34: OK MD1000 GGBLMJ1    O/2 O/2 O/3 O/3 O/3 O/3 M/  M/  M/  M/  M/  M/  M/  M/  M/ 
    1: 50: OK MD1000            O/4 O/4 O/4 O/4 O/4 O/7 O/7 O/7 M/  O/7 O/5 O/5 O/5 O/5 O/5
    1: 81: OK MD1000 833Q12S    O/1 O/1 O/1 O/1 O/1 O/6 O/6 O/6 O/6 O/6 O/0 O/0 O/0 O/0 O/0
        
    For vdisk status, type: storcli /call/vall show

**Also See**

My gocons project for invoking Dell IPMI commands.

