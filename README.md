# QAProject

This is a test of directspecials.com using selenium webdriver.

Instructions

The resources folder includes all the necessary drivers and setup to run the tests. This folder includes jar files for selenium, sts-bundle (platform) to execute the scripts, JDK for java, Firefox setup & drivers for chrome, Mozilla & IE.
I used Spring Tool Suite 3.8.2.Release which is compatible with Selenium 2.53.1 and Mozilla Firefox 47.0.2.
I am including all the setups of the above mentioned software that needs to be installed for executing the scripts.
I ran the script using TestNG, which needs to be installed in Spring Tool Suite.
The JAR files that I used are :

1. TestNG
2. Selenium 2.53.1 -> libs
3. Selenium 2.53.1 -> selenium-server-2.53.1 & selenium-server-2.53.1-srcs


Approach
========

I performed an extensive test of directspecials.com using both manual and automation. The testing went pretty smoothly for the most part, however I found some errors listed below along with the screen shots.

Manual Testing Approach
========================

Screenshot1 : User input gets appended to the Textbox Label.

Screenshot2 : Phone, Alt Phone and ZIP accepts characters/alphabets.

Screenshot3 : With the wrong inputs in Call Now form, pressing the ‘contact me’ button gives the ‘Thank You’ screen instead of an error.

Screenshot4 : The last name accepts numbers with an approved green tick mark in directtv.com/dtvapp/register/register.jsp

Screenshot5 : Scroll bar is missing when the page is minimized.

Automation Testing Approach
===========================

data-driven elements : I tested the 'Call Me' form given in the home page for directspecials.com with multiple inputs from an excel spreadsheet. I called the excel sheet path in the script and put the sheet column data in a for loop.

