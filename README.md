# Daily-Naukri-Update
Selenium and Python powered automation script
Daily Naukri Update
license Test Code Climate made-with-python

Selenium and Python powered automation script
This script automates information updates on the job portal "Naukri". Most recruiters may filter users with the most recent updates on their profile.

Use this script to update your Naukri Profile on schedule every day; this can be completed in seconds.

In order to use this, you need Git, Python 3, and Google Chrome on your machine.

Installation
Install Python 3.10+ and run the below commands

git clone https://github.com/souravkumarkuila/Daily-Naukri-Update
cd Naukri
pip install --upgrade pip
python3 -m venv .venv              # create virtual environment for installing dependencies
./.venv/bin/activate.ps1           # source ./.venv/bin/activate  # command for macOS/linux
pip install -r requirements.txt    # Install dependencies
Configuration: Update RESUME_PATH, USERNAME, PASSWORD, and MOBILE directly in constants.py before running the script.

Run the Script
python naukri.py
