# python_geometry_game
Guessing game where the player inputs x and y coordinates to try and have them land within a randomly generated rectangle.

I created 2 classes, 'Point' and 'Rectangle'.  

The 'Point' class is initialized with the instance variables 'x' and 'y'.
Within 'Point' I defined the 'falls_in_rectangle' function with a 'rectangle' paramenter.
The 'falls_in_rectangle' function takes the 'x' an 'y' coordinates and compares each to the 'lowleft' and 'upright' 'x' and 'y' coordinates from the rectangle parameter.

The 'Rectangle' class is initialized with instance variables 'lowleft' and 'upright'. 

Next, I imported the 'randint' method and created a rectangle variable that calls the 'Rectangle' class and uilizes the 'Point' class and 'randint' to generate 2 touples of 'x' and 'y'coordintates.  These touples are the 'lowleft' and 'upright' coordinates of the rectangle respectively.

The generated rectangle is then printed to the player and they are prompted to guess 'x' and 'y' which are stored as floating point numbers in the variable 'user_point'.

Finally, a print statement shows the user if their guess was inside the recatngle which returns 'True' or not inside as 'False'.
This print statement takes the values stored in 'user_point' and calls the function 'falls_in_rectangle' to compare the user input to the generated rectangle coordinates.
