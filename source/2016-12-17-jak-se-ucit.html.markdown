---
title: Kde a jak se začít učit programovat
date: 2016-12-17 15:42 UTC
layout: post
tags: Programování
author: Zuzka
---

Často dostávám dotazy o tom, kde a jak se má člověk začít učit programovat. Jaký jazyk je nejlepší? Kde seženu dobré zdroje? Mám číst knihy nebo rovnou zkoušet programovat? To jsou vše validní otázky a já na ně rozhodně nemám jedinou správnou odpověď ani nemám patent na rozum, ale ráda bych vám přeci jen sdělila svůj názor z pohledu, jak jsem se programovat učila já, naprostý technický antitalent a sociolog.

##Jaký programovací jazyk?

To je asi nejčastější otázka. Já se učila v Ruby ([https://www.ruby-lang.org/](https://www.ruby-lang.org/])) a nemůžu si to rozhodnutí vynachválit, ačkoliv v Ruby už neprogramuju. Ruby je obecný, dynamický a objektově orientovaný jazyk.
Obecný znamená, že není specificky navržen pro jedno konkrétní použití, ale je možné v něm psát např. webové aplikace, konzolové aplikace, knihovny, hry, … Dynamický znamená, že se nekontrolují typy (např. jestli něco je číslo nebo text) při kompilaci, ale až při běhu programu. To zní asi strašidelně, ale v praxi to znamená, že můžeme psát krásně elegantní syntaxi, která je značně kratší a čitelnější než mají staticky typované jazyky. Objektově orientovaný pak znamená, že se vše točí kolem objektů (oproti tomu ve funkcionálním programování je ve středu funkce, tak jak ji známe z matematiky).
Obdobný jazyk jako je Ruby je pak Python. Nebo pak Javascript. Všechny jsou podle mého názoru super volba pro začátečníky, neboť:

- jsou velice čitelné
- nematou začátečníky spoustou kódu, který “nic nedělá”
- mají super komunitu a velkou spoustu online totoriálů a návodů
- fungují jak na windowsech, macu tak i na linuxu (Javascript funguje v prohlížeči takže nevyžaduje žádný setup a můžete ho zkoušet okamžitě!!)

Oproti tomu, mnozí řeknou, že nejlepší je začít se učit Javu nebo C# a to hlavně proto, že to je dnes standard, který se používá všude. To je pravda, ale jakmile budete znát jeden programovací jazyk, naučit se jiný není takový problém. Rozhodně to není špatná volba a přítomnost explicitně uvedených typů vám naopak může pomoci dělat méně chyb.

Porovnejte si definice třídy v Ruby a v Javě:

![](http://image.slidesharecdn.com/ruby-vs-java-1235028123866125-1/95/ruby-vs-java-7-728.jpg?cb=1235268579)
(vzato z [Ruby vs Java](http://www.slideshare.net/Belighted/ruby-vs-java/7-Ruby_syntax_is_terse_Example)).

Co ale je nutno uznat, jako velké plus, je Visual Studio. Super editor pro C#. Jedná se o nástroj, který začátečníkovi pomůže tím, že mu doplňuje kód, napovídá, opravuje chyby, apod. A v základní verzi, které bohatě stačí, je zdarma! Jinak jde-li o to, zda se učit Javu nebo C#, tak pokud nemáte nic proti Microsoftu, tak rozodně C#. Je to podle mě mnohem lepší jazyk.

Pak tu jsou “specifické” jazyky, jako je třeba na Swift (pro vývoj na iOS), funkcionální jazyky (Haskell, F#, Scala), které já osobně miluju, ale povětšinou není příliš praktické s nimi začínat, neboť většina ukázek v tutoriálech budou nějaké matematické knihovny či práce s daty. Dá se s nimi sice dělat téměř vše, jsou ale trochu náročnější na pochopení, zejména tím, že nejsou objektové a tudiž nemodelujete svět pomocí objektů jako u ostatních zmíněných jazyků. (kde např. knihovní systém naprogramujete tak, že máte knihu jako objekt a tá má nějaké vlastnosti — kdy byla vypůjčena, kdo je její autor, o čem je, apod., dále máte objekt čtěnář, který má jak vlastnosti tak chování, třeba si může knihu půjčit).

Dále existují tzv. low level jazyky, které jsou mnohem “blíže” k počítačům jako takovým a dále k lidem. Děláte v ních totiž více práce, takže máte i větší kontrolu nad tím, co se děje. Například se staráte o uvolňování paměti (v Ruby, Javě, apod. se o to stará garbage collector, který to dělá napozadí za vás). Takovéto jazyky jsou např. C++, Rust a C.

Moje finální rada ale zní, že na jazyku zase tolik nezáleži. Učte se programovací koncepty, základní myšlenky, neučte se syntaxi.

##Kde se učit?

A dostáváme se k té fun části, kde se to mám učit? Sropto k tomu budete potřebovat angličtinu. České zrdoje ani žádné neznám, ani nechci znát (pokud přeci jen je to opravdu problém, něco jsem našla a příkládám na konci článku, ale prosím, naučte se anglicky!).

**Pro Ruby existuje spousta strašně super online kurzů:**

- [https://www.codecademy.com/learn/ruby](https://www.codecademy.com/learn/ruby)
- [https://www.bloc.io/ruby-warrior/#/](https://www.bloc.io/ruby-warrior/#/)
- [https://www.codeschool.com/learn/ruby](https://www.codeschool.com/learn/ruby)

Pro další zdroje, zejména pro dělání webu (pomocí knihovny Ruby on Rails) se podívejte [na můj blog](http://jocellyn.cz/2014/07/09/ruby-on-rails-crossroad.html)

**Pro C# jsem našla:**

- [https://mva.microsoft.com/?lang=cs-cz](https://mva.microsoft.com/?lang=cs-cz) (ha, česky!)
- [https://dotnetcademy.net/CSharp/Beginner](https://dotnetcademy.net/CSharp/Beginner)
- [http://learncs.org/](http://learncs.org/)

**Python:**

- [https://www.codecademy.com/learn/python](https://www.codecademy.com/learn/python)
- [https://developers.google.com/edu/python/](https://developers.google.com/edu/python)

**Javascript:**

- [https://www.codecademy.com/learn/javascript](https://www.codecademy.com/learn/javascript)
- [https://www.udacity.com/course/javascript-basics--ud804](https://www.udacity.com/course/javascript-basics--ud804)
- [https://www.rithmschool.com/courses/javascript](https://www.rithmschool.com/courses/javascript)

Rozhodně si myslím, že je super začít nějakým online kurzem, zkouknout pár videí a až potom sáhnout po pořádné knize či rovnou po kódu. Já miluju programátorské knihy, v mém bytě zabírají asi nejvíce místa ze všeho :) ale myslím, že pro úplné začátečníky je snažší poslouchat a vidět kód s vysvětlením ve videu.

Naprosto nejvíc doporučuju tento kurz o základech programování:

[https://www.lynda.com/Programming-Foundations-tutorials/Foundations-Programming-Fundamentals/83603-2.html](https://www.lynda.com/Programming-Foundations-tutorials/Foundations-Programming-Fundamentals/83603-2.html)
(ano, je placený ale NAPROSTO stojí za to).

Nebo máme super kurz v Czechitas — úvod do programování, který není specifický pro jazyk ale jde tam o základy. Již proběhl např. tady: [http://www.czechitas.cz/uvod-do-programovani-3-12-2016-brno/](http://www.czechitas.cz/uvod-do-programovani-3-12-2016-brno)

A poslední tip je tato boží úvodní kniha, z té jsem se učila prvně já:
[https://pine.fm/LearnToProgram/](https://pine.fm/LearnToProgram/)

A to je vše, pokud máte jakékoliv otázky, klidně mi piště na zuzka@czechitas.cz
