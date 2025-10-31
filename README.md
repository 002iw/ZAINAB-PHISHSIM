# Zainab PhishSim

Zainab PhishSim — a small authorized phishing-training simulator for lab use only.

> Important: This repository is intended for authorized training/testing environments only. Do not use this tool against real third-party systems.

## Features
- Create training campaigns
- Landing pages (captive-like) for testing within authorized networks
- Store events and export CSV reports
- Terminal ASCII banner: *Powered by Zainab Basim*

## Quick start (development)
```bash
git clone https://github.com/YOUR_USERNAME/ZAINAB-PHISHSIM.git
cd ZAINAB-PHISHSIM
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 zainabbasim_phishsim_v2.py
# open http://localhost:5000
