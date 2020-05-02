---
title: PROJECTS 🧰
layout: page
permalink: projects
---

During the last years, I have been contributing to some open-source projects,
most of them related to the orbital mechanics field. So far so good, other
projects I am involved with do not necessary deal with the aerospace world; in
fact some of them are just focused on "coding 4 fun". The following lines show
those projects an a brief description on them.

<br>

<!-- The poliastro project -->
### The poliastro project: astrodynamics with Python
<img class="imgleft" align="left" src="{{ site.url}}/resources/projects/poliastro.png"
style="width:150px; height:200px; margin-right: 30px">

This Python package, who's original author is [**Juan Luis Cano
Rodríguez**](https://github.com/astrojuanlu) enables user to easily perform
orbital mechanics and astrodynamic calculations. For example you can define an
orbit from the usual state vector, COE elements or even retreive it from
official databases (extremely useful when working with asteroids). Furthermore,
its plotting capabilities are really powrful: 2D and 3D with static and
interactive support, solar system plots, porkchops...

I had the opportunity to be one of the GSOC'19 edition students for this
project, who at that moment was workign under the umbrella organization of [Open
Astronomy](openastronomy.org/).

If you want to know more about this project, how to download and contribute,
please refer to its [official source
code](https://github.com/poliastro/poliastro), where you will find also
documentation website link.

<br>

<!-- The astrobook -->
### The astrobook: the open-source book on orbital mechanics
<img class="imgleft" align="right" src="{{ site.url}}/resources/projects/astrobook.png"
style="width:200px; height:200px; margin-left: 30px">

I started this project at November'19 because I liked to have a custom source of
information on orbital and celestial mechanics that could be free to anyone. It
would take the best parts of my favourite books and combine them in such a way
to build the greatest book of all time in the field. Computer algorithms
together with amazing figures are the core of this book.

Everything is done with open-source tools and the whole materials can de freely
downloaded from the [official
repository](https://github.com/astrobook/astrobook). This might become a very
long project but I think it is worht it.

<br>

<!-- Atmopy project -->
### Atmopy: atmospheric models with Python
<img class="imgleft" align="left" src="{{ site.url}}/resources/projects/atmopy.png"
style="width:150px; height:150px; margin-right: 20px">

Durign my GSOC'19 period at poliastro, I implemented two atmospheric models:
COESA62 and COESA76. We usually care about atmosphere models because depending
on their assumptions, different values for density (and therefore drag force)
are obtained as function not only of height but also external factors.
Therefore, air density is a key factor when analyzing orbit perturbations since
it will introduce an altitude decay as time passes. 

My objective with this project is to collect all possible atmospheric models and
implement those in a modern and readable language such us Python. If you are
interested in this project, please refer to the [homepage of the
project](https://github.com/jorgepiloto/atmopy).
