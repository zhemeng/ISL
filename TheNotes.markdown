## An Introduction to Statistical Learning

by Gareth James • Daniela Witten • Trevor Hastie • Robert Tibshirani

### Chapter 1: Introduction

### Chapter 2: Statistical Learning
* pg 17: General form: ![](https://latex.codecogs.com/gif.latex?Y%20%3Df%28X%29&plus;%5Cepsilon), where ![](https://latex.codecogs.com/gif.latex?%5Cepsilon) is a random error term. There are two main reasons that we may wish to estimate ![](https://latex.codecogs.com/gif.latex?f): prediction and inference.
* pg 18: Variability associated with ![](https://latex.codecogs.com/gif.latex?%5Cepsilon) also affects the accuracy of our predictions. This is known as the irreducible error, because no matter how well we estimate ![](https://latex.codecogs.com/gif.latex?f), we cannot reduce the error introduced by ![](https://latex.codecogs.com/gif.latex?%5Cepsilon).
* pg 25: ![](https://github.com/zhemeng/markdown_attachments/blob/master/Screen%20Shot%202019-09-21%20at%203.48.37%20PM.png  | width=100)
The Trade-Off Between Prediction Accuracy and Model Interpretability: as the flexibility of a method increases, its interpretability decreases.
* pg 
* pg 67: Private methods are defined within a constructor or another method, but not available externally through any instance.
* pg 68: Privileged methods are defined within the constructor using the `this` keyword, and can access private methods while being publicly accessible.
* pg 70: When you declare function `foo() { ... }`, you can call the function before its definition. If you use var `foo = function() { ... }`, you can't.
* pg 74: When a method of an object is used as an event handler, you can bind `this` to the object again using `call` or `apply`.
