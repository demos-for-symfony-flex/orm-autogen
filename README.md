# [symfony-flex-demo](https://symfony-flex-demo.github.io)/orm-autogen

[![Build Status](https://travis-ci.org/symfony-flex-demo/orm-autogen.svg?branch=master)](https://travis-ci.org/symfony-flex-demo/orm-autogen)

* *[Databases and the Doctrine ORM](https://symfony.com/doc/current/doctrine.html)*
* *[The Dotenv Component](https://symfony.com/doc/current/components/dotenv.html)*

## TODO
* Entities like in https://auth0.com/blog/symfony-tutorial-building-a-blog-part-1/

## Done
* .env.dist is no more contaminated, but default values are no more added in `.env`, using an empty framework-bundle section.
```sh
###> symfony/framework-bundle ###
###< symfony/framework-bundle ###
```

## CRUD
* [ERROR] Missing packages: to use the make:crud command, run:
  * composer require annotations form validator twig-bundle security-csrf
    * sensio/framework-extra-bundle
    * symfony/form
    * symfony/validator
    * symfony/twig-bundle
    * symfony/security-csrf


## Bugs in symfony/demo
* sqlite files in var/data: does this directory exist?
* .env.dist has been contaminated
