# Cowrie Honeypot Project

## Objective
Moniter SSH login activity using Cowrie honeypot on an Ubuntu VM.

## work completed
- installed and configured Cowrie.
- Tested SSH access locally on port 2222.
- Checked JSON event logs.
- Recorded 2 successful login events and 2 command-input events in the current log review.
- Created cowrie_attack_summary.png using matplotlib.

## Test result
The observed source IP was 127.0.0.1, which is local testing, not an external attack. The commands recorded in the reviewed sessions were exit. No failed-login events were show in that filtered output.

## Files
- cowrie_attack_summary.png: local test summary chart.
- README.md: project overview and test notes.

## Limitation
This is an initial local test.External attack monitoring, broader log analysis, and geolocation visualization have not yet been completed.
