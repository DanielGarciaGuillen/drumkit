# Project Title

This is a Drumkit project based on the 30 days Javascript challenge.

## Getting Started

Just hit the keys of your keyboard and do some music.

## Demo

## [Drumkit](https://danielgarciaguillen.github.io/drumkit/)

![Drumkit](/image/drumkit.png?raw=true "Drumkit")

## Learnings

* How to attach keys to audio with the using data-key="45"/

"Custom data attributes are intended to store custom data private to the page or application, for which there are no more appropriate attributes or elements.

These attributes are not intended for use by software that is independent of the site that uses the attributes.

Every HTML element may have any number of custom data attributes specified, with any value."

* How to listen to events like "keydown" and log them on the console

* How to use ES6 template literals `${e.keyCode}`

* Add class to key inside function with `key.classList.add("playing)`

* Use forEach and ES6 function arrow to add event listener to keys with:
  `key.forEach(key => key.addEventListener('transitioned', removeTransition));`

## Built With

* Vanilla Javascript
* Css
* Html
