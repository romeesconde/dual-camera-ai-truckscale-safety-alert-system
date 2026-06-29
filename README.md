# Dual-Camera AI Truckscale Driver Exit Safety Alert System

This project is an AI-powered truckscale safety monitoring prototype developed during my OJT at Charoen Pokphand Foods Philippines Corp. – Aqua.

The system uses a Flask-based CCTV dashboard with YOLO object detection, RTSP streaming, MySQL logging, and Telegram/API alerts. It is designed to monitor trucks on a truckscale, identify vehicle direction, check whether a driver/person exits the vehicle after the truck becomes stable, and send an alert when no exit is detected within the allowed time limit.

## Key Features

* Dual-camera CCTV monitoring setup
* Primary and secondary camera switching logic
* Vehicle and person detection using YOLO
* Vehicle front/back direction classification
* Truck count and scale status monitoring
* Driver/person exit checking
* MySQL database logging
* Telegram/API safety alerts
* RTSP streaming support
* Dashboard display for active camera, vehicle facing, truck count, driver timer, driver status, and recording status

## Technologies Used

* Python
* Flask
* YOLOv8
* MySQL
* MediaMTX RTSP Streaming
* Telegram Bot API
* HTML/CSS
* CCTV/IP Camera Monitoring

## Project Purpose

The purpose of this project is to improve truckscale safety monitoring by automatically detecting truck activity, selecting the best camera angle, checking driver/person exit behavior, recording video evidence, and sending alerts when a possible safety issue occurs.

## Note

This repository is a sanitized portfolio version. It does not include confidential company files, real CCTV footage, private credentials, internal IP addresses, API tokens, Telegram bot tokens, database passwords, or sensitive operational data.
