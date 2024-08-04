# Pomodoro Timer

This is a simple Pomodoro Timer application built using Python and Tkinter. The Pomodoro Technique is a time management method that uses a timer to break work into intervals, typically 25 minutes in length, separated by short breaks.

## Features

- **Work Interval**: 25 minutes of focused work.
- **Short Break**: 5 minutes break after each work interval.
- **Long Break**: 20 minutes break after four work intervals.
- **Visual Timer**: Display the countdown timer.
- **Check Marks**: Track the number of completed work intervals.
- **Start and Reset**: Buttons to start or reset the timer.

## Requirements

- Python 3.x
- Tkinter (usually included with Python installations)

## How to Run

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/pomodoro-timer.git
    cd pomodoro-timer
    ```

2. **Run the Application**:
    ```sh
    python pomodoro_timer.py
    ```

## Code Overview

### Constants and Variables

Define colors, font, and timer intervals:
```python
PINK = "#e2979c"
RED = "#e7305b"
GREEN = "#9bdeac"
YELLOW = "#f7f5dd"
FONT_NAME = "Courier"
WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20
reps = 0
timer = None
