This M4L MIDI device allows you to set up to 8 MIDI notes and map them to OSC trigger messages. It is meant to make synchronisation with QLab or other softwares with a custom OSC API easier.

Setting up:
1) Input host name. For a local connection, use default 127.0.0.1.
2) Input destination port. QLab listens by default to port 53000. Make sure QLab is actively listening: QLab Settings -> Network -> OSC Access -> Check "View", "Edit" and "Control"
3) Enable as many notes as you want to use, and write the note value or number for each of them.
4) Write your OSC addresses for each action. You can find QLab's OSC dictionary here: https://qlab.app/docs/v5/networking/using-osc/
5) By default, messages are sent as TRIGGERs, like /cue/1/start but you can also use the note's velocity as a parameter. If you wish to do so, toggle the menu to PARAMETER. the velocity value will be immediately appended to your message.

This device is a simplified version of the M4L devices in the Ableton Connection Kit (https://github.com/Ableton/m4l-connaection-kit/tree/main).
