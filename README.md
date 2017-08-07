# Katas we love

This repository is a mix of Papers We Love and katas: a place where to store katas for future reference.

## How-To

  * Create a new header (h3 - `###`) with the title.
  * Create a human-readable description as the body of the element
  * Create a `Tags` element specifying any information about the kata, in machine readable form:
    * comma-separated tags
    * all lowercase
    * prefer using nouns (rather than verbs)
    * Suggestion: 
      * include the topic
      * the author
      * what to learn
      * what to practice
      * the programming language
      * the size of the exercise
      * and anything else that comes to your mind

## Contents

### [Legacy code katas](http://www.devjoy.com/2013/01/legacy-code-katas/)

Take a legacy codebase and refactor to separate the concerns.

The code is small enough to be understood at once, but big enough to add validation, input and output, side effects.

Plus: 

  * Use only automatic refactorings until you have broken the dependencies
  

Tags: legacy-code, richard-dalton, c-sharp, automatic-refactoring, one-day, dependency-breaking-technique, any-language

<hr>

### [aptera/effectively](https://github.com/aptera/effectively)

> These kata illustrate some techinques we can use to stabilize legacy code—the code that works, DON'T TOUCH IT. 

Tags: legacy-code, extract-and-override, static-cling, sprout-method, interface-indirection, john-fazzaro, warren-barnes, j-d-gomes, dependency-breaking-technique

<hr>

### [Agile Software Development In Practice](https://github.com/bkimminich/AgileSoftwareDevelopmentInPractice)

<hr>

### [Numerology](https://github.com/Gianfrancoalongi/incremental_katas/tree/master/Numerology)

An incremental kata to replace some numbers with others, following some rules.

This kata is ideal to practice Rules and Rule Engine

Tags: incremental-kata, rule, business-rule, gianfranco-alongi, number, algorithm, business-code

<hr>

### [Tell don't ask kata](https://github.com/gabrieletondi/tell-dont-ask-kata)

A refactoring kata with nearly perfect code coverage in which the feature envy smell is very strong. Almost all behavior is separated from its data and the domain is anemic.

Tags: refactoring, gabriele-tondi, tell-dont-ask, design-principle, solid, value-object, object-orientation, oop, feature-envy, code-smell, anemic-domain

<hr>

### [Video Store](http://blog.symprise.net/2009/01/14/revisiting-fowlers-video-store-01-object-oriented-syntax/)

A classic legacy-code kata by Martin Fowler.

A 1/2 to 1 day exercise

Tags: refactoring, martin-fowler, classic, video-store, solid, code-smell, object-orientation, oop, half-day, one-day

<hr>

### [Gilded Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata/)

A legacy-code kata by Emily Bache.

The purpose is to add a new feature to a legacy code, with the [optional] restrictions of not changing some elements in the classes.

Tags: legacy-code, emily-bache, github, example, constraint, restriction, c, groovy, java, spock, kotlin, r, smalltalk, typescript, abap, c99, clisp, cpp, csharp, dart, elixir, fsharp, go, haskell, js, perl, perl6, php, plsql, python, ruby, rust, scala, swift

<hr>

### [Greeting kata](https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata)

A greenfield kata to practice specialization and some business rules.

The purpose is to build a new system that can greet differently based on the input. 

> This Kata is designed to help practice what a test of a pure function ought to look like. It is intentionally designed to start with a very easy, non-branching base case which slowly becomes addled with complexity as additional requirements are added that will require significant branching and eventually a pressure to compose additional units.
> 
> This Kata was suggested by Nick Gauthier and inspired a bit by Bob from Exercism.
> 
> This Kata is designed to be used with Detroit-school TDD.

Tags: nick-gauthier, bob, exercism, detroit-school-tdd, outside-in, pure-function, greeting-kata, business-rule

<hr>

