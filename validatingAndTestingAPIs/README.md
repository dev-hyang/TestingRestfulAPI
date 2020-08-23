Excises for the course
# How to install PHP [Composer.phar](https://getcomposer.org/download/)

## How to install [Behat](https://docs.behat.org/en/latest/quick_start.html)

## How to install [Guzzle](http://docs.guzzlephp.org/en/stable/overview.html#installation)

## What's [Gherkin & Cucumber?](https://cucumber.io/docs/gherkin/reference/)


After you install Composer.phar, cd > into directory and just copy vendor/bin/behat in the command line, the compiler will compile and execute the .feature files by itself and also let you know what functions are expected there in the /features/bootstrap/FeatureContext.php
> behat.yml is a configuration file which could set external parameters for construct() function in FeatureContext.php file. Like set the global username/password for authentication api testing.
> composer.json is a json file specifies the plugins you installed in the composer
> composer.lock
> composer.phar is a exectuable file which could be used to install plugins: syntax is php composer.phar require xx xxVersion
