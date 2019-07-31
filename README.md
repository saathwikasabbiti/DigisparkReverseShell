# Reverse Shell in 10-15 Seconds with a Digispark
A simple payload to get reverse shell in seconds.

## How to Use
1. Set IP Address & Port to your Netcat listener in 'remotescript.PS1'
2. Upload remotescript.PS1 to Pastebin and grab raw paste link. 
3. Replace 'REMOTESCRIPTURL' with your Pastebin raw URL on line 37 in 'flash.ino'
4. Open and upload 'flash.ino' via Arduino IDE to your Digispark.
5. Listen for connections using Netcat. ``nc -lp PORT'
