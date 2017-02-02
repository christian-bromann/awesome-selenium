# Awesome Selenium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/christian-bromann/awesome-selenium.svg?branch=master)](https://travis-ci.org/christian-bromann/awesome-selenium)

> A curated list of delightful [Selenium](http://www.seleniumhq.org/) [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Resources

- [Tools](#tools)
- [CSS Regression Testing](#css-regression-testing)
- [Driver](#driver)
- [Online Tools](#online-tools)
- [Cloud Services](#cloud-services)
- [Web Scraping / Mining](#web-scraping-mining)
- [Specifications](#specifications)
- [Blogs](#blogs)

### Tools

#### Javascript

- [selenium-webdriver](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) - The official WebDriver JavaScript bindings from the Selenium project.
- [WD](https://github.com/admc/wd) - WebDriver/Selenium 2 node.js client.
- [WebdriverIO](http://webdriver.io) - better implementation of WebDriver bindings with predefined 50+ actions.
- [CasperJS](http://casperjs.org/) - open source navigation scripting & testing utility.
- [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing.
- [DalekJS](http://dalekjs.com/) - Automated cross browser testing.
- [SlimerJS](http://slimerjs.org/) - A scriptable browser for Web developers.
- [Nightwatch](http://nightwatchjs.org/) - efficient and straightforward Javascript End-to-End tests.
- [yiewd](https://github.com/jlipps/yiewd) - WD.js wrapper using latest Harmony generators! Get rid of the callback pyramid with yield.
- [Karma](http://karma-runner.github.io/0.12/index.html) - Brings a productive testing environment to developers for unit testing (mostly AngularJS).
- [Protractor](https://angular.github.io/protractor/) - Protractor is an end-to-end test framework for AngularJS applications.
- [Cypress](https://www.cypress.io/) - Cypress helps developers write automated tests for the web.
- [CodeceptJS](http://codecept.io/) - Modern Era Aceptance Testing Framework for NodeJS.
- [Nightmare.js](http://www.nightmarejs.org/) - A high-level browser automation library.

#### Ruby

- [Selenium with Ruby](http://seleniumhq.github.io/selenium/docs/api/rb/index.html) - Selenium Ruby bindings
- [Watir](https://watir.com/) - Automated testing that doesn’t hurt
- [Anemone](https://github.com/chriskite/anemone) - Anemone web-spider framework.
- [Mechanize](http://docs.seattlerb.org/mechanize/) - automating interaction with websites.
- [Spidr](https://github.com/postmodern/spidr) - web spidering library that can spider a site, multiple domains, certain links or infinitely.
- [cobweb](https://rubygems.org/gems/cobweb) - web crawler that can use resque to cluster crawls to quickly crawl extremely large sites.

#### PHP
- [Facebook WebDriver](https://github.com/facebook/php-webdriver) - A PHP client for webdriver.
- [Selenium Setup](https://github.com/bogdananton/Selenium-Setup) - A tool for PHP developers to start their own Selenium server.
- [Steward](https://github.com/lmc-eu/steward) - A test runner integrating php-webdriver with PHPUnit.

#### Python

- [Selenium with Python](http://selenium-python.readthedocs.io/) - Selenium Python bindings
- [Pomade](https://github.com/saucelabs/pomade) - SauceLabs integrated test runner for Selenium test.
- [mechanize](http://wwwsearch.sourceforge.net/mechanize/) - Stateful programmatic web browsing.

#### Java

- [Selenium with Java](http://seleniumhq.github.io/selenium/docs/api/java/index.html) - Selenium Java bindings
- [Conductor](http://conductor.ddavison.io) - Turbo-boosted Selenium framework that makes test writing a breeze.
- [darcy](https://github.com/darcy-framework/darcy-webdriver) - Page object framework for structured, maintainable automation.
- [Serenity](http://www.thucydides.info/) - It is an open source library for writing better quality automated acceptance tests faster. (Formerly Thucydides).

#### C#

- [Selenium with C#](http://seleniumhq.github.io/selenium/docs/api/dotnet/index.html) - Selenium C# bindings

#### Groovy

- [Geb](http://www.gebish.org/) - It can be used for scripting, scraping and general automation — or equally as a functional/web/acceptance testing solution via integration with testing frameworks such as Spock, JUnit & TestNG.

### CSS Regression Testing

- [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS.
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - Regression testing tool for [WebdriverIO](http://webdriver.io) (currently deprecated, please use [wdio-screenshot](https://www.npmjs.com/package/wdio-screenshot) for the time being).

### Driver

#### Desktop

- [Firefox](https://github.com/SeleniumHQ/selenium/wiki/FirefoxDriver) - Firefox driver (for FF < v48) is included in the selenium-server-standalone.jar available in the downloads.
- [Geckodriver](https://github.com/mozilla/geckodriver) - Firefox driver (for FF > v48), supported with Selenium >= v3
- [Chrome](https://sites.google.com/a/chromium.org/chromedriver/home) - ChromeDriver is a standalone server which implements WebDriver's wire protocol for Chromium.
- [Internet Explorer](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver) - The InternetExplorerDriver is a standalone server which implements WebDriver's wire protocol.
- [Edgedriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) - Microsoft Webdriver server for Edge
- [Safari](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver) - The SafariDriver is implemented as a Safari browser extension. The driver inverts the traditional client/server relationship and communicates with the WebDriver client using WebSockets (only supported for Safari <= v9, all new Safari version comming with macOS Sierra come with an integrated SafariDriver that is closed source by Apple).
- [Opera](https://github.com/operasoftware/operachromiumdriver/blob/master/README.md) - OperaDriver is a vendor-supported WebDriver implementation developed by Opera Software and volunteers that implements WebDriver API for Opera.

#### Mobile

- [Appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps. It drives iOS, Android and Windows Apps using the WebDriver protocol.
- [Selendroid](http://selendroid.io/mobileWeb.html) - Selendroid is based on the Android instrumentation framework.
- [ios-driver](http://ios-driver.github.io/ios-driver/) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.  
- [Winium](https://github.com/2gis/Winium) - Automation framework for Windows platforms. It is free. It is opensource. It is Selenium-based. Supports: Windows Desktop (WPF, WinForms); Windows Store or Universal Apps for Windows Phone; Windows Phone Silverlight Apps.

### Desktop Tools
- [SWD Page Recorder](https://github.com/dzharii/swd-recorder) - Windows Desktop application that makes it easy to create, test and debug new Selenium Webdriver PageObject classes. It works with C#, Java, Python and Ruby out of the box and you may add own code generation templates.

### Cloud Services

- [Sauce Labs](https://saucelabs.com) - Cross browser testing made awesome. Selenium testing, mobile testing, JS unit testing on 300+ OS/browser platforms. Get started for free.
- [Browserstack](https://www.browserstack.com/) - Test your website for cross browser compatibility on real browsers. Instant access to multiple desktop and mobile browsers. Get Free Trial.
- [TestingBot](https://testingbot.com) - TestingBot provides easy cross browser testing with Selenium in the cloud.

### Web Scraping / Mining

- [Scrapy](http://scrapy.org) - **Python**, mainly a scraper/miner - fast, well documented and, can be linked with [Django Dynamic Scraper](http://django-dynamic-scraper.readthedocs.org/en/latest/) for nice mining deployments, or [Scrapy Cloud](http://scrapinghub.com/scrapy-cloud.html) for PaaS (server-less) deployment, works in terminal or an server stand-alone proces, can be used with **Celery**, built on top of **Twisted**.
- [Node-Crawler](https://github.com/sylvinus/node-crawler) - **Node.js** Web Crawler/Spider for NodeJS + server-side jQuery.

### Specifications

- [The WebDriver Wire Protocol](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol) - All implementations of WebDriver that communicate with the browser, or a RemoteWebDriver server shall use a common wire protocol.
- [WebDriver](http://www.w3.org/TR/webdriver/) - This specification defines the WebDriver API, a platform and language-neutral interface and associated wire protocol that allows programs or scripts to introspect into, and control the behaviour of, a web browser.

### Blogs

- [Official Selenium Blog](https://seleniumhq.wordpress.com/) - The official blog by SeleniumHQ.
- [Elemental Selenium](http://elementalselenium.com/) - A free, once-weekly e-mail on how to use Selenium like a Pro.
- [Assert Selenium](http://www.assertselenium.com/) - Selenium Automation in a Right way - A Selenium only blog.
- [SauceLabs Blog](https://saucelabs.com/blog) - Blog curated by SauceLabs

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christian Bromann](http://www.christian-bromann.com/) has waived all copyright and related or neighboring rights to this work.
