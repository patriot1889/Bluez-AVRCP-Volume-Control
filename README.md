# Bluez-AVRCP-Volume-Control

This script looks out for volume changes from a connected bluetooth device using AVRCP.
If a change is detected a command is run to set the volume to the correspondig percentage for 3rd mixer control. (3.5mm output on a Raspberry Pi)

This is meant as either an example of how to capture and use the volume change notifications or as a usable script for control the Raspberry Pi's analogue audio output.


The script logs to journal, you can view this in realtime using "sudo journalctl -n 50 -f"
