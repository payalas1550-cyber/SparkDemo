# SparkDemo
Code snippets for Spark! demos

# Getting Started
1.) Make a GitHub account (a platform built on top of git to share code and collaborate with others)

- https://github.com/

2.) Install Git (version control system which manages your code's history)

- https://git-scm.com/downloads Download the appropriate version for your operating system.

3.) Clone (or fork) this repo locally

- Using a command line (or Git Bash) run:
  - `git clone https://github.com/BuechnerGIS/SparkDemo.git`
- Change directories into the SparkDemo folder
  - `cd ./SparkDemo`

4.) (Optionally) Download Visula Studio Code
- https://code.visualstudio.com/

5.) Install Python (if it's not already installed) - *This is tested using Python 3.12*.
- If using VSCode, open a `Git Bash` terminal.
- If using Git Bash, right click in a Windows Explorer and select `open Git Bash here`.
- Type `python` and/or `python3`. If an interpreter comes up, it's installed! If not...
  - (Windows) https://www.python.org/ftp/python/3.12.7/python-3.12.7-amd64.exe.
  - (Mac) https://www.python.org/ftp/python/3.12.7/python-3.12.7-macos11.pkg.
- Check "Add python.exe to PATH".
- Choose Customize installation install: `pip`, `Python test suite`, and `py launcher`.
- Customize the install location to somewhere you will remember. I usually do `C:\Python`.
- Add the path to the Python folder to your system environment variables.

6.) Configure your environment (back in the terminal)
- Create a python virtual environment
  - `python -m venv ./venv`
- Activate the virtual environment
  - _Windows_
    - `./venv/bin/activate.bat`
  - _Mac/Linux (Git Bash)_
    - `source ./venv/bin/activate`
- Install modules (*This might take a minute..*)
  - `python -m pip install -r ./requirements.txt`
- Start Jupyter Notebook Server
  - `python -m notebook`

7.) Open your local Jupyter Server
- In the terminal, look for a URL with ?token= in it. Copy that whole line into your browser.
- Under "Files" double click `JupyterNotebook.ipynb` and step through the exercise!


# Exercises

## Pull OSM data you created!
Write a query to download your data from https://overpass-turbo.eu/.
Download as a GeoJSON.
- Add to a Leafmap map in Jupyter Notebook

## Query the data
Explore your data using `<dataframe-name>.query()` function


University data: https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx?gotoReportId=7&fromIpeds=true&sid=70365247-c69e-40c7-a078-5b9304fc3b2f&rtid=7