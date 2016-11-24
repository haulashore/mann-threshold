# Spec

## Objective

Connect the readership of the business press with authentic science.

## Approach

* Interactivity: engage readers with things to change and explore.
* Visualization: present core ideas in familiar terms.
* Authenticity: base on authentic (traceable, reproducible) science,
  math, simulation etc. Where practical, compute in the
  browser. Access technical detail via mouseovers (or similar).
* Code: modeling code (at least) is open source, and controlled on
  github (or similar); tests for critical functions.
* Format: multiple slides; mobile focus; suitable for serialization.

## Limitations

* Limit to modern browsers?
* Publisher may close-source some code?

## Content

### Slide 0: Introduction

* Explain the utility of the EBM.
* Contrast with complex models.
* Why are such models important in science and engineering?
* Outline contents.


### Slide 1: Black body radiation

* Example: coals in a fire; slider changes temperature
  ( [spectrum to RGB](http://markkness.net/colorpy/ColorPy.html) ).
* Slider to estimate temperature of sun
* What things are approximately black bodies?

### Slide 2: Atmospheric absorption.

* Show Sun's (black body) spectrum after simple filter.
* Extend to filtering Sun's through atmosphere (Something like
  https://commons.wikimedia.org/wiki/File:Atmospheric_Transmission.png.)
* Filter Earth's spectrum through atmosphere.
* Qualitatively, enough here to understand greenhouse effect. But,
  for quantitative results, need more...

### Slide 3: Energy balance

* Basic idea = steady-state conservation of energy (?).
* Introduce seesaw-speedo (below).
* Start without atmosphere, progressively add forcings (borrow ideas
  from http://climateblab.github.io/energy-balance/ ).

![](https://github.com/haulashore/mann-threshold/blob/master/seesaw_speedo.png "Seesaw speedo")

### Slide 4: Mann conclusion

* Port Mann's code to javascript.
* Interactive simulation & plot.
* http://climateblab.github.io/dangerous-threshold/
