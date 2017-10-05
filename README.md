# magento2-exercises
Exercises for the Test Driven Magento course

## Docker Dev Environment

If you use Docker, a dev environment which is suitable for tests, can be created as follows:

1. Install Magento via composer

       composer create-project --repository-url=https://repo.magento.com/ magento/project-community-edition <installation directory name>
       
   More info: http://devdocs.magento.com/guides/v2.2/install-gde/prereq/integrator_install_ce.html

2. Install the dockerize-magento2 component

       composer require --ignore-platform-reqs tddwizard/magento2-dockerized

    More info: https://github.com/tddwizard/magento2-dockerized
