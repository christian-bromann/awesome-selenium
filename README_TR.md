# Awesome Selenium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Test Awesome List](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml/badge.svg)](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml)

> Güzel [Selenium](http://www.seleniumhq.org/) [kaynaklarının](#resources) düzenlenmiş bir listesi.

[Awesome](https://github.com/sindresorhus/awesome) listesinden ilham alındı.

## Kaynaklar

- [Araçlar](#araçlar)
- [CSS Regresyon Testi](#css-regresyon-testi)
- [Konteynerler(Docker vb.)](#konteynerlerdocker-vb)
- [Driver](#driver)
- [Masaüstü Araçları](#masaüstü-araçları)
- [Selenium Grid](#selenium-grid)
- [Bulut Hizmetleri](#bulut-hizmetleri)
- [Cihaz Farmları(Device Farms)](#cihaz-farmlardevice-farms)
- [Web Kazıma / Madenciliği](#web-kazma--madencilii)
- [Özellikler](#özellikler)
- [Bloglar](#blogs)

### Araçlar

#### Javascript

- [selenium-webdriver](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) - Selenium projesinden resmi WebDriver JavaScript bağlamaları.
- [WD](https://github.com/admc/wd) - WebDriver/Selenium 2 node.js client.
- [WebdriverIO](http://webdriver.io) - Önceden tanımlanmış 50'den fazla eylemle WebDriver bağlamalarının daha iyi uygulanması.
- [Zombie.js](http://zombie.js.org/) - Delicesine hızlı, headless full-stack testing.
- [SlimerJS](http://slimerjs.org/) - Web geliştiricileri için script yazılabilir bir tarayıcı.
- [Nightwatch](http://nightwatchjs.org/) - Verimli ve basit Javascript Uçtan Uca testler.
- [Karma](http://karma-runner.github.io/0.12/index.html) - Unit testing için geliştiricilere verimli bir test ortamı sağlar (çoğunlukla AngularJS).
- [Protractor](https://angular.github.io/protractor/) - Protractor AngularJS uygulamaları için uçtan uca bir test frameworküdür.
- [CodeceptJS](http://codecept.io/) - NodeJS için modern çağ Acceptance Testing frameworkü.

#### Ruby

- [Selenium ile Ruby](http://seleniumhq.github.io/selenium/docs/api/rb/index.html) - Selenium Ruby bağlamaları
- [Watir](http://watir.github.io) - Zarar vermeyen otomatik test
- [Anemone](https://github.com/chriskite/anemone) - Anemon web-spider framework.
- [Mechanize](http://docs.seattlerb.org/mechanize/) - Websiteler ile etkileşimi otomatize etmek.
- [Spidr](https://github.com/postmodern/spidr) - Bir siteyi, birden çok domaini, belli linkleri veya limitsiz sayıda linki crawl edebilen web spidering kütüphanesi.
- [cobweb](https://rubygems.org/gems/cobweb) - Son derece büyük siteleri hızlı bir şekilde taramak için taramaları kümelemek için resque kullanabilen web tarayıcısı.
- [Capybara](https://rubygems.org/gems/capybara) - Rack tabanlı web uygulamaları için bir entegrasyon test aracı. Bir kullanıcının bir web sitesiyle nasıl etkileşime gireceğini simüle eder.

#### PHP
- [Facebook WebDriver](https://github.com/facebook/php-webdriver) - Webdriver için bir PHP client'ı.
- [Selenium Setup](https://github.com/bogdananton/Selenium-Setup) - PHP geliştiricilerinin kendi Selenium sunucularını başlatmaları için bir araç.
- [Steward](https://github.com/lmc-eu/steward) - PHP-webdriver'ı PHPUnit ile entegre eden bir test çalıştırıcısı.

#### Python

- [Selenium ile Python](http://selenium-python.readthedocs.io/) - Selenium Python bağlamları
- [Helium](https://github.com/mherrmann/selenium-python-helium) - Helium, Selenium'un kullanımını daha kolay ve hızlı hale getirir
- [Selene](https://github.com/yashaka/selene) - Selenide'den ilham alan özlü ve okunabilir otomatik test frameworkü, Selenide gibi Ajax'ı da destekler.
- [mechanize](http://wwwsearch.sourceforge.net/mechanize/) - Durum bilgisi olan programlı web taraması.
- [Robot](http://robotframework.org/) - Robot Framework, kabul testi ve ATDD için genel bir test otomasyon frameworkü.
- [behave-webdriver](https://github.com/spyoungtech/behave-webdriver) Selenium ve Python ile davranış odaklı testler.

#### Java

- [Selenium ile Java](http://seleniumhq.github.io/selenium/docs/api/java/index.html) - Selenium Java bağlamları
- [Conductor](http://conductor.ddavison.io) - Test yazmayı çok kolay hale getiren turbo-boosted Selenium frameworkü.
- [darcy](https://github.com/darcy-framework/darcy-webdriver) - Yapılandırılmış, sürdürülebilir otomasyon için sayfa nesnesi frameworkü.
- [Selenide](https://github.com/codeborne/selenide) - Fluent API kullanarak okunması ve bakımı kolay otomatik testler yazmak için bir çerçeve. Selenide, Ajax ve zaman aşımlarıyla ilgili çoğu sorunu çözen bir sihir numarasına sahiptir.
- [Galen Framework](http://galenframework.com/) -Responsive web siteleriniz için otomatik görünüm ve his testi.
- [Serenity](http://www.thucydides.info/) - Daha kaliteli otomatik kabul testlerini daha hızlı yazmak için açık kaynaklı bir kütüphanedir. (Eski adıyla Thucydides).
- [seleniumQuery](https://github.com/seleniumQuery/seleniumQuery) - WebDriver için Java'da jQuery benzeri çapraz sürücü arabirimi. İnce bir katman olarak tasarlanmıştır, gerektiğinde bazı durumları (örn. onaylama/bekleme) daha basit hale getirmek için tek başına veya en sevdiğiniz framework üzerinde kullanılabilir.
- [WebDriverManager](https://github.com/bonigarcia/webdrivermanager) - Selenium WebDriver ikili(binary) dosyalarının otomatik yönetimi.
- [Lightning](https://github.com/aerokube/lightning-java) - Hafif ve yıldırım hızında WebDriver istemcisi.

#### C#

- [Selenium ile C#](http://seleniumhq.github.io/selenium/docs/api/dotnet/index.html) - Selenium C# bağlamaları
- [Atata](https://github.com/atata-framework/atata) - Selenium WebDriver'a dayalı otomatik web testi tam özellikli framework.
- [Strontium](https://github.com/jimevans/strontium) - Selenium/WebDriver (Uzak) Sunucusu için bir .NET uygulaması (ancak eski)

#### Groovy

- [Geb](http://www.gebish.org/) - Scripting, kazıma ve genel otomasyon için veya aynı şekilde Spock, JUnit ve TestNG gibi test çerçeveleriyle entegrasyon yoluyla işlevsel/web/kabul testi çözümü olarak kullanılabilir.

#### Dart

- [dart.webdriver](https://github.com/google/webdriver.dart) -  Dart için WebDriver bağlamaları sağlar. Bunlar WebDriver JSON interface kullanır ve bu nedenle WebDriver uzak sunucusunun kullanılmasını gerektirir.

### CSS Regresyon Testi

- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) -[WebdriverIO](http://webdriver.io) için regresyon test aracı. (şu anda kullanımdan kaldırıldı, şu an için lütfen [wdio-screenshot](https://www.npmjs.com/package/wdio-screenshot) kullanın).

### Konteynerler(Docker vb.)

#### Docker

- [elgalu/docker-selenium](https://github.com/elgalu/docker-selenium) - Chrome ve Firefox ile Docker'da Selenium kullanımı ve buna ek olarak video kayıt desteği.
- [Ggr](https://github.com/aerokube/ggr) - Büyük Selenium kümeleri oluşturmak için kullanılan hafif bir yük dengeleyici(load-balancer).
- [SeleniumHQ/docker-selenium](https://github.com/SeleniumHQ/docker-selenium) - Chrome ve Firefox ile Selenium Bağımsız Sunucu, Hub ve Düğüm(Node) yapılandırmaları için Docker görüntüleri.
- [Selenoid](https://github.com/aerokube/selenoid) - Docker konteynerlerinde tarayıcıları başlatan hafif bir Selenium hub uygulaması.
- [zalando/zalenium](https://github.com/zalando/zalenium) - Herkesin tek kullanımlık ve esnek bir Selenium Grid altyapısına sahip olmasını sağlar
- [bravostudiodev/bravo-grid](https://github.com/bravostudiodev/bravo-grid) - Uzaktan Sikuli test/otomasyon yürütme ve grid düğümü dosya yükleme/indirme desteği sağlamak için Selenium Grid Extras için Docker görüntüsü/kurulumu (Selenium Grid bölümüne bakın).

#### Kubernetes
- [kubernetes/examples](https://github.com/kubernetes/examples/tree/master/staging/selenium) - Bir Kubernetes kümesinde Selenium Hub ve Node'ların örnek dağıtımı.
- [Moon](https://github.com/aerokube/moon) - Tarayıcıları başlatmak için Kubernetes kullanan ticari bir kapalı kaynaklı kurumsal Selenium uygulaması.
- [Callisto](https://github.com/wrike/callisto) - Kubernetes'te tarayıcıları başlatmak için açık kaynaklı bir araç. Her selenium oturumu(session) için ayrı oluşturulur.
- [WebGrid](https://github.com/TilBlechschmidt/WebGrid) - Açık kaynaklı, merkezi olmayan, ölçeklenebilir ve sağlam bir selenium grid eşdeğeri.

### Driver

#### Masaüstü (tarayıcılar)

- [Firefox](https://github.com/SeleniumHQ/selenium/wiki/FirefoxDriver) - Firefox sürücüsü (FF < v48 için), indirmelerde bulunan Selenium-server-standalone.jar dosyasına dahildir.
- [Geckodriver](https://github.com/mozilla/geckodriver) - Selenium >= v3 ile desteklenen Firefox sürücüsü (FF > v48 için)
- [Chrome](https://sites.google.com/a/chromium.org/chromedriver/home) - ChromeDriver, WebDriver'ın Chromium için tel protokolünü uygulayan bağımsız bir sunucudur.
- [Internet Explorer](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver) - InternetExplorerDriver, WebDriver'ın tel protokolünü uygulayan bağımsız bir sunucudur.
- [Edgedriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) - Edge için Microsoft Web sürücüsü sunucusu
- [Safari](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver) - SafariDriver, bir Safari tarayıcı uzantısı olarak uygulanır. Sürücü, geleneksel istemci/sunucu ilişkisini tersine çevirir ve WebSockets kullanarak WebDriver istemcisi ile iletişim kurar (yalnızca Safari <= v9 için desteklenir, macOS Sierra ile gelen tüm yeni Safari sürümleri, Apple tarafından kapalı kaynak olan entegre bir SafariDriver ile birlikte gelir).
- [Opera](https://github.com/operasoftware/operachromiumdriver/blob/master/README.md) - OperaDriver, Opera Software ve Opera için WebDriver API'sini uygulayan gönüllüler tarafından geliştirilen, satıcı destekli bir WebDriver uygulamasıdır.

#### Mobil (tarayıcılar ve uygulamalar)

- [Appium](http://appium.io/) - Appium, yerel ve hibrit mobil uygulamalarla kullanım için açık kaynaklı bir test otomasyon çerçevesidir. WebDriver protokolünü kullanarak iOS, Android Uygulamalarını çalıştırır.
- [Selendroid](http://selendroid.io/mobileWeb.html) - Selendroid, Android enstrümantasyon çerçevesine dayanmaktadır.
- [ios-driver](http://ios-driver.github.io/ios-driver/) - Selenium / WebDriver kullanarak herhangi bir IOS yerel, karma veya mobil web uygulamasını test edin.
- [WebDriverAgent](https://github.com/manishPatwari/WebDriverAgent) - iOS için bir WebDriver sunucusundan WebDriver API aracılığıyla uzaktan kontrol cihazlarına.

#### Masaüstü GUI Otomasyonu (tarayıcı merkezli olmayan)

- [WinAppDriver](https://github.com/Microsoft/WinAppDriver) - Windows uygulama otomasyonu için Microsoft'un WebDriver uygulaması.
- [Winium](https://github.com/2gis/Winium) - Windows platformları için otomasyon çerçevesi. Ücretsizdir. Açık kaynak kodludur. Selenyum bazlıdır. Destekler: Windows Masaüstü (WPF, WinForms); Windows Phone için Windows Mağazası veya Evrensel Uygulamalar; Windows Phone Silverlight Uygulamaları.
- [QtWebDriver](https://github.com/cisco-open-source/qtwebdriver) - Qt tabanlı GUI uygulamalarını otomatikleştirmek için WebDriver'ı kullanmak için.
- [AutoItDriverServer](https://github.com/daluu/AutoItDriverServer) - (Uzak)WebDriver API aracılığıyla AutoIt'i kontrol etmek/sürmek için Selenium sunucusu.
- [AutoPyDriverServer](https://github.com/daluu/AutoPyDriverServer) - (Uzak)WebDriver API aracılığıyla AutoPy'yi kontrol etmek/sürmek için Selenium sunucusu.
- [Appium for Mac](https://appium.io/docs/en/drivers/mac/) - Mac OS X masaüstünü otomatikleştirmek için Appium/WebDriver uygulaması.
- [SilkAppDriver](https://github.com/MicroFocus/SilkAppDriver) - (Uzaktan)WebDriver API aracılığıyla ticari SilkTest platformunu kontrol etmek/sürdürmek için Selenium sunucusu.

### Masaüstü Araçları

- [SWET](https://github.com/sergueik/SWET) - Aynı işlevsellik için SWD Sayfa Kaydedici'nin varisi.
- [Looking Glass](https://github.com/dmolchanenko/LookingGlass) - Tarayıcılar arası öğe denetçisi ve Selenium kod üreteci sunan Java uygulaması.
- [Ranorex Selocity](https://www.ranorex.com/selocity/browser-extension/) - Ranorex'in yaratıcılarından tarayıcı öğesi denetimi için bir Firebug/FirePath/Firefinder ve Selenium IDE alternatifi.
- [Silk WebDriver](https://www.microfocus.com/products/silk-portfolio/silk-webdriver/) - SilkTest'in yaratıcılarından kayıt, oynatma ve komut dosyası dışa aktarma için bir Selenium IDE alternatifi.
- [Fire IE Selenium](https://code.google.com/archive/p/fire-ie-selenium/) - Internet Explorer tarayıcısı için öğe denetimi sağlayan Microsoft Excel tabanlı araç.

### Selenium Grid

- [Selenium Grid Extras](https://github.com/groupon/Selenium-Grid-Extras) - Video kaydı gibi temel Selenium Gridinin ötesinde ek özellikler sağlayan bir framework.
- [SeLion](https://github.com/paypal/SeLion) -(Java) Temel Selenium Grid işlevselliğinin ötesinde, özellikle kararlılık iyileştirmeleri vb. gibi ek özelliklerle Selenium testlerini çalıştırmak için kütüphane.
- [Selenium Grid Extensions](https://github.com/sterodium/selenium-grid-extensions) - Sikuli testlerini/otomasyonunu uzaktan çalıştırma, bir grid düğümüne dosya yükleme/indirme gibi ek özellikler sağlayan Selenium Grid için bir dizi uzantı.

### Bulut Hizmetleri

- [Sauce Labs](https://saucelabs.com) - Çapraz tarayıcı testi harika oldu. 300'den fazla işletim sistemi/tarayıcı platformunda selenyum testi, mobil test, JS birim testi. Ücretsiz başlayın.
- [HeadSpin](https://www.headspin.io/) - Gerçek tarayıcılar çalıştıran binlerce gerçek cihazda web sitenizi çapraz tarayıcı uyumluluğu açısından test edin. Bulutta birden çok masaüstü ve mobil tarayıcıya anında erişim sağlayın. Ücretsiz deneme alın.
- [Browserstack](https://www.browserstack.com/) - Web sitenizi gerçek tarayıcılarda çapraz tarayıcı uyumluluğu açısından test edin. Birden çok masaüstü ve mobil tarayıcıya anında erişim. Ücretsiz deneme alın.
- [LambdaTest](https://www.lambdatest.com/selenium-automation) - Web sitenizi 2000'den fazla gerçek tarayıcı ve işletim sisteminde çapraz tarayıcı uyumluluğu açısından test edin. Ücretsiz deneme alın.
- [TestingBot](https://testingbot.com) - TestingBot, bulutta Selenium ile kolay çapraz tarayıcı testi sağlar.
- [Moon Cloud](https://aerokube.com/moon-cloud/) - Dakika başına faturalandırma ve sınırsız sayıda tarayıcı ile genel bulut platformunda özel Selenium kümeniz.
- [Mail7](https://www.mail7.io/) - E-posta iş akışı testini otomatikleştirmek için tek kullanımlık e-posta hizmeti, [Bu döküman](https://docs.mail7.io/tutorials/registration-and-login-automation-using-selenium-with-disposable-email) Mail7'nin Selenium ile nasıl uygulanacağını(implemente edileceğini) açıklar.
- [Thundra Foresight](https://www.thundra.io/foresight) - Test hatalarını anında tespit ederek test takımlarınıza bir görünürlük aracı.

### Cihaz Farmları(Device Farms)

- [OpenSTF](https://github.com/DeviceFarmer/stf) - Android'e ve aynı zamanda iOS'a yönelik kendi cihaz çiftliğinizi çalıştırmak için bir framework.

### Web Kazıma / Madenciliği

- [Scrapy](http://scrapy.org) - **Python**, daha çok bir kazıyıcı/madenci - hızlı, iyi dökümante edilmiş ve [Django Dynamic Scraper](http://django-dynamic-scraper.readthedocs.org/en/latest/) ile bağlanabilir, güzel madencilik deploymentları için veya [Scrapy Cloud](http://scrapinghub.com/scrapy-cloud.html) PaaS (sunucusuz) deploymentları için, terminalde veya tek başına(standalone) sunucu işleminde, **Celery** ile kullanılabilir, **Twisted** üzerine kurulmuştur.
- [Node-Crawler](https://github.com/sylvinus/node-crawler) - **Node.js**, NodeJS + sunucu tarafı jQuery için Web Crawler/Spider.

### Özellikler

- [The WebDriver Wire Protocol](https://www.selenium.dev/documentation/legacy/json_wire_protocol/) - Tarayıcıyla veya bir RemoteWebDriver sunucusuyla iletişim kuran tüm WebDriver uygulamaları, ortak bir kablo protokolü kullanacaktır.
- [WebDriver](http://www.w3.org/TR/webdriver/) - Bu spesifikasyon, programların veya komut dosyalarının bir web tarayıcısına göz atmasına ve davranışını kontrol etmesine izin veren bir platform ve dilden bağımsız arabirim ve ilişkili kablo protokolü olan WebDriver API'sini tanımlar.

### Bloglar

- [Official Selenium Blog](https://www.selenium.dev/blog/) - SeleniumHQ'nun resmi blogu.
- [Elemental Selenium](http://elementalselenium.com/) - Selenium'un bir Profesyonel gibi nasıl kullanılacağına anlatan ücretsiz, haftada bir e-posta.
- [SauceLabs Blog](https://saucelabs.com/blog) - SauceLabs küratörlüğünde blog.

## Lisans

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

Kanunen mümkün olduğu ölçüde, [Christian Bromann](http://www.christian-bromann.com/) bu çalışmaya ilişkin tüm telif haklarından ve ilgili veya komşu haklardan feragat etmiştir.