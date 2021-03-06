# uk-store-bot
A UK store bot for any items online from Argos, Smyths, AO and John Lewis

# requirements
  - python 3.6 or higher; Install latest at https://www.python.org/downloads/
  - latest google chrome version (version 88.0+) - check your chrome version chrome://settings/help and update to latest if needed. - If you dont already have google chrome installed, install at https://www.google.com/intl/en_uk/chrome/
  - latest chrome driver for chrome version 88; this can be installed at https://chromedriver.chromium.org/downloads
  - any sort of unzipping program, i'd recommend installing winrar since its free and easy to use
  -- If you dont meet any single one of these requirements, the program will NOT work
  
# required modules
  - Selenium - installable by typing 'pip install selenium' into the command prompt. Make sure you install everything above, in the requirements.
  -- If you dont install selenium, the program will NOT work --
  
# instructions
  1. Install the included, zipped, python program - install automatically by clicking https://github.com/MMZaini/uk-store-bot/archive/main.zip - it should be in your downloads folder, you can drag it over to your desktop or anywhere else if you'd like.
  2. Locate and unzip 'uk-store-bot-main.zip'. Then, using winrar right click the zip and select 'Extract Here'
  3. Open the new folder that can be found in the same directory that you have the zip in when unzipping.
  4. You can now delete the zip since its no longer needed but make sure you keep the folder.
  5. Open the folder and copy the chromedriver you installed to the folders, you want to copy it into the 'bots' folder.
  6. Then double click the chromedriver and you'll see a little command prompt looking window come up. It'll say something like Starting ChromeDriver, Only local connections are allowed and ChromeDriver was started successfully. If you see somehting like this on the window you've comleted the hard part.
  7. Minimise the chromedriver into your taskbar and double click the file for whichever store you want to bot. Paste in the link of the item you want to bot (it must be an item from the store the file is name (eg: an Argos link for argos.py and a john lewis link for John Lewis.py)) It'll then bring up another command prompt looking window which should say something like 'DevTools listening'. Then It'll open chrome and depending on the performance (speed) of your computer, it'll refresh the page constantly until the item is avaliable for to be added to cart and purchasesd, when it is avaliable, it will add to cart and take you straight to the checkout page and make a beep sound to alert you to the availbility of the item. Then you'd just checkout normally.
  
# things to keep in mind
  - Smyths and Argos can require you to either login or create an account to make a purchase, so when you first open the program, i'd recommend opening a new tab in the same window, typing in "smyths/argos create account" or "smyths/argos login" if you already have an account and login/create an account, make sure when doing this you select 'save password' or 'autosave details'. This is much quicker than having to login everytime you want to purchase an item, especially when the item is in high demand because it may become sold out before you're able to check out.  

# common errors
  - "chromedriver.exe' executable needs to be in PATH." -- You can fix this error by closing chromedriver if you have it open, then find where the chromedriver.exe and put it into your desktop. Then put the .py file for whichever store you want onto your desktop too. then double click the chromedriver. Then double click the .py and it should work
  - "please specify a unique value for --user-data-dir argument, or don't use --user-data-dir" -- You can fix this by closing all other chrome tabs you may have. Remember: You can only have 1 bot open at a time (you can change this, check # customisability)

# customisability
  -- Keep in mind, if you want to customise or change the code and use it your self, make sure to read the license before doing anything --  
  - You can make it so you have multiple bots open at the same time, here are some instructions.
  
  1. Open the files of the bots you want to have open at the same time in a code editor
  2. find where it says "options.add_argument" then check the whole line and go to where it says 'bot'  
  3. change the bot to something else, it needs to be different for each file for it to work. (you may need  to put each file in a seperate folder and copy chromedriver into each folder and run it from each folder if its still not working)
  - You can really easily change the item you want to bot, here are some instructions on how to do it. (you only need common sense for this and make sure you read the license before distrubuting it!)
  

# features to add
  - (maybe) GUI
  - More stores
