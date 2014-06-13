# [clojure](http://niquola.github.io/clojure-2014-slides)


# ruby 

Я не буду много говорить про ruby, приведу только историческую справку.

Рабочим названием ruby было MatzLisp. В одной из переписок Матцумото
назвал ruby - lisp for ordinary people.

History (Mon, 13 Feb 2006 13:43:02 +0900)

```
Ruby is a language designed in the following steps:

* take a simple lisp language (like one prior to CL).
* remove macros, s-expression.
* add simple object system (much simpler than CLOS).
* add blocks, inspired by higher order functions.
* add methods found in Smalltalk.
* add functionality found in Perl (in OO way).

So, Ruby was a Lisp originally, in theory.
Let's call it <b>MatzLisp</b> from now on. ;-)

```

# lisp

В нашей достаточно молодой отрасли деятельности не так много шедевров:
unix phylosophy & linux, vim & emacs. 
Среди языков программирования LISP занимает уникальное место.
LISP был придуман MacCarthy в конце 50. Из выживших языков он младше только Fortrana.
MacCarthy создавал его не, как исправление ошибок Fortrana, 
но как попытка аксиоматизации вычесления.
Цитируюя  Paul Grahame: есть две базовые модели для языков - модель C  и модель LIPS.
Последнии 20 лет появляются языки, которые постепенно добавляют идеи из LISP к модели C.

[Paul Grahame about LISP](http://www.paulgraham.com/lisp.html)


[Eric Raymond](http://ru.wikipedia.org/wiki/%D0%A0%D1%8D%D0%B9%D0%BC%D0%BE%D0%BD%D0%B4,_%D0%AD%D1%80%D0%B8%D0%BA) в своем эссэ ["How to Become a Hacker"](http://www.catb.org/esr/faqs/hacker-howto.html) сказал:

> lisp is worth learning for the profound enlightenment experience 
> you will have when you finally get it; that experience 
> will make you a better programmer for the rest of your days, 
> even if you never actually use Lisp itself a lot.


# Clojure

Это современный и практичный диалект LISP, расширенный персистентными (иммутабельными) структурами данных, 
который может исполнятся на JVM, CLR и JS. 
Clojure придумал и реализовал Rich Hickey, на мой взгляд, одна из самых светлых голов в сегоднешнем IT.


# Rationale

Clojure это Lisp для функционального программирования, 
симбиотирующий со взрослой платформай и спроектированный
для Concurency.


Когда мы говорим о языке мы должны задать три основных вопроса:

Каковы примитивы для данных и кода?
Какие есть средства для композиции данных и кода (создания более сложных структур из простейших)?
И какие средства для создания абстракций (выделения общих идей и сокрытия деталей реализации)?

Это можно представить таблицей

| Primitives    | Composition   | Abstracton  |
| ------------- |:-------------:| -----:|
| persistent ds    | dynamic lang | ADT & Protocols with Multhimethod |
| only ~ 10  built ins   | Fun. Comp. unified form      |   Functions & Macro |




