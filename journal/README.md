# First week - Chapter 1 - 13/09 ~ 19/09:

This week I read the first chapter and I am progressing on the exercises.

I thought it was very cool to see applications where you transform different kinds of information into visual images to apply Computer Vision techniques on
mouse draw movement or bits of malware files.

I am sincerely curious if I will be able to detect facial micro-expression for detection of genuine emotions of people. I think I can use general emotion detection
on facial expressions and only detect anomalies or outlies in a time-series of facial expression.

# Second week - Chapter 2 - 20/09 ~ 06/09

### Highlights:
It was really cool to know how to get a free api token at azure so that i can make my own datasets for computer vision with bing image search.

There were some jupyter tips that I loved such as:
1. When inside the parentheses of a function, pressing Shift and Tab simultaneously
will display a window with the signature of the function and a short description.
Pressing these keys twice will expand the documentation, and pressing them
three times will open a full window with the same information at the bottom of
your screen. 
2. In a cell, typing ? func_name and executing will open a window with the signa‐
ture of the function and a short description.
3. In a cell, typing ?? func_name and executing will open a window with the signa‐
ture of the function, a short description, and the source code.
4. Unrelated to the documentation but still very useful: to get help at any point if
you get an error, type %debug in the next cell and execute to open the Python
debugger, which will let you inspect the content of every variable.

There is a library called ImageClassifierCleaner inside fast.ai that helps a lot getting your image dataset to a valid point.

The key here is that this library applies prediction into images, so that you get least confidence predictions first, so that you can change this image's label or even remove from your dataset
