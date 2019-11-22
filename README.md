# MyPersonalDocForTesting

comment  créer des tests dans Seleniums 3 pré requis


1 elements locators pour identifier, selectionner un element.
web driver method pour  intéragir et faire des opeation sur l'élément.
Programming features ( to enhance Test Cases)

Elements locators :
Selenium supports 8 elements locators

1 id
2 name
3 className
4 tagName
5 linkText
6pariallLinkText
7 cssSelector
8 Xpath

Web elements
Browser -driver object
-----------
Link
button
image, image Button, image link
Edit box,
Text Area
Check box
Radio Button
Drop down box
List box
Combo box
Combo Box
Web Table / HTML table
Frame ex...
 

A Methods on browser

1 get()
2 getTitle()
3 getPageSource()
4 getwindowHandle()
6 close()
7 quit()
-------------

B Brower navigation methods

1 navigate()->to()
2 navigate()->back()
3 navigate ()->foward()
4 navigate->refresh()

C methods on elements

1 findElement()
2 findElements()
3 sendkeys()
4 clear()
5 click()
6 isDiplayed()
8 isSelected()
9 getText()
10) getAttribute()

d) others

1) manage->windows-maximize
2 explicitlywaot()


Handling Elements in Selenium
----------------------------

1) Handling Browser

Operations on browser :

Launch the browser
Navigate to specified url
return current url
get the page title
return page source
return window handle
close focused browser
close all browser all the browser opened by selenium webdriver after execution
---------
Navigate to another url
navigate back to previous url
navigate forward
refresh the browser
maximize the browsr window














ce qui est nouveau avec selenium 3.0

Selenium core 

removed

Selenium tests eported from IDe, use the selenium html runnerµ
Selenium 3 server
Lightweight commande line compatible remote server
Migrating from Selenium 2 to 3

firefox >= 48 and WebDriver

Use geckodriver for firefox brower like chrome  é IE


Avantage de Facebook Web Driver => support jsonWireProtocol  

https://stackoverflow.com/questions/54382080/what-is-the-difference-between-protocol-and-json-wire-protocol  

Préparer la venue de de la W3C WebDriver. standardizaion avec la version 4 de Selenium Web Driver API car la version 3 de la Web Driver APi n'est aŝ conforme aux standarts, c 'est le changement majeur qu'apportera la version 4





Selenium 4 - Selenium WebDriver W3C Standrdization

the major highlighted change in the selenium 4 is the W3C Standardization of selenium webdriver

WebDriver API is not only used in Selenium, but also used in other automation Tools

. Mobile Automation tools like appium and IOS Driver heavily deoend on WebDriver API across differejt Software without any compatible issues.

Untill Selenium 3, the communication between the webdriver Api and the brfowers is done by the JSON Wire protocol.

. API encoding and decoding is required

In Selenium 4, the communicate will happen using W3C protocol
. WebDriver APPI will now directly communicate with the Browsers witjout any need of API encoding and decoding

Selenium will become morte stable, standardn trustworthy and popular by w3C Standrdization.
As per the standardization process, W3C recommendation dicument for WebDriver API is now available at https://www.w3.org/TR/webdriver/

W3C Stndadization of webdriver, reduces the compatibility issues across different supported browsers.


