# Spec

## Objective

Connect the readership of the business press with authentic science.

## Approach

* Interactivity: draw in readers with things to change and explore.
* Visualization: present core ideas in familiar terms.
* Authenticity: base everything on authentic science, math,
  simulation etc. Access to technical detail is via mouseovers (or
  similar).
* Code: modeling code (at least) is open source, and controlled on
  github (or similar); tests for critical functions.
* Format: multiple slides; mobile focus; suitable for serialization.

## Limitations

* Limit to modern browsers?
* Publisher may close-source some code?

## Content

### slide 0: Introduction

* What is it?
* What isn't it?
* Why is it important?
* What is to come?


### Slide 1: Black body radiation

* Use color of coals in a fire.
* Use slider to estimate temperature of sun.
* Convert spectrum to RGB for display ( http://markkness.net/colorpy/ColorPy.html ).
* What things are approximately black bodies?

### Slide 2: Atmospheric absorption.

* Filter Sun's (black body) spectrum with simple filter.
* Extend to filtering Sun's through atmosphere (Something like
  https://commons.wikimedia.org/wiki/File:Atmospheric_Transmission.png. Introduce
  different elements individually?)
* Filter Earth's spectrum through atmosphere.
* Qualitatively, enough here to understand greenhouse effect. But,
  for quantitative results, need more...

### Slide 3: Energy balance

* Basic idea
* Introduce seesaw-speedo.
* Initially, no atmosphere, then add by user selection (borrow
  ideas from http://climateblab.github.io/energy-balance/ ).

![](https://github.com/haulashore/mann-threshold/blob/master/seesaw_speedo.png "Seesaw speedo")


### Slide 4: Mann model

* Explain model extensions.
* Add Mann's forcings.

### Slide 5: Mann conclusion

* Interactive simulation & plot.
* http://climateblab.github.io/dangerous-threshold/
