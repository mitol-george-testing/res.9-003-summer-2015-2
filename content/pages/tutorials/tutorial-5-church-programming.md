---
content_type: page
is_media_gallery: true
parent_title: Tutorials
parent_uid: 1991b27f-a447-8dc0-a6a2-79748088784f
title: 'Tutorial 5: Church Programming'
uid: 32907aca-b7d5-1972-49b3-b36fb769ce08
---

Tutorial Overview
-----------------

| ![Diagram with photos of three types of stacked objects—dishes in a sink, stable tower of blocks and collapsing unstable tower of blocks.](BASEURL_PLACEHOLDER/resources/tutor5) | Josh Tenenbaum and colleagues propose that our intuitions about properties like the stability of a stack of blocks, may derive from "probabilistic programs" that can simulate, with some uncertainty, the physics that governs how objects behave in space and time. Such programs can be implemented and tested using probabilistic programming languages such as the Church language. (Image courtesy of Josh Tenenbaum, used with permission.) 

The unit on modeling human cognition introduced a framework based on the creation of generative models of the physical and social worlds that enable probabilistic inference about objects, agents, and events. The Church programming language was designed to facilitate the implementation and testing of such models. In this tutorial, you will first learn the syntax and some basic primitives of the Church language, and how to define functions that implement simple probabilistic models and inference methods. The concepts are then explored through examples such as hypothesis testing in the domain of coin-flipping, and reasoning about the goals and beliefs of an agent.

Unit Activities
---------------

### Useful Background

*   Introductions to probability and probabilistic approaches to modeling behavior
*   [Video lectures]({{< baseurl >}}/pages/unit-2.-modeling-human-cognition) on computational models of cognition by Josh Tenenbaum
*   Introduction to computer programming

### Videos and Slides{{< video-gallery-item href="/resources/tutorial-5" section="Tutorial 5: Church Programming" title="Tutorial 5.1: Tomer Ullman - Church Programming Language Part 1" description="Description: Learn the Church programming language, which facilitates the implementation and testing of generative models of physical and social worlds that enable probabilistic inferences about objects, agents and events. Instructor: Tomer Ullman" thumbnail="https://img.youtube.com/vi/lv3kGg-eRa0/default.jpg" >}} {{< video-gallery-item href="/resources/tutorial-5-1" section="Tutorial 5: Church Programming" title="Tutorial 5.2: Tomer Ullman - Church Programming Language Part 2" description="Description: Learn the Church programming language, which facilitates the implementation and testing of generative models of physical and social worlds that enable probabilistic inferences about objects, agents and events. Instructor: Tomer Ullman" thumbnail="https://img.youtube.com/vi/Unvy1L_NH0c/default.jpg" >}}
### Code

[Church\_examples (RTF)]({{< baseurl >}}/resources/church_ex) contains the code examples described in the two-part tutorial video. These examples can be executed by copying the code into one of the following Church programming environments. Code can also be written from scratch and modified in these environments:

1.  First edition of the [Probabilistic Models of Cognition](http://v1.probmods.org/) electronic text, cited in the section below on _Future Study_, which includes a separate [Play space](http://v1.probmods.org/play-space.html) where code can be copied, modified, and executed
2.  [webchurch engine](https://github.com/probmods/webchurch) that runs Church code in a web browser, which is available on GitHub for download onto your local computer

### Further Study

Goodman, N. D., and J. B. Tenenbaum. [_Probabilistic Models of Cognition, First Edition_](http://v1.probmods.org/) (electronic).

*   This interactive text introduces many probabilistic modeling techniques and contains an embedded Church programming environment with coding examples throughout the text that can be modified and executed in place. The text also includes a separate [Play space](http://v1.probmods.org/play-space.html) and [Church language reference](http://v1.probmods.org/webchurch/online/ref.html).

Goodman, N. D, and J. B. Tenenbaum. _[Probabilistic Models of Cognition, Second Edition](https://probmods.org/)_ (electronic). With programming exercises written in the web-based probabilistic programming language, [WebPPL](http://webppl.org/).

Goodman, N. D., and A. Stuhlmüller. [_The Design and Implementation of Probabilistic Programming Languages_](http://dippl.org/). (electronic)

*   This online text describes how probablistic programming languages (PPLs) can be embedded in other languages, and introduces the [WebPPL](http://webppl.org) language, a web-based PPL embedded in JavaScript.

[forestdb.org](http://forestdb.org/): A repository of probabilistic models implemented in the Church language

The Church language is one of several probabilistic programming languages. Learn more about such languages at the [Probabilistic-Programming wiki](http://probabilistic-programming.org/wiki/Home).