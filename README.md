# Objective

This automation repository is to demonstrate the capabilities of FluentLenium for web automation. FluentLenium is a wrapper for Selenium webdriver provides easier implementation of web automation features with lesser lines of code.

## Environment dependencies

- Java Development Kit (1.8+)
- Apache maven
- Chromedriver
- Selenium Java
- FluentLenium
- Testng
[fluentlenium](https://github.com/FluentLenium/FluentLenium)

## Setup to Clone and execute test

```
git clone https://github.com/sureshbabuthangam/Webautomation
cd Webautomation
mvn clean test
```

## Automation Features Implemented

* Page Object Model design pattern
* FluentLenium 
    * Properties to read project properties
    * PageFactory & FluentLenium Web Objects 
* Testng Tests
    * Fill a web page form
    * Handling Popup window

## Troubleshooting Tips:
* If you are using jdk 1.8+ then use FluentLenium 3.x.x, otherwise if FluentLenium 4.x.x is used then it requires higher version of java


## Areas for improvement

* Capturing Screenshots for every test case
* Separating the data layer and reading data from flatfile or excel
* Implement a better reporting utility like Extent reports

## Revision History
* 1.0.0 First Release with initial features
