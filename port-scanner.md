# 🔍 Port-Scanner

**GitHub Repository:** [gab-dev-7/port-scanner](https://github.com/gab-dev-7/port-scanner)

## Overview

A high-performance network reconnaissance tool designed for efficient port scanning and service detection across networks.

## Detailed Description

Port-Scanner provides fast, accurate port scanning capabilities with detailed service information, making it ideal for network administrators and security professionals.

## Installation

```bash
git clone https://github.com/gab-dev-7/port-scanner.git
cd port-scanner
pip install -r requirements.txt
chmod +x port_scanner.py
```

## Usage Examples

# Basic port scan

./port_scanner.py --target 192.168.1.1

# Specific port range with service detection

./port_scanner.py --target example.com --ports 1-1000 --service-detection

# Save results to file

./port_scanner.py --target 10.0.0.1 --output scan_results.json

## Features in Detail

- **Multiple Scan Types**: TCP Connect, SYN, UDP scanning
- **Banner Grabbing**: Service version detection
- **Parallel Scanning**: Fast execution through concurrency
- **Flexible Output**: Multiple export formats including JSON and CSV

## Tech Stack Deep Dive

- **Python 3.7+**: Core implementation
- **Socket Programming**: Low-level network communication
- **Concurrent.Futures**: Parallel scanning operations
- **Argparse**: Robust command-line interface

[← Back to Overview](../)
