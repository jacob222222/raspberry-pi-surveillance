# raspberry-pi-surveillance
Basic Raspberry Pi motion detection surveillance system



-----------------------------------------------------------------------

# Raspberry Pi Motion Detection Surveillance System

This is a basic surveillance system project using a Raspberry Pi, camera module, and motion detection software.

## Project Description

This system uses a Raspberry Pi to detect motion and save video footage or snapshots when movement is detected. It also includes an optional RFID access control component using the MFRC522 reader.

## Features

- Detects motion using `motion` software
- Records video or images on motion detection
- Live stream can be enabled on local network
- Optional integration with RFID reader

## Hardware Used

- Raspberry Pi 3/4 or Zero W
- Raspberry Pi Camera Module or USB webcam
- Optional: MFRC522 RFID module

## Folders and Files

- `motion/motion.conf`: Configuration file for motion detection
- `rfid/rfid_reader.py`: Python script to scan RFID tags
- `images/demo.jpg`: Example image or snapshot from the system

## Demo
Should Display "Motion Capture"

![Motion Capture](images/demo.jpg)

## Status

This was a personal project created for learning and demonstration purposes. It can be extended or modified based on different hardware setups.
