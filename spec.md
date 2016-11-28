# Specification

## Objective

Present authentic climate-science in a substantive, accessible way to
readers of the business press.

## General approach

* Interactivity: engage readers with things to change and explore.
* Visualization: present core ideas in familiar terms.
* Authenticity: base on authentic (traceable, reproducible) science,
  math, simulation etc. Where practical, compute in the
  browser. Access technical detail via mouseovers (or similar).
* Code: client-side, open source and controlled on github (or
  similar); tests for critical functions.
* Format: multiple slides (suitable for serialization); mobile focus.

## Limitations

* Limit to recent browser versions?
* Publisher may close-source some code?
* No server-side computation.

## Content

### Slide 1: Introduction / EBM

* Explain the utility of the EBM.
* Contrast with complex models.
* Why are such models important/pervasive in science and engineering?
* Contents

### Slide 2: Black body radiation

* Interactive example:
  [incandescence](https://en.wikipedia.org/wiki/Incandescence)
  ([spectrum to RGB](http://markkness.net/colorpy/ColorPy.html),
  [color temperature](https://en.wikipedia.org/wiki/Color_temperature)).
* Slider to estimate temperature of sun
  ([effective temperature](https://en.wikipedia.org/wiki/Effective_temperature)).
* What things are approximately black bodies?

### Slide 3: Atmospheric absorption.

* Show Sun's (short-wave) spectrum after simple filter (notch?).
* Extend to filtering Sun's through atmosphere (Something
  like
  [this](https://commons.wikimedia.org/wiki/File:Atmospheric_Transmission.png).)
* Filter Earth's (long-wave) spectrum through atmosphere.
* Qualitatively, enough here to understand greenhouse effect. But,
  for quantitative results, need more...

### Slide 4: Energy balance

* Introduce seesaw-speedo as a proxy for the ODE (below).
* Start without atmosphere, progressively add forcings (borrow ideas
  from http://climateblab.github.io/energy-balance/ ).
* Detail of forcings in mouseovers (or similar).

![](https://github.com/haulashore/mann-threshold/blob/master/seesaw_speedo.png "Seesaw speedo")

### Slide 5: Mann conclusion

* Port Mann's code to javascript.
* Interactive simulation & plot.
* http://climateblab.github.io/dangerous-threshold/
