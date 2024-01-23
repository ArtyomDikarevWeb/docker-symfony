#  Project installing

When you install project first time create **_.env_** from **_.env.dist_** use
```shell
make run
```

after that use
```shell
make up
```
to up containers

You can check other commands in Makefile 
or typing **_make_** in your terminal from root of the project

## Dependencies

This build includes next dependencies from the box:
- [PHPStan](https://phpstan.org/user-guide/getting-started)
- [NelmioApiDocBundle](https://symfony.com/bundles/NelmioApiDocBundle/current/index.html#how-does-this-bundle-work)
- [Symfony test-pack](https://symfony.com/doc/current/testing.html) (that includes [PHPUnit](https://phpunit.de/))