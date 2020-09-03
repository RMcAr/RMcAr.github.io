---
layout: post
title:      "Enter your title here"
date:       2020-09-03 12:33:46 +0000
permalink:  enter_your_title_here
---


The content of What is a Box Cox Transformation?
A Box Cox transformation is a way to transform non-normal dependent variables into a normal shape. Normality is an important assumption for many statistical techniques; if your data isn’t normal, applying a Box-Cox means that you are able to run a broader number of tests.

The Box Cox transformation is named after statisticians George Box and Sir David Roxbee Cox who collaborated on a 1964 paper and developed the technique.

Running the Test
At the core of the Box Cox transformation is an exponent, lambda (λ), which varies from -5 to 5. All values of λ are considered and the optimal value for your data is selected; The “optimal value” is the one which results in the best approximation of a normal distribution curve. The transformation of Y has the form:
boxcox formula 1


This test only works for positive data. However, Box and Cox did propose a second formula that can be used for negative y-values:
boxcox formula2


The formulae are deceptively simple. Testing all possible values by hand is unnecessarily labor intensive; most software packages will include an option for a Box Cox transformation, including:

R: use the command boxcox(object, …).
Minitab: click the Options box (for example, while fitting a regression model) and then click Box-Cox Transformations/Optimal λ.your blog post goes here.
