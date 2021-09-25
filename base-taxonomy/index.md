---
layout: page
title: Taxonomy
description: A taxonomy of machine learning models of source code.
---
A probabilistic model of source code is a probability distribution 
over code artifacts. To group these family of models
in terms of shared design choices,
we separate these models into three categories,
based on the form of the equation of the modeled probability 
distribution and their inputs and outputs. Some models fall into multiple categories
because decompositions of their equations fall into different categories.


 * [**SQL Parsing**]({% link base-taxonomy/sql_parsing.html %}) involves converting a natural language query into its equivalent SQL query which can be run over given databases to obtain the answer from the output denotation.

 * [**Representational Models of Code**]({% link base-taxonomy/representational.html %}) take an abstract
    representation of 
    code as input.  Example representations include token contexts or data flow.
    The resulting model yields a conditional probability distribution over code
    element properties, like the types of variables, and can predict them.

 * [**Pattern Mining Models**]({% link base-taxonomy/pattern.html %}) infer, without supervision, a likely latent
    structure within code. These models are an instantiation of clustering
    in the code domain; they can find reusable and human-interpretable patterns.

