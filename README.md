# Welcome to bruteSpoof
>Helps spoof ZMAP IP for scanning SSH for bruting. Needs 2 servers CLIENT and SPOOFER. Also im sure you're tired of your VPS getting suspended because of the SSH & Telnet bruting for your botnet.

## Interface & ToolPlay
This is a CLI output of the program.
```
root@trackprojects:~# python console.py 
Usage: python console.py <outputfile> <spoof?> <scanlst>
```

Output File is where ZMAP will save all the ips.
Spoof? is a yes & no option. [ You need to edit the IP in the file to change it to your CLIENT server's ip ].
scanLST is the file which contains all the ranges to scan via ZMAP.

## Installation
First you need to install a few modules to prevent errors like this that will prevent you from running the script.
```
root@trackprojects:~# python console.py 
Traceback (most recent call last):
  File "xLib.py", line 14, in <module>
    import urllib
ImportError: No module named urllib
```
To do this run the following commands on your system. <br>
```pip install urllib```<br>
```pip install re```<br>
These will install all the modules required to run this script. Once all this is done run this command to finnaly start the bruteSpoof script.<br>
```python console.py```

Note: This is still in BETA as the CLINET side script still has to be made.
