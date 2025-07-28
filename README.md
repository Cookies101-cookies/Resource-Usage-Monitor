# Resource-Usage-Monitor

A simple Python script that visualizes CPU, RAM, and Disk usage in real-time using psutil and matplotlib.

## Features

- Tracks CPU usage per core
- Monitors RAM and Disk usage
- Live graph updates every 2 seconds
- Interactive, real-time plotting

## Preview

![Usage Monitor Screenshot](IMG_OO75.png)

## Requirements

1. Make sure you have the following Python libraries installed
   ```bash
   pip install psutil matplotlib

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/cookies101-cookies/resource-usage-monitor.git cd resource-usage-monitor

2. Run the script
   ```bash
   python monitor.py

## How it Works

- The script collects system usage stats every 2 seconds using psutil.
- matplotlib is used to plot real-time graphs for:
  - CPU usage (per core)
  - RAM usage (total %)
  - Disk usage (of root partition /)
- Plots refresh live using plt.ion() and plt.pause().

## Notes

- CPU usage is displayed per core, so the graph will show multiple values per interval.
- This is ideal for personal system monitoring, educational purposes, or as a foundation for more advanced tools.

   

