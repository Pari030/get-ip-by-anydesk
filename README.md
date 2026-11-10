# Get IP By Anydesk
*Get IP of someone whoose trying to connect to your monitor with anydesk (Windows and Linux).*
>You can run the program before open anydesk.

## Download Tutorial [git needed]
1. `git clone https://github.com/Pari030/GetIpByAnydesk`
0. `cd GetIpByAnydesk`
0. `py -m pip install -r requirements.txt`
0. `cd src`
0. `py main.py`

>On Linux use `python3` instead of `py` and run both the `pip install` and `main.py` with `sudo`: anydesk runs as root, so a normal user can't see its connections.

## Features
- [x] **Automatic waiting and retry until anyone connect to your minitor.**
- [x] **Automatic get IP information.**
- [x] **Compatible with linux**

# Example Photo

![example photo](screen.png)
