---
layout: other
title: 'Where does a dollar go? A data-driven flow diagram of wealth in America'
date: 2024-08-18
permalink: /portfolio/where_does_dollar_go/
tags:
  - Macroeconomics
  - Wealth inequality
  - Economic sustainability
  - Data-driven differential equations
---

## Introduction
I had a craving for a crisp apple. At my grocer after a run on a hot summer day, the single piece of produce rang to exactly $1. Staring at the unlikely round price, my mind went to who that dollar paid: surely the grocer, the trucking company that delivered it, the orchard that produced it, and likely a number of financial institutions along every step. But these were businesses, not people. At the grocer you have the clerk (who was currently staring at my immobile self, frozen by the beauty of complexity), but also a myriad of employees stocking shelves, cleaning floors; the business owner who pays their costs e.g., advertisements, utilities, loans, and all their associated employees and liabilities. One could recursively enumerate the fractions of fractions of a penny that go to e.g., "financial organization H" who provided a loan 20 years ago to the utility company that kept the lights on during my 3 minute trip to the store, but I had lost the thread.

_Who_ was paid by my purchase could be rephrased in a more meaningful (and perhaps tractable) question: _What socioeconomic stratums are paid by a purchase, and for each, how much?_

It occurs immediately that this framing of the problem has implications far beyond my apple, essentially providing a time-derivative of our country's wealth distribution. The leading order analysis is well understood in the implicit statement of acceleration in the colloquialism "the rich get richer" - that is, that the wealthy obtain additional wealth at a faster rate than the poor obtain a proportionate amount. However, a mechanistic explanation had not (to my knowledge) been investigated. Knight in 1954(?) provided a sketch of a circular economy, introducing a schematic of how money circulates between businesses, individuals, and the government. It is exactly this type of diagram I seek to produce, but rather than a coporate-centric viewpoint, I want to understand the flow of wealth between layers of wealth in our society. Further, I wanted to go beyond schematics and attempt to parameterize connections between entities, providing a very lumped estimate to my original question.

My original hope was to parameterize - via digging through _many_ SEC disclosures - this flow of wealth for any given product. And while this is still possible, and likely interesting on a per-business level, it fails to provide insights that cut across sectors, which likely differ heavily (see e.g., agriculture and technology).

However, if we relinquish the hope of a fully descriptive mechanistic model of the economy, one could parameterize a very reduced model, where all businesses are aggregated and serve as an intermediary to redistribute capital between the economic classes.

The creation and learning of this model, with particular emphasis on estimating the flows of wealth, is the main study of this article. We proceed in a series of model enrichment, beginning with the coarsest model possible, and gradually adding data-driven mechanisms that allow finer understanding of the flows of wealth.


## Definitions
We must first admit a series of definitions to set the analysis on firm (if disputable) footing.

First and foremost, what is wealth and who can own it? One might point to income, or net worth, or GDP per capita