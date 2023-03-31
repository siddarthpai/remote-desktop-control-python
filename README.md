# Python Remote Desktop

A Python GUI based application to let one computer access the other computer remotely.

## Prerequisites

* Python 3 (I used Python 3.9.0)
* Two or more computers running Windows / macOS / Linux
* All computers need to be connected to the same network

## Usage

* We first need to install the [`pyautogui`](https://pyautogui.readthedocs.io/en/latest/) module to control the cursor and keyboard. Launch <b>Command Prompt</b> or <b>Terminal</b> and type the following:

```
pip install pyautogui
```

* You now need to download `server.py` onto one of the computers and `client.py` to the rest.

* Now run `server.py` on and note the IP address as well as the port that comes as an alert.

* On the other computers, run `client.py`. When it asks for the <b>Host IP Address and the Port</b>, type the details that you saw in the alert.

* On the computer running `server.py`, you should now see a tkinter window. This window is your virtual touchpad. Click inside the window, and as your cursor moves inside that window, the cursor will move simultaniosly on the client computers!
- Other actions include  : 
1) **Right click** - ctrl+r
2) **Left click** - ctrl + l
3) **Double click** - ctrl+d
4) To type in text, use the text option.
## Authors

Siddarth.D.Pai - 
GitHub: https://github.com/siddarthpai/remote-desktop-control-python
LinkedIn: https://www.linkedin.com/in/siddarth-pai-ba993a219

