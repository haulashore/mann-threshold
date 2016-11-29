# Specification

This is a specification for a visual, interactive browser-based
explanation of the energy balance climate model (EBM), and of Mann's
conclusions using the model. The emphasis is on showing, rather than
telling. The goal is to give the reader an authentic appreciation of
the principles (i.e., maintaining a genuine connection to the
underlying science).

The approach is based on reproducing Mann's research with a
(coffeescript/javascript) port of his simulation code. This opens many
directions for exploration, and allows readers to experiment with
parameters to gain a tangible feel for the outcomes.

The key technical element is the EBM's differential equation. The
equation itself should be available as a mouseover, but should not
appear at the top level (too intimidating). As a proxy, the
specification proposes a hybrid of a set of scales (to illustrate the
balance) and a speedometer (to show the level of unbalance affects the
rate of change). Even non-technical readers will intuitively
understand the relationship between speed and distance, and we lean on
this to bridge to the ODE. As a bonus, the graphic may be styled to
show that the earth's future is in the balance (which is a key
conclusion of Mann's research).

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

* Introduce balance-speedo as a proxy for the ODE (below).
* Start without atmosphere, progressively add forcings (borrow ideas
  from http://climateblab.github.io/energy-balance/ ).
* Detail of forcings in mouseovers (or similar).

![](https://github.com/haulashore/mann-threshold/blob/master/seesaw_speedo.png "Seesaw speedo")

### Slide 5: Mann conclusion

* Port Mann's code to javascript.
* Interactive simulation & plot.
* http://climateblab.github.io/dangerous-threshold/
