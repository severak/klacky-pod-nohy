v čem mi hází Symfony framework (a [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) přístup obecně)

# klacky pod nohy

# Co se mi nelíbí

- předně [#21343](https://github.com/symfony/symfony/issues/21343)
- filozofie *thin controllers and fat models* (mám tendenci to psát naopak)
- špatně strukturovaná dokumentace (příklady dobré: [Flourish](http://flourishlib.com/docs/HowDoI), [SS64](https://ss64.com), [Lua manuál](http://www.lua.org/manual/5.1/manual.html) + [PiL](http://www.lua.org/pil/contents.html))
- [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping), zde konkrétně Doctrine
- obálkové třídy na pole, [ArrayObject](http://php.net/manual/en/class.arrayobject.php)y všeho druhu (všude, kde se to používalo jsem nakonec dospěl k psaní metody na jejich rozbalování na obyčejnou `array`)
- [The Bundle System](https://symfony.com/doc/current/bundles.html) protože znepřehledňuje strukturu aplikace
- FOSUserBundle - proč? [proto](https://jolicode.com/blog/do-not-use-fosuserbundle)
- tři různé formáty configů, protože přináší zmatek do dokumentace
- vůbec je configů [nějak moc](https://github.com/severak/klacky-pod-nohy/blob/master/1aizha.jpg), to způsobuje nepředvídatelnost chování aplikace
- [systém událostí](http://symfony.com/doc/current/event_dispatcher.html). Tohle bylo zlo už za Drupalu.
- přidat entitu, controller a formulář je stejně pracný jako začínat nějakej malej projekt mimo (proto generování boilerplate)

## Co se mi naopak líbí

(natolik, že bych se to nebál použít ve vlastních aplikacích)

- Symfony router
- Twig
- předvídatelný autoloader (díky použití composeru)
- DIčko, ale jen používání
