# 🕒 Time Calculator

A Python program that takes a starting time, a duration, and an optional starting day of the week, then returns the resulting time.

## Features

- Handles AM/PM time format
- Calculates correct time even with day rollover
- Optionally accounts for starting weekday
- Shows how many days later the result is

## How It Works

You provide:
- A start time in 12-hour format (e.g., `"3:00 PM"`)
- A duration in hours and minutes (e.g., `"3:10"`)
- *(Optional)* A weekday (e.g., `"Tuesday"`)

Example:
add_time("3:00 PM", "3:10")           # Returns "6:10 PM"
add_time("11:30 AM", "2:32", "Monday")  # Returns "2:02 PM, Monday"
add_time("11:43 AM", "00:20")          # Returns "12:03 PM"
