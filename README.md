```
 | |/ / (_) (_)       | |          | |            | |   
 | ' /    ___    ___  | |_    ___  | |__     ___  | | __
 |  <    / _ \  / __| | __|  / _ \ | '_ \   / _ \ | |/ /
 | . \  | (_) | \__ \ | |_  |  __/ | |_) | |  __/ |   < 
 |_|\_\  \___/  |___/  \__|  \___| |_.__/   \___| |_|\_	
 ```

The Kostebek is a reconnaissance tool which uses firms' trademark information to discover their domains.

**Changelog** 

v1.0.0

- Search trademark information in TLD domains and write founded trademark informations to a file
- Get the trademark informations from the file
- Google search with using the trademark informations
- Record trademark information which found on google search in a file
- Record new domain information which also found on google search in a file


**Installation**

```
sudo apt-get -y install python3-pip

pip3 -r requirements.txt  


download latest version of Chromedriver and configure your driver-path
#sudo apt-get install unzip
#wget -O /tmp/chromedriver.zip http://chromedriver.storage.googleapis.com/2.10/chromedriver_linux64.zip && sudo unzip /tmp/chromedriver.zip chromedriver -d /usr/local/bin/


download latest version of Chrome
https://www.google.com/chrome/browser/desktop/
#dpkg -i google-chrome-stable_current_amd64.deb
#apt-get install -f
#dpkg -i google-chrome-stable_current_amd64.deb
```

**Example**

 Trademark Scan :  python3 kostebek.py -u list.txt -n Organization Name
 
 Get Google Domains  : python3 kostebek.py -g Organization Name 
 
 Get Company Trademarks : python3 kostebek.py -t Organization Name

