# Task 14 – CloudKicker

## Public Access

http://51.20.183.172

## Setup

* Flask running on: 127.0.0.1:5000
* Nginx running on: Port 80

## Architecture

Internet → Nginx (80) → Flask (127.0.0.1:5000)

## Notes

* Flask is not exposed publicly
* Reverse proxy configured using Nginx
