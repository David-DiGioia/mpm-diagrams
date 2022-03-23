# mpm-diagrams

## Introduction

MPM Diagrams is a collection of diagrams and intended to help in understanding concepts related to the material point method (MPM).

Thanks to [Material point method after 25 years: theory, implementation and applications](https://www.researchgate.net/publication/336796234_Material_point_method_after_25_years_theory_implementation_and_applications) and [The Material Point Method for Simulating
Continuum Materials
](http://alexey.stomakhin.com/research/siggraph2016_mpm.pdf) for being the source of much of the information contained in these diagrams.

## Lagrangian and Eulerian coordinates

The set of undeformed material points is called Ω^0 and the set of the "current position" material points called Ω^t.

The <i>material or Lagrangian coordinate</i> is the position vector in the original undeformed space of a material point and is denoted <b>X</b>.

The <i>spatial or Eulerian coordinate</i> is the position vector of the same material point in a deformed configuration and is denoted <b>x</b>.

The mapping between <b>X</b> and <b>x</b> is called phi, and is given by

<b>x</b> = phi(<b>X</b>, t)

![00_lagrangian_and_eulerian_coordinates](00_lagrangian_and_eulerian_coordinates.png?raw=true "00_lagrangian_and_eulerian_coordinates")
