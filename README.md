# zend-mvc-form

zend-mvc-form is a Composer metapackage that provides a single package for
installing all packages necessary to fully use [zend-form](https://zendframework.github.io/zend-form)
under [zend-mvc](https://zendframework.github.io/zend-mvc), including:

- [zendframework/zend-code](https://zendframework.github.io/zend-code/)
- [zendframework/zend-form](https://zendframework.github.io/zend-form/)
- [zendframework/zend-i18n](https://zendframework.github.io/zend-i18n/)

Install using:

```console
$ composer require zendframework/zend-mvc-form
```

> ### i18n integration
>
> This package only requires zend-i18n, and not [zend-mvc-i18n](https://zendframework.github.io/zend-mvc-i18n).
> This is to allow providing the bare minimum required to use zend-form, as its
> base view helper extends from the base zend-i18n view helper. If you
> want to provide translations for your form elements, please install
> zend-mvc-i18n as well.
