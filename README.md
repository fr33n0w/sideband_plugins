# sideband_plugins

# Repository of self-developed Reticulum Sideband Plugins

# Installing Sideband Plugins:
    # Installing Sideband Plugins:
    1 Goto Menù -> Plugins
    2 Enable Plugins
    3 Enable Command Plugins 
    4 Select a plugin folder to put scripts in it.
    

# Here you can find some useful Sideband Plugins.

- msg.py
my first plugin for automatic messaging, for handfree remote node testing purpose, useful for on the road testing and LoRa signal quality continuous check. 
  
Download and copy the script in the Sideband Directory folder.
Chek if plugin command is added in sideband by looking at the bottom of the plugins menu. If new command is not found, reboot and restart sideband and it should appear.

Once the plugin is correctly installed, with a remote istance of sideband you can send the following command:
msg <number of messages> <delay time between messages> <custom text message>
  
    Example: msg 10 5 hello!

    The remote sideband will replay the message "hello!" 10 times with a delay of 5 second per message.

msg.py Plugin Screenshots:

![photo_2025-02-01_16-22-10](https://github.com/user-attachments/assets/f878a00b-d148-4d4d-a68f-bf1510e308cb) ![photo_2025-02-01_16-22-10 (2)](https://github.com/user-attachments/assets/81083b41-b65c-4d9e-922e-e5e0b424b8b6)
