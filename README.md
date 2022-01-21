# Web-Scraping-2
* We scraped the stars data from Nasa’s site

 ## Used
  * Usage of selenium(In our project we haven't used selenium)
  * Usage of Beautiful soup
  * Getting data from Html of a page

## Steps To Create A Live Image Prediction
  * *We created a virtual environment.*
  * *We installed the necessary libraries.*
  * *We imported the selenium and Beautiful soup in our code.*
  * *We added a new hyperlink to the header.*
  
## Code is given below
### *Code for importing libraries :*
````
from selenium 
import webdriver 
from bs4 import BeautifulSoup 
import time
import csv
````
### *Code to start chromedriver:* 
````
START_URL = "https://exoplanets.nasa.gov/exoplanet-catalog/" 
browser = webdriver.Chrome("/path/to/chromedriver") 
browser.get(START_URL)
time.sleep(10)
````
### *Code for adding hyperlink in code:*
![image](https://user-images.githubusercontent.com/74312429/150482571-1ebd3180-fbe4-42f5-9e62-0d64a4d8ce90.png)
![image](https://user-images.githubusercontent.com/74312429/150482602-8d05e422-39d5-4c07-bd39-7113b2be7024.png)

### *Code for activating venv*
````
python -m venv venv
#open venv in integrated terminal
cd Scripts
.\activate.bat
````
## New Terms :
 * *Beautiful soup targets html tags.html.parser the data.
 * *enumerate add index numbers.*
 * *xpath is used to navigate through elements in xml document.*
 * *BeautifulSoup(bs4):- used for parsing text as html and performing actions in it like finding specific html tags with a particular id,class,ul,il tag etc..*
 * *Selenium:-used for browsing over websites.*
