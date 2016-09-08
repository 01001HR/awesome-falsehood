# Awesome Falsehood [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome falsehoods programmers believe in.


## Foreword

*Falsehood* articles are a form of commentary on a particular subject, and are
appreciated by the developper community at large for their effectiveness and
density. They're a convenient written form to approach an unfamiliar domain by
dispelling myths, point out common pitfalls, show inconsistencies and
subtilities.

They might looks like to some as a suite of wordy unit-tests covering extensive
edge-cases provided by real-world usage.


## What's a good candidate for this awesome list?

### *Falsehood*-like articles

Articles following the *falsehood* scheme are prime candidates for inclusion in
this awesome list.

These articles starts with the hypothesis that developers have a naive, simple
view of the subject at hand. Then procceed to list a set of candid assumptions
that might be held by such programmers. Each one is intentionnaly false, and
sometimes illustrated by a counter-example.

A list of falsehood is crafted as a progression that is designed to refine
concepts. Having read the whole list of falsehood, the reader should pocssess a
global, if not complete, overview of the domain being targetted by the article,
including most, if not all, its pitfalls, edges-cases and inconsistencies.

### Library

When possible, we provide a list of programming libraries or modules that may
solve, or try to, the complexities and idiosyncracies pointed by the
*falsehood* articles above.

### Data structures

Data models and structures generic enough to cover and addresses most of the
falsehoods are also welcome in this page.


## Contents

- [Meta](#meta)
- [Build systems](#build-systems)
- [Dates and time](#dates-and-time)
- [Emails](#emails)
- [Gender](#gender)
- [Geography](#geography)
- [Human names](#human-names)
- [Networks](#networks)
- [Phone numbers](#phone-numbers)
- [Prices](#prices)
- [Postal addresses](#postal-addresses)
- [Versions](#versions)


## Meta

- [Falsehoods Programmers Believe](http://spaceninja.com/2015/12/08/falsehoods-programmers-believe/) - A brief list of common falsehoods. A great overview and quick introduction into the world of falsehoods.


## Build systems

- [Falsehoods programmers believe about build systems](http://pozorvlak.livejournal.com/174763.html)


## Dates and time

- [Falsehoods programmers believe about time](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time) - Seminal article on dates and time.
- [More falsehoods programmers believe about time](http://infiniteundo.com/post/25509354022/more-falsehoods-programmers-believe-about-time) - Part. 2 of the article above.
- [Falsehoods programmers believe about time and time zones](http://www.creativedeletion.com/2015/01/28/falsehoods-programmers-date-time-zones.html) - Another takes on time-related falshoods, with an emphasis on time zones.
- [Falsehoods Programmers Believe About Time](https://gist.github.com/thanatos/eee17100476a336a711e) - A critique of the first article with a very detailed explanation of each falsehood, adding more context and external resource to the subject.


## Emails

- [I Knew How To Validate An Email Address Until I Read The RFC](http://haacked.com/archive/2007/08/21/i-knew-how-to-validate-an-email-address-until-i.aspx/).


## Gender

- [Falsehoods Programmers Believe About Gender](https://gist.github.com/garbados/f82604ea639e0e47bf44)


## Geography

- [Falsehoods programmers believe about geography](http://wiesmann.codiferes.net/wordpress/?p=15187).


## Human names

- [Falsehoods Programmers Believe About Names](https://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/).
- [XKCD #327: Exploits of a Mom](https://xkcd.com/327/).
- [HL7 V3 RIM](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=186): a flexible data model for representing human names.
- [iOS NSPersonNameComponentsFormatter](https://developer.apple.com/library/ios/documentation/Miscellaneous/Reference/NSPersonNameComponentsFormatter_Class/index.html): localized representations of the components of a person’s name.


## Networks

- [Falsehoods programmers believe about networks](http://blog.erratasec.com/2012/06/falsehoods-programmers-believe-about.html)


## Phone numbers

- [`libphonenumber`](https://github.com/googlei18n/libphonenumber): Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers. Also available for [C#](https://github.com/erezak/libphonenumber-csharp), [Objective-C](https://github.com/iziz/libPhoneNumber-iOS), [Python](https://github.com/daviddrysdale/python-phonenumbers), [Ruby](https://github.com/sstephenson/global_phone) and [PHP](https://github.com/giggsey/libphonenumber-for-php).


## Prices

- [Falsehoods programmers believe about prices](https://gist.github.com/rgs/6509585).


## Postal addresses

- [Falsehoods programmers believe about addresses](https://www.mjt.me.uk/posts/falsehoods-programmers-believe-about-addresses/).
- [`libaddressinput`](https://github.com/googlei18n/libaddressinput): Google's common C++ and Java library for parsing, formatting, and validating international postal addresses.
- [`addressing`](https://github.com/commerceguys/addressing): A PHP 5.4+ addressing library, powered by Google's dataset.
- [`postal-address`](https://github.com/scaleway/postal-address): Python module to parse, normalize and render postal addresses.


## Versions

- [Falsehoods programmers believe about versions](https://github.com/xenoterracide/falsehoods/blob/master/versions.md)


## Lisense

Content of this repository is licensed under the [BSD 2-Clause
License](LICENSE.md).
