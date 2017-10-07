# Test Driven Magento: Exercises

Exercises for the Test Driven Magento course. The exercise descriptions are in the [Wiki](https://github.com/tddwizard/magento2-exercises/wiki)

## TDD Katas

To get started with TDD Katas (not Magento), refer to this tutorial: [Get Ready for TDD Katas with PHPUnit + PhpStorm
](https://www.schmengler-se.de/en/2017/01/get-ready-for-tdd-katas-with-phpunit-phpstorm/)

## Docker Dev Environment

If you use Docker, a Magento 2 dev environment which is suitable for tests, can be created as follows:

1. Install Magento via composer

       composer create-project --repository-url=https://repo.magento.com/ magento/project-community-edition <installation directory name>
       
   More info: http://devdocs.magento.com/guides/v2.2/install-gde/prereq/integrator_install_ce.html

2. Install the dockerize-magento2 component

       composer require --ignore-platform-reqs tddwizard/magento2-dockerized

    More info: https://github.com/tddwizard/magento2-dockerized
