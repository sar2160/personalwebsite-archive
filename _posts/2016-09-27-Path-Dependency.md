---
layout: post
title: "Adventures in Path Dependency"
---

I read Scott E. Page's article *Path Dependence* for a class and thought it would be fun to model some of his examples.
I can't do justice to the whole article here, but here is the TL:DR summary;

1. start with an urn that has a Maroon ball and a Black ball inside
2. Add/remove balls according to a set of rules
3. Repeat process *t* times and see what proportion of Maroon / Black you end up with

*Fun Aside: "Maroon" sounds like "Market". Black is alliteratively close to "Bureaucratic"*

Here's some examples:

### Polya Process:

Pick a random ball (and then return it), add a ball of the same color to the urn. This process quickly converges to a steady percentage of Maroon balls, dependent on the initial few iterations. The first few times determines the outcome forever.

<img src="assets/polya.gif" alt="A polya process" style= "width: 400px;" align="center"/>


### Balancing Process:

Pick a random ball (and return it), add a ball of the opposite color to the urn. As the name implies, this process converges to an approximately even balance of Maroon and Black balls.

<img src="assets/balancing.gif" alt="A balancing process" style= "width: 400px;" align="center"/>


### Biased Polya Process:

Same as the Polya process, but we start with two Black balls and only one Maroon ball. This imbalance is enough
to cause the urn to fill overwhelmingly with Black balls over time.

<img src="assets/biased_polya.gif" alt="A biased polya process" style= "width: 400px;" align="center"/>


Page describes many other processes that are more interesting and I have yet to get to all of them. Maybe over time. I find the exercise to be a very useful way to look at the spread of social institutions over time.
