# MTA Lab

A lab to practice arrays and hashes while traveling through a subway system.

###Prerequisites:
- Arrays
- Hashes

###Objectives:

- Practice with array methods like intersection, index, etc.
- Practice accessing items in a hash

###Activity:
- Working in pairs, students should create a program that models a simple subway system.

- The program takes the line and stop that a user is getting on at and the line
and stop that user is getting off at and prints the total number of stops for the trip.
- There are 3 subway lines:
  - The N line has the following stops: Times Square, 34th, 28th, 23rd, Union Square, and 8th
  - The L line has the following stops: 8th, 6th, Union Square, 3rd, and 1st
  - The 6 line has the following stops: Grand Central, 33rd, 28th, 23rd, Union Square, and Astor Place.
  - All 3 subway lines intersect at Union Square, but there are no other intersection points.
    - For example, this means the 28th stop on the N line is different than the 28th street stop on the 6 line, so you'll have to differentiate this when you name your stops in the arrays.
    
### Sample Input/Output

```

***MTA***

What train do you want to get on: n, l, s? n
Which stop: ts, 34th, 28th-n, 23rd-n, us? ts

What train do you want to get off: n, l, s? s
Which stop: gc, 33rd, 28th-s, 23rd-s, us? gc


Your trip length is 8 stops.
```

### Hints:
* Consider diagraming the lines by sketching out the subway lines and their stops and intersection.
* Make subway lines keys in a hash, while the values are an array of all the stops on each line.
* The key to the lab is to find the __intersection__ of the lines at Union Square.
* Make sure the stops that are the same for different lines have different names (i.e. 23rd on the N and on the 6 need to be differentiated)


