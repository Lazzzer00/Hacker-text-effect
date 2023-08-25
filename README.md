# Hacker-text-effect
This a nice effect that I made using an youtube video as inspiration.
It is fairly simple.
Create an h1 tag, type what you want it to contain and add a data attribute to contain it's value.
Use some basic css, make the background black, text white and bigger and center it on the screen.
In JavaScript create a string containing all the letters in the english alphabet.
Set the number of iteration to 0.
Select your h1 tag using a querySelector("h1") and then add a function on mouse over which it essentally the same as :hover.
Function will take in the event and set the interval to iterate every 30ms.
The we take the inner text of the h1 and split every letter.
We map each letter and it's index so it changes to a random letter from the string we innicialy made.
We say that if the index of the letter is less than the number of iterations it remains the original letter,
if it isn't less we assign it a new value. 
Every 30ms we up the iteration count by one.

That's the algorithm, if you think something can be imporved let me know, 
and if you add something else that makes it look cooler let me know 2.
Thx!
