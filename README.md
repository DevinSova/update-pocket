# update_pocket

update_pocket is cross-platform script to update your Analogue Pocket firmware, openFPGA cores, and any required dependencies.

## Requirements
- Python 3
- `requests, beautifulsoup4` python modules

## macOS and Linux users
1. Download this repo and unzip it onto the root of your pocket sd card
2. Run `update_pocket.sh`, it will update the updater (!) and install required dependencies

## Windows users
1. Install python (can be done from Microsoft Store or [here](https://www.python.org/downloads/))
2. Open Command Prompt or Powershell and enter `python -m pip install requests beautifulsoup4`
3. Download this repo and unzip it onto the root of your pocket sd card
4. Run `update_pocket.bat`

## How can I add a new core?
Just open `repo.json` and add your repository name, then submit a PR. Make sure you publish a zipped release so that we can find it!