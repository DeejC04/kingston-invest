# Kingston Investment Tool

## Note: Currently in development. This version is not applicable to the average user (yet!). If you know what you're doing, then feel free to test it!

# Table of Contents
1. [Introduction](#Introduction)
2. [Setup](#Setup)
3. [Webapp](#Webapp)
4. [Strategies](#Strategies)
5. [Index Maker](#index-maker)
6. [Collage](#Collage)

## Introduction 
Hi! I'm getting into computational finance, and decided to create a repository full of miscellaneous tools that help me on the daily, so maybe they'll help you. I have a lot of docs on this project, so if you're confused just keep reading! The table of contents below lets you jump to all the different tools.

## Setup
### Installing Libraries:
#### Automatic:
Type `.\setup.bat` in your terminal. This script should install everything necessary.
#### Manual:
The libraries required are:
- requests
- tqdm
- python-dotenv
- randfacts
- quote
- pandas
- matplotlib
- seaborn
- Pillow
- Flask
- pyScss
- flask flask-wtf
- flask-assets
- yfinance
- shutil
- datetime

Here's a command to install all of the above at once:<br>
``pip install requests tqdm python-dotenv randfacts quote pandas matplotlib seaborn Pillow Flask pyScss flask-wtf flask-assets yfinance shutil``
<br>

### API Key
For this project, I use the Alpha Vantage API. They currently offer free API keys. Head over [here](https://www.alphavantage.co/support/#api-key) to claim your free key.
Once you have your API key, create a file called `.env` inside the project's root directory.
Paste your API Key like this: `AV_API_KEY = "XXXXXXXXXXXXXXXXXX"`

Done!
<br>

## Web App
After you have run `.\update.bat`, run `python app.py` to launch a local version of the webapp. Navigate to `locahost:5000` to see it.

## Strategies
#### Description: <br>
Here you can run strategies that I have formulated throughout the years. They are named accordingly.  <br>
Instructions are found inside the strategies folder, read ``usage.md``.

## Index Maker
#### Description: <br>
Here you can create your own custom indices. Want to create the next SP500? Test it out here. <br>
Instructions are found inside the index-maker folder, read ``usage.md``.

## Collage
#### Description: <br>
Generates a collage of all your favorite stocks and/or sets it as your desktop wallpaper.
![example](https://raw.githubusercontent.com/gholtzap/kingston-invest/master/collage.png)

#### Step 1 : Generate Your Data

Type `.\update.bat` to gather & download all data. This script will generate all data + images.
<br>

#### Step 2 : Run wallpaper.py
Run  ``wallpaper.py`` to set the collage as your wallpaper.


