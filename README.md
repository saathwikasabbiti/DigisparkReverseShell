# Reverse Shell in 10-15 Seconds with a Digispark
A simple payload to get reverse shell in seconds. Supports Windows 10.
**WARNING: I claim no responsibility for any illegal actions using this script.**

## How to Use
**Ensure you have installed the Digispark Drivers and configured your Arduino IDE before attempting to flash the script.**
1. Set IP Address & Port to your Netcat listener in 'remotescript.PS1'
2. Upload remotescript.PS1 to Pastebin and grab raw paste link. 
3. Replace 'REMOTESCRIPTURL' with your Pastebin raw URL on line 37 in 'flash.ino'
4. Open and upload 'flash.ino' via Arduino IDE to your Digispark.
5. Listen for connections using Netcat. `nc -v -n -l -p PORT`

## What it Does
- Disables Windows Defender to allow the Reverse Shell connection between the victim and server.
- Establishes Reverse Shell connection using Powershell script hosted online.
- Bypasses UAC prompts
- Remains completely hidden from taskbar, and opens no visible windows.
- Clears Run box history from registry.

