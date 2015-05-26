# Awesome Selenium

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

- [selenium-webdriver](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) - The official WebDriver JavaScript bindings from the Selenium project
- [WD](https://github.com/admc/wd) - WebDriver/Selenium 2 node.js client
- [WebdriverIO](http://webdriver.io) - better implementation of WebDriver bindings with predefined 50+ actions
- [CasperJS](http://casperjs.org/) - open source navigation scripting & testing utility
- [Zombie.js](http://zombie.labnotes.org/) - Insanely fast, headless full-stack testing
- [DalekJS](http://dalekjs.com/) - Automated cross browser testing
- [SlimerJS](http://slimerjs.org/) - A scriptable browser for Web developers
- [Nightwatch](http://nightwatchjs.org/) - efficient and straightforward Javascript End-to-End tests
- [yiewd](https://github.com/jlipps/yiewd) - WD.js wrapper using latest Harmony generators! Get rid of the callback pyramid with yield
- [Karma](http://karma-runner.github.io/0.12/index.html) - Brings a productive testing environment to developers.

#### Ruby

- [Anemone](https://github.com/chriskite/anemone) - Anemone web-spider framework
- [Mechanize](http://docs.seattlerb.org/mechanize/) - automating interaction with websites
- [Spidr](https://github.com/postmodern/spidr) - web spidering library that can spider a site, multiple domains, certain links or infinitely
- [cobweb](https://rubygems.org/gems/cobweb) - web crawler that can use resque to cluster crawls to quickly crawl extremely large sites

#### Python

- [mechanize](http://wwwsearch.sourceforge.net/mechanize/) - Stateful programmatic web browsing

### CSS Regression Testing

- [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - Regression testing tool for [WebdriverIO](http://webdriver.io)

### Driver

- [Firefox](https://github.com/SeleniumHQ/selenium/wiki/FirefoxDriver) - Firefox driver is included in the selenium-server-stanalone.jar available in the downloads.
- [Chrome](https://sites.google.com/a/chromium.org/chromedriver/home) - ChromeDriver is a standalone server which implements WebDriver's wire protocol for Chromium.
- [Internet Explorer](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver) - The InternetExplorerDriver is a standalone server which implements WebDriver's wire protocol.
- [Safari](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver) - The SafariDriver is implemented as a Safari browser extension. The driver inverts the traditional client/server relationship and communicates with the WebDriver client using WebSockets.
- [Opera](https://github.com/operasoftware/operachromiumdriver/blob/master/README.md) - OperaDriver is a vendor-supported WebDriver implementation developed by Opera Software and volunteers that implements WebDriver API for Opera.
- [Selendroid](http://selendroid.io/mobileWeb.html) - Selendroid is based on the Android instrumentation framework.
- [ios-driver](http://ios-driver.github.io/ios-driver) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
- [Appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps. It drives iOS and Android apps using the WebDriver JSON wire protocol.

### Online Tools

- [CasperBox IDE](http://ide.casperbox.com) - Simple online IDE for writing and running CasperJS scripts directly in the browser (built on top of CasperBox API)

### Cloud Services

- [Sauce Labs](https://saucelabs.com) - Cross browser testing made awesome. Selenium testing, mobile testing, JS unit testing on 300+ OS/browser platforms. Get started for free.
- [Browserstack](http://www.browserstack.com) - Test your website for cross browser compatibility on real browsers. Instant access to multiple desktop and mobile browsers. Get Free Trial.
- [TestingBot](https://testingbot.com) - TestingBot provides easy cross browser testing with Selenium in the cloud.
- [CasperBox](http://casperbox.com/) - RESTful API for running CasperJS scripts online

### Web Scraping / Mining

- [Scrapy](http://scrapy.org) - **Python**, mainly a scraper/miner - fast, well documented and, can be linked with [Django Dynamic Scraper](http://django-dynamic-scraper.readthedocs.org/en/latest/) for nice mining deployments, or [Scrapy Cloud](http://scrapinghub.com/scrapy-cloud.html) for PaaS (server-less) deployment, works in terminal or an server stand-alone proces, can be used with **Celery**, built on top of **Twisted**
- [Snailer](http://snailer.org/) - **Node.js** Frontend test and audit framework. Extensible with plugins.
- [Node-Crawler](https://github.com/sylvinus/node-crawler) - **Node.js** Web Crawler/Spider for NodeJS + server-side jQuery

### Specifications

- [The WebDriver Wire Protocol](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol) - All implementations of WebDriver that communicate with the browser, or a RemoteWebDriver server shall use a common wire protocol.
- [WebDriver](http://www.w3.org/TR/webdriver/) - This specification defines the WebDriver API, a platform and language-neutral interface and associated wire protocol that allows programs or scripts to introspect into, and control the behaviour of, a web browser.

### Blogs

- [Official Selenium Blog](http://seleniumhq.wordpress.com/) - The official blog by SeleniumHQ.
- [Elemental Selenium](http://elementalselenium.com/) - A free, once-weekly e-mail on how to use Selenium like a Pro.
