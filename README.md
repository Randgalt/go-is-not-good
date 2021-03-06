# What's this

This repository is a list of articles that complain about **golang**'s imperfection.

## Motivation

Seems like complaining about **go**'s flaws is becoming a trend. Any newbie must have a chance to read all the **go**-is-bad arguments before they go too far. So here it is.

## What it's for

This repo is not aimed to offend or insult someone (at least not more than each author does it in its article), especially **golang** itself, its authors and the community. It is for educational purpose only. Any contributor can have an absolutely different point of view.

I don't think anyone would deny that **go** has weaknesses: it certainly has. But how do you know, *is it really a language design flaw or is it just you, doing something completely wrong*? This list here to help you quickly answer the question.

## How to use it

You're writing some code. And suddenly you understand you need something that language can't give you. You go here and check if you're the one with that issue or not. If it's a common issue, it'll be here. Then you decide what to do: choose another tool for your task or go find a better solution or a workaround.

# The List

+ https://cowlark.com/2009-11-15-go/ (David Given, 2009)
  - c-style
  - poor design
  - no constructors
  - no user-type iteration
  - `new` and `make` instead of one
  - stuck in 70's
  - no OOP
  - lack of syntactic sugar
+ https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis, 2010)
  - no language interoperability (only C)
  - no versioning model
  - no OOP
  - has pointers
  - no semicolons at line endings
  - no `this`
  - no overloading
  - no exceptions
+ https://uberpython.wordpress.com/2012/09/23/why-im-not-leaving-python-for-go/ (Yuval Greenfield, 2012)
  - error handling
  - stuck in 70's
  - `panic` instead of exceptions
+ http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King, 2012)
  - un-googlable name
  - stuck in 70's
  - no exceptions
  - is compiled
  - too young
+ http://jozefg.bitbucket.org/posts/2013-08-23-leaving-go.html (Danny Gratzer, 2013)
  - no generics
  - is not extensible
+ http://magicmakerman.blogspot.ru/2013/07/why-googles-go-programming-language.html (Magic Maker Man, 2013)
  - no OOP
  - no asserts
  - has pointers
  - weird mascot (gopher)
+ http://how-bazaar.blogspot.ru/2013/04/the-go-language-my-thoughts.html (Tim Penhey, 2013)
  - error handling
  - inconvenient `range`
  - no generics
+ http://corte.si/posts/code/go/go-rant.html (Aldo Cortesi, 2013)
  - too opinionated
+ http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta, 2014)
  - project layout is bad
  - can't import packages relatively
  - different build approaches
  - no sugar for slices
  - lack of basic data structures
+ http://yager.io/programming/go.html (Will Yager, 2014)
  - no generics
  - no operator overloading
  - nil as a failure marker
  - type inference is too simple
  - no immutables
  - no pattern matching
+ https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman, 2014)
  - ide support is not good
  - GOPATH is a mess
  - pointers are a mess
  - upper-case/lower-case scoping is bad
  - hidden types
  - immature gc
  - hard to extend
  - no exceptions
  - no generics
  - dependency management is a near miss
+ http://dtrace.org/blogs/wesolows/2014/12/29/golang-is-trash/ (Keith Wesolowski, 2014)
  - the worst compiler toolchain ever
  - psuedointellectual arrogance of Rob Pike and everything he stands for
  - confusing and undebuggable
+ https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan, 2014)
  - no decent IDE
  - error handling
  - variable shadowing
  - no generics
  - not-so-obvious slices behaviour
+ http://spaces-vs-tabs.com/4-weeks-of-golang-the-good-the-bad-and-the-ugly/ (Freddy Rangel, 2015)
  - not-so-obvious slices behaviour
  - error handling
  - hard to test, hard to mock
+ https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/ (Kaushal Subedi, 2015)
  - no generics
  - slow json parsing
  - bad dependency management
  - no subpackages
+ http://byrd.im/go-is-poor (Ian Byrd, 2015)
  - slice manipulations are broken
  - nil interfaces are not entirely nil
  - funny variable shadowing
  - no first-class support of interfaces
  - questionable compiler rigidity
  - go generate is a quirk
+ http://www.evanmiller.org/four-days-of-go.html (Evan Miller, 2015)
  - no unused imports
  - too opinionated
  - poor std math lib
  - weird mascot (gopher)
+ http://blog.goodstuff.im/golang (David Pollak, 2015)
  - no immutables
  - too simple
  - stupid syntax
  - too opinionated
  - error handling
  - stuck in 70's
  - no generics
  - method access modifiers (upper/lower case for public/private)
  - no `map` and `filter`
+ http://nomad.so/2015/03/why-gos-design-is-a-disservice-to-intelligent-programmers/ (Gary Willoughby, 2015)
  - too simple
  - no generics
  - bad dependency management
  - stuck in 70's


# Reverse complaints index

It's a reverse complaints index, generated by https://github.com/ksimka/go-is-not-good/blob/master/generator.go (thanks to @capoferro)

+ GOPATH is a mess
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ `new` and `make` instead of one
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ `panic` instead of exceptions
  - https://uberpython.wordpress.com/2012/09/23/why-im-not-leaving-python-for-go/ (Yuval Greenfield 2012)
+ bad dependency management
  - https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/ (Kaushal Subedi 2015)
  - http://nomad.so/2015/03/why-gos-design-is-a-disservice-to-intelligent-programmers/ (Gary Willoughby 2015)
+ c-style
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ can't import packages relatively
  - http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta 2014)
+ confusing and undebuggable
  - http://dtrace.org/blogs/wesolows/2014/12/29/golang-is-trash/ (Keith Wesolowski 2014)
+ dependency management is a near miss
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ different build approaches
  - http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta 2014)
+ error handling
  - https://uberpython.wordpress.com/2012/09/23/why-im-not-leaving-python-for-go/ (Yuval Greenfield 2012)
  - http://how-bazaar.blogspot.ru/2013/04/the-go-language-my-thoughts.html (Tim Penhey 2013)
  - https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan 2014)
  - http://spaces-vs-tabs.com/4-weeks-of-golang-the-good-the-bad-and-the-ugly/ (Freddy Rangel 2015)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ funny variable shadowing
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ go generate is a quirk
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ hard to extend
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ hard to test, hard to mock
  - http://spaces-vs-tabs.com/4-weeks-of-golang-the-good-the-bad-and-the-ugly/ (Freddy Rangel 2015)
+ has pointers
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
  - http://magicmakerman.blogspot.ru/2013/07/why-googles-go-programming-language.html (Magic Maker Man 2013)
+ hidden types
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ ide support is not good
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ immature gc
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ inconvenient `range`
  - http://how-bazaar.blogspot.ru/2013/04/the-go-language-my-thoughts.html (Tim Penhey 2013)
+ is compiled
  - http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King 2012)
+ is not extensible
  - http://jozefg.bitbucket.org/posts/2013-08-23-leaving-go.html (Danny Gratzer 2013)
+ lack of basic data structures
  - http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta 2014)
+ lack of syntactic sugar
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ method access modifiers (upper/lower case for public/private)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ nil as a failure marker
  - http://yager.io/programming/go.html (Will Yager 2014)
+ nil interfaces are not entirely nil
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ no OOP
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
  - http://magicmakerman.blogspot.ru/2013/07/why-googles-go-programming-language.html (Magic Maker Man 2013)
+ no `map` and `filter`
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ no `this`
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
+ no asserts
  - http://magicmakerman.blogspot.ru/2013/07/why-googles-go-programming-language.html (Magic Maker Man 2013)
+ no constructors
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ no decent IDE
  - https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan 2014)
+ no exceptions
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
  - http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King 2012)
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ no first-class support of interfaces
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ no generics
  - http://jozefg.bitbucket.org/posts/2013-08-23-leaving-go.html (Danny Gratzer 2013)
  - http://how-bazaar.blogspot.ru/2013/04/the-go-language-my-thoughts.html (Tim Penhey 2013)
  - http://yager.io/programming/go.html (Will Yager 2014)
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
  - https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan 2014)
  - https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/ (Kaushal Subedi 2015)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
  - http://nomad.so/2015/03/why-gos-design-is-a-disservice-to-intelligent-programmers/ (Gary Willoughby 2015)
+ no immutables
  - http://yager.io/programming/go.html (Will Yager 2014)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ no language interoperability (only C)
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
+ no operator overloading
  - http://yager.io/programming/go.html (Will Yager 2014)
+ no overloading
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
+ no pattern matching
  - http://yager.io/programming/go.html (Will Yager 2014)
+ no semicolons at line endings
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
+ no subpackages
  - https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/ (Kaushal Subedi 2015)
+ no sugar for slices
  - http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta 2014)
+ no unused imports
  - http://www.evanmiller.org/four-days-of-go.html (Evan Miller 2015)
+ no user-type iteration
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ no versioning model
  - https://dzone.com/articles/i-don%E2%80%99t-much-get-go (Jon Davis 2010)
+ not-so-obvious slices behaviour
  - https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan 2014)
  - http://spaces-vs-tabs.com/4-weeks-of-golang-the-good-the-bad-and-the-ugly/ (Freddy Rangel 2015)
+ pointers are a mess
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ poor design
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
+ poor std math lib
  - http://www.evanmiller.org/four-days-of-go.html (Evan Miller 2015)
+ project layout is bad
  - http://blog.mattbasta.com/things_that_make_me_sad_in_go.html (Matt Basta 2014)
+ psuedointellectual arrogance of Rob Pike and everything he stands for
  - http://dtrace.org/blogs/wesolows/2014/12/29/golang-is-trash/ (Keith Wesolowski 2014)
+ questionable compiler rigidity
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ slice manipulations are broken
  - http://byrd.im/go-is-poor (Ian Byrd 2015)
+ slow json parsing
  - https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/ (Kaushal Subedi 2015)
+ stuck in 70's
  - https://cowlark.com/2009-11-15-go/ (David Given 2009)
  - https://uberpython.wordpress.com/2012/09/23/why-im-not-leaving-python-for-go/ (Yuval Greenfield 2012)
  - http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King 2012)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
  - http://nomad.so/2015/03/why-gos-design-is-a-disservice-to-intelligent-programmers/ (Gary Willoughby 2015)
+ stupid syntax
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ the worst compiler toolchain ever
  - http://dtrace.org/blogs/wesolows/2014/12/29/golang-is-trash/ (Keith Wesolowski 2014)
+ too opinionated
  - http://corte.si/posts/code/go/go-rant.html (Aldo Cortesi 2013)
  - http://www.evanmiller.org/four-days-of-go.html (Evan Miller 2015)
  - http://blog.goodstuff.im/golang (David Pollak 2015)
+ too simple
  - http://blog.goodstuff.im/golang (David Pollak 2015)
  - http://nomad.so/2015/03/why-gos-design-is-a-disservice-to-intelligent-programmers/ (Gary Willoughby 2015)
+ too young
  - http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King 2012)
+ type inference is too simple
  - http://yager.io/programming/go.html (Will Yager 2014)
+ un-googlable name
  - http://www.darkcoding.net/software/go-lang-after-four-months/ (Graham King 2012)
+ upper-case/lower-case scoping is bad
  - https://rule1.quora.com/Golang-Not-yet (Jordan Zimmerman 2014)
+ variable shadowing
  - https://www.scriptrock.com/blog/our-experience-with-golang (Mark Sheahan 2014)
+ weird mascot (gopher)
  - http://magicmakerman.blogspot.ru/2013/07/why-googles-go-programming-language.html (Magic Maker Man 2013)
  - http://www.evanmiller.org/four-days-of-go.html (Evan Miller 2015)

# Get involved

Feel free to add a PR with a new or old article you found on the internet. The structure is simple, just look at existing entries. Run `make` and check in the resulting `README.md` along with your updated `entries.json`.

```json
{
	"URL": "https://kaushalsubedi.com/blog/2015/11/10/golang-sucks-heres-why/",
	"Author": "Kaushal Subedi",
	"Year":  2015,
	"Complaints":[
		"no generics",
		"slow json parsing",
		"bad dependency management",
		"no subpackages"
	]
}
```

## TODO

+ merge complaints with the same ideas under the same names (make the complaints list smaller)
+ sort reverse index by the number of articles which have that complain (popular complains to the top)
