# orm

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

## Bugs in symfony/demo
* sqlite files in var/data: does this directory exist?
* .env.dist has been contaminated
