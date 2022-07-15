# CS 360 Project 1 Part I: The Metacircular Evaluator

Collaborators: Nakul

Please put anything else you would like us to know here.

## Problem 5: Homework statistics

Please let us know how much time you spent on each problem. You may enter time using any format described [here](https://github.com/wroberts/pytimeparse).

Problem 1: 10m

This problem was relatively simple. We saw that there was a function for primitives. We then just followed the formatting for the already exisiting primitives. The only thing that was a bit troublesome was implementing error. When we added error, it would not even run the tests and give us back the error. We then found out that we had to just put inside a lambda.

Problem 2: 4hr

The reason that this one took a long time was because we were trying to add it as a special definition. So we were trying to define it inside the "Setup-environment" function rather than trying to add it as a special form. We then found out that we had to implement it as a special form. There was one obstacle when trying to add it as a special form. We had trouble trying to return the last item in the list if there was no #t or #f. However the solution was just a nested if statement.

Problem 3: 3hr

This one also took a long time. This was mainly due to a lot of functions that we needed to create and also exisiting functions that we needed to utilize. So if one helper function wasn't right, then the whole function would be wrong. That was the main problem we experienced. Our helper functions were not getting the proper parameters. 

Problem 4: 20m

After reading the lecture that talked about force and delay, we tried implementing it. For delay, it say that it was basically just using an empty lambda and calling the expression in that lambda. We implemented it and it only passed one test case. We then just decided not to implement it because we had no other ideas.
