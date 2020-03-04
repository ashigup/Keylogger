Welcome to the keylogger ! 

Keystroke logging, often referred to as keylogging or keyboard capturing, is the action of recording (logging) the keys struck on a keyboard, typically covertly, so that the person using the keyboard is unaware that their actions are being monitored. 
Data can then be retrieved by the person operating the logging program.
A keylogger is a program that records your keystrokes, and this program saves them in a log file on your local computer.

Currently, there is one keylogger program for one of the major operating systems; Windows.

---
## Windows Installation
keylogger requires:
  1. python 3X
  2. pynput

### Step 1: 
Download the repository using github or git eg.git clone https://github.com/ashigup/Keylogger/

### Step 2: 
Install the modules by running `pip install -r requirements.txt`

---
## How to run it?

### Step 1:

copy the server.py file from bin/server.py to the desired directory you want to transfer the logs to.
and run
```
py server.py
```
This will activate the server.

#### NOTE: 
hostname and port number in the "server.py" and "client.py" file can be edited to send it to                                            some other server other than localhost:9999</b>

### Step 2:

Run following command to activate the key-logger
```
py key_logger.py
```

Run following command to activate the mouse-logger
```
py mouse_logger.py
```

This will activate the logger, and it will start logging keyboard strokes and mouse-clicks in two separate log files (txt).

As soon as the user press the "ESC" key, the logger sends the files to the remote server active in another directory
and logs are transfered into one server copy of logs (txt).


### Uses

Some uses of a keylogger are:

- Business Administration: Monitor what employees are doing.
- School/Institutions: Track keystrokes and log banned words in a file.
- Personal Control and File Backup: Make sure no one is using your computer when you are away.
- Parental Control: Track what your children are doing.
- Self analysis

---

