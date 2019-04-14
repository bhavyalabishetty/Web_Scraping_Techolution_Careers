# Web-Scraping using Selenium
Web scraping is defined as a tool for turning the unstructured data on the web into machine readable, structured data which is ready for analysis.

# Why use Selenium?
There are numerous ways of Scraping the data. Some of them include using  Beautiful Soup is a popular Python library that makes web scraping by traversing the DOM (document object model) easier to implement.
But there are some websites that uses Javascript links which will not work without installing some additional packages, this is where Selenuim comes in handy.

# What is the need of Selenium?
The Selenium package is used to automate web browser interaction from Python.
With Selenium, programming a Python script to automate a web browser is possible.

Important Note: There are several websites in which data should not be scraped, in that case we can disguise our webscraping.

# Locating Web Elements:

Web elements in WebDriver can be located and inspected. Selenium IDE and Firebug can be used to inspect the web element on the GUI. It is highly suggested to use Selenium IDE to find the web elements. Once the web element is successfully found, copy and paste the target value within the WebDriver code. The types of locators and the locating strategies are pretty much the same except for the syntax and their application.

In WebDriver, web elements are located with the help of the dynamic finders (findElement(By.locatorType(“locator value”))).

# Some of the methods for identifying elements include:

id -> driver.findElement(By.id(“ID_of_Element”))->	Locate by value of the “id” attribute

className ->	driver.findElement(By.className(“Class_of_Element”)) ->	Locate by value of the “class” attribute

linkText ->	driver.findElement(By.linkText(“Text”)) ->	Locate by value of the text of the hyperlink

partialLinkText	-> driver.findElement(By.partialLinkText(“PartialText”))	-> Locate by value of the sub-text of the hyperlink

name	-> driver.findElement(By.name(“Name_of_Element”))	-> Locate by value of the “name” attribute

xpath	 -> driver.findElement (By.xpath(“Xpath”))	-> Locate by value of the xpath 

cssSelector ->	driver.findElement(By.cssSelector(“CSS Selector”)) -> Locate by value of the CSS selector 

tagName ->	driver.findElement (By.tagName(“input”)) ->	Locate by value of its tag name



# Reference:
The following article were a  helpful reference for this project:

https://www.softwaretestinghelp.com/selenium-webdriver-tutorial-10/
https://medium.freecodecamp.org/better-web-scraping-in-python-with-selenium-beautiful-soup-and-pandas-d6390592e251


