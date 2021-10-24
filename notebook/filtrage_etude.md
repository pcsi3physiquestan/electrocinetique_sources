---
jupytext:
  encoding: '# -*- coding: utf-8 -*-'
  formats: ipynb,md:myst
  split_at_heading: true
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
# Filtrage linéaire (2): Etude d'un filtre

````{admonition} Objectifs
:class: tip
* Expliciter les conditions d'utilisation d'un filtre afin de l'utiliser comme moyenneur, intégrateur ou dérivateur
* Relier l'acuité de la résonance au facteur de qualité
* Choisir un type de filtre en fonction des besoins d'un système
* Établir le type de filtre étudié par une étude rapide du système.
````

Cette partie se propose de faire la synthèse des activités précédentes en expliquant les méthodes d'analyse d'un filtre basées sur l'étude de __sa bande passante__ et de son __diagramme de Bode__.

Nous mettrons notamment en avant les caractères __dérivateurs, intégrateurs et moyenneurs__ de certaines filtres.

Les différents types de filtres et leur forme canonique seront présentées. Celà sera aussi l'occasion d'apprendre à choisir un filtre en fonction des besoins ou du __gabarit__ imposé.
