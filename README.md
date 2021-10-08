# laminas-mvc-form

laminas-mvc-form is a Composer metapackage that provides a single package for
installing all packages necessary to fully use [laminas-form](https://docs.laminas.dev/laminas-form)
under [laminas-mvc](https://docs.laminas.dev/laminas-mvc), including:

- [doctrine/annotations](https://www.doctrine-project.org/projects/annotations.html)
- [laminas/laminas-form](https://docs.laminas.dev/laminas-form/)
- [laminas/laminas-i18n](https://docs.laminas.dev/laminas-i18n/)

Install using:

```console
$ composer require laminas/laminas-mvc-form
```

> ### i18n integration
>
> This package only requires laminas-i18n, and not [laminas-mvc-i18n](https://docs.laminas.dev/laminas-mvc-i18n).
> This is to allow providing the bare minimum required to use laminas-form, as its
> base view helper extends from the base laminas-i18n view helper. If you
> want to provide translations for your form elements, please install
> laminas-mvc-i18n as well.
