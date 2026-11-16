
# Falcons Club - Task 2

## Recon and Log Analysis

This task was completed on Ubuntu 22.04.

### Nmap Scan
Scanned localhost using Nmap. Ports 22 (SSH) and 80 (HTTP) were open.

### SSH Login Logs
Generated three failed SSH login attempts on my Ubuntu VM and saved the entries in sample_auth.log.

### Python Script
Created analyze_logs.py to read the sample log and display lines containing "Failed password".

### Files
- localhost_scan.txt - Nmap results
- sample_auth.log - Failed SSH login entries
- analyze_logs.py - Python log analysis script
- log_analysis_output.txt - Script output

### Run
python3 analyze_logs.py

SSH password authentication was disabled again after testing.
