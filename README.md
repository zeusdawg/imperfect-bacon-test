# Searching for Bacon

This is a simple automated test that searches for bacon using Google.  It utilizes Selenium IDE as it's very easy to use, and gives a good visual test results.  It can also be used to create a simple test, and can be exported to a variety of languages to create a more in depth test that could, for example, be run on a server.

## Installation of Selenium IDE

The Selenium IDE can be installed on Firefox and Chrome via their web stores. Below is the link to the Selenium webpage for further instructions:

https://www.selenium.dev/selenium-ide/

A more indepth article about installing Selenium IDE is located here:

https://www.selenium.dev/selenium-ide/docs/en/introduction/getting-started


## Usage 

Once you have the Selenium IDE installed on your browser, download the Selenium file, from the attachment sent via email, or from my github https://github.com/zeusdawg/cosmogrrl/projects/1 "Bacon_Project.side" to a handy, and memorable location on your hard drive.  

Open the browser that has Selenium installed, click on the Selenium icon in the toolbar.  Open "Bacon_Project.side".  You run the test by clicking play. This opens a tab and runs the test.  Click back onto the Selenium window to see the results of each step, should it be in the background.  

## TODO

The original plan was to utilize Python and BeautifulSoup.  However, I ran into issues as my current laptop is an older Mac, and I could not guarantee that writing using older and unsupported versions of Xcode, Python and BeautifulSoup would run on more modern systems.

- Convert the test to Python and BeautifulSoup, or similar.
- Add better verification that the wikipedia article about bacon is the top result, and that results for Sir Francis Bacon is lower.
- Compare bacon calorie results.
- Add location functionality.
- Verify that the weather in Bacon, Indiana is above 32 Fahrenheit, or 0 Celsius.
