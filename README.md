# port-scanning

## Introduction

Welcome to the Port Scanner project! This simple Python script allows you to scan for open ports on a specified target IP address or hostname. The script utilizes the `socket` library to check the connectivity of each specified port, aiding in network analysis and cybersecurity assessments.

## Features

- Scans a specified range of TCP ports on a target IP address.
- Logs results to a file (`port_scan.log`).
- Supports customizable port ranges.
- Displays open ports in the console output.

## Requirements

To run this script, you need the following:

- Python 3.x
- The `socket` library, which is included with Python by default.
- The `argparse` library for command-line argument parsing (also included with Python).

## Installation

1. Clone this repository or download the script file:
   ```bash
   git clone https://github.com/MrTsekar/port-scanner.git
   cd port-scanner
