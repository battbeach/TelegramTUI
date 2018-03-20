# TelegramTUI
Telegram client on your console

![telegram](https://user-images.githubusercontent.com/18473198/37569384-a4d32e70-2af2-11e8-948c-5a177b384657.png)

### Dependencies
* [Telethon](https://github.com/LonamiWebs/Telethon)
* [NpyScreen](https://github.com/bad-day/npyscreen)
* [python-aalib](http://jwilk.net/software/python-aalib)

### Installation
`sudo apt-get install git python3 python3-pip`  
`sudo pip3 install telethon`  
`git clone https://github.com/bad-day/TelegramTUI`   
`cd TelegramTUI`
### Additional steps for macosx installation
Download https://github.com/billagee/aalib-patched and re-compile the aalib into a shared lib: 
`pip3 install python-aalib`
Make sure that there is no issue with aalib
`python -c 'import aalib'`

### Usage
* [Create application](https://core.telegram.org/api/obtaining_api_id)  
* Put **api_id** and **api_hash** into **config.ini**  
* Run `./telegramTUI`

### Controls
* Navigation: `Tab`, `Shift+Tab`, `mouse`  
* Send message: `Ctrl+S`, `Alt+Enter`  
* Exit: `Ctrl+Q`, `ESC`  
* Paste: `Shift+INS`
