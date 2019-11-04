# Youtube-Comment-scraping-using-selenium
Social media analytics has been gaining traction to mine the customer/user sentiments for boosting businesses.It gathers various statistics of data to measure various performance of your social media strategy. Youtube is one main source of collecting customer information and mining this data can leverage many business strategies.


<h1>Selenium 1</h1>

Selenium is a popular tool for automating browsers and is also very handy for web scraping.

Selenium needs a driver to interface with the selected browser, which can now speak directly to its respective browser's engine to control it.

A python script can be programa web browser using Selenium. It gives us the freedom we need to efficiently extract the data and store it in our preferred format for future use.

<h1>Setting up the python Environment: </h1>

<h2>Step 1: Install Python binding:<h2>

#Open terminal and type-
$ pip install selenium

<h2>Step 2: Download WebDriver (Chrome):<h2>

Visit https://sites.google.com/a/chromium.org/chromedriver/download 
Select the compatible driver for your Chrome version
To check the Chrome version you are using, click on the three vertical dots on the top right corner
Then go to Help -> About Google Chrome

<h2>Step 3: Move the driver file to a PATH:<h2>

Go to the downloads directory, unzip the file, and move it to usr/local/bin PATH.

$ cd Downloads
$ unzip chromedriver_linux64.zip
$ mv chromedriver /usr/local/bin/

We’re all set to scrape the youtube comments data using selenium.

