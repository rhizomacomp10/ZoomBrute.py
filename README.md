# ZoomBrute.py fixed
### A program that automatically tests random Zoom meeting codes,  to brute force meetings.
This is just a quick script that [DDDASHXD](https://github.com/DDDASHXD) made and edited by me that generates either a random 9 or 10 char number, and tries to use it on zoom.
If it works, it'll tell you.

#### currently only works with http proxies not sure

# Requirements
1. You need to have the newest public version of chrome installed
2. Latest version of [Chrome Driver](https://chromedriver.chromium.org/) in the same directory as main.py

# Usage
1. Have python installed to path obviously
1. Open powershell (or cmd) and `CD` to the directory where main.py is located
2. Type in `python setup.py` to install the requirements for script
3. Type in `python main.py` to start the script
4. Enter a proxy if needed, if not, just press enter without writing anything. [Get Proxies](https://proxyscrape.com/free-proxy-list)
5. Done! The program will automatically try different codes, and put the working ones inside working.txt
