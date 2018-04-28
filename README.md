`ntulearn-dl` is a script to batch downloading course materials from NTULearn

## Features
* Login with username and password and store the session
* Batch download course documents
* Group files by folder

## To-do
* Add argparse
* add netrc support

## Assumptions
Installed:
* Python 2.7
* pip or easy_install

## Library dependencies
* `requests`
* `beautifulsoup4`

## How to use?
1. Download the repository
2. Install dependencies using command-line (prefix 'py -2.7 -m' if using windows)
    - `pip install requests`
    - `pip install beautifulsoup4`
3. Edit `config.py`:
    - replace `USERNAME` and `PASSWORD` with those of yours
    - add NTU courses codes you want to download, more courses -> more time
4. `python ntulearn-dl.py`
