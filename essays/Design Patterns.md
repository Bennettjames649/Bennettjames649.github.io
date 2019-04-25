---
layout: essay
type: essay
title: Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2019-04-24
labels:
  - Software Engineering
  - Learning
  - Design Patterns
---

Common Problems
 When designing a program there are often problems that require the same set of steps to be called in a certain sequence. For example, a calculator configured with order of operations will go through a predetermined sequence of checks before giving you your final result. In this example the calculator is solving a math problem, but rather than simply doing exactly what the operators say to do in order, it has its own internal logic for the situation. Such function was designed and implemented specifically for this particular function of doing math with order of operations. 
 
 Common Solutions
 By creating a general solution a specific problem, we allow our code to be reusable in multiple different aspects. This general design process is a design pattern waiting to be implemented. Going back to our calculator example, there are a few things we must ask ourselves. First, what problem are we solving? Second, how do you intend to solve this problem? And lastly, are there any repercussions for using this particular implementation? With the calculator, our problem is solving equations using order of operations, our intended solution is to evaluate the equation in the order given by order of operations, and our tradeoff is that this function will only work on math problems. 
 
 Use Cases
 While this gives a general idea of how to solve our problem, it does not ultimately layout exactly how we will reach our solution. Additionally, depending on the problem, there may be more to consider about our function. Different situations require different solutions, and no one single design pattern is going to completely cover all possible scenarios, they key is coming up with a custom design pattern that can be generalized in its usage. For example, I have used a singleton implementation design pattern in a previous class to create objects with certain properties. While it was very useful, it was extremely error unfriendly, as any small error would cause the singleton to  have issues. This design could only be implemented if you set up the program to run in the specific way, meaning that not only was this an incredibly specific use for singletons, but also that the onyl way you could successfully utilize singletons was to plan for it from the start.
 
 While my specific design pattern required extra work, it allowed a more robust usage of the system when everything ran smoothly, even if it did require more memory. While all design patterns solve problems, you should use the one that best fits your specific scenario so that you don't got through a huge amount of effort for what ammounts to a small return.
