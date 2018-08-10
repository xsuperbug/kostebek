# Köstebek

The Kostebek is a reconnaissance tool which uses firms' trademark information to discover their domain and process it. 

**Changelog** 

v1.0.0

- Get trademark information by using a text file
- Get trademark information in TLD domains
- Get trademark information by using Google search engine
- Save trademark information to a file
- saved domains in a text file from Google Search Engine


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

