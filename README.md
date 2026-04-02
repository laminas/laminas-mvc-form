# laminas-mvc-form

> ## 🇷🇺 Русским гражданам
> 
> Мы, участники Laminas, родились и живем в разных странах. У многих из нас есть друзья, родственники и коллеги как в России, так и в Украине. Некоторые из нас родились в России. Некоторые из нас живут в России. У некоторых бабушки и дедушки сражались с фашистами во Второй мировой войне. Здесь никто не поддерживает фашизм.
> 
> У одного из нас есть украинская родственница, которая спаслась из дома вместе с сыном. Поезд задержался из-за бомбежки на дороге впереди. У нас есть друзья, которые прячутся в бомбоубежищах. Мы с тревогой ждем весточки от них после воздушных налетов, которые беспорядочно наносят удары и попадают по больницам, школам, детским садам и домам. Мы не берем это из каких-либо СМИ. Мы наблюдаем это напрямую.
> 
> Вы доверяете нам достаточно, чтоб использовать наши программы, и мы просим вас довериться нам вновь. Мы нуждаемся в помощи. Выходите и протестуйте против этой бесполезной войны. Остановите кровопролитие. Скажите "Нет войне!"
> 
> ## 🇺🇸 To Citizens of Russia
> 
> We at Laminas come from all over the world. Many of us have friends, family and colleagues in both Russia and Ukraine. Some of us were born in Russia. Some of us currently live in Russia. Some have grandparents who fought Nazis in World War II. Nobody here supports fascism.
> 
> One team member has a Ukrainian relative who fled her home with her son. The train was delayed due to bombing on the road ahead. We have friends who are hiding in bomb shelters. We anxiously follow up on them after the air raids, which indiscriminately fire at hospitals, schools, kindergartens and houses. We're not taking this from any media. These are our actual experiences.
> 
> You trust us enough to use our software. We ask that you trust us to say the truth on this. We need your help. Go out and protest this unnecessary war. Stop the bloodshed. Say "stop the war!"

> [!CAUTION]
>
> ## Maintenance mode
>
> This package is considered feature-complete, and is now in **security-only** maintenance mode, following a decision by the Technical Steering Committee.
> More information on this decision can be found in a blog post: [Laminas MVC End of Life Schedule](https://getlaminas.org/blog/2026-03-06-laminas-mvc-eol-schedule.html).  
> The security-only status will continue until the security support for PHP 8.4 ends, which will be 31st December 2028.
>
> If you have a security issue, please [follow our security reporting guidelines](https://getlaminas.org/security/).

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
