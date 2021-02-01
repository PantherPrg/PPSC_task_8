# PPSC_task_8: Freeze Ray
**| difficulty: 9/10 |**

You work at a research facility of alien technologies, and your team has recently obtained a mechanism that can freeze object midair. During testing, objects are thrown up in a testing zone (X units wide and Y units tall) and then frozen using the alien equiment. The data is recorded like so, which each 1 being an object and 0 being air: 

[[0, 0, 1, 0],
[1, 0, 1, 0], 
[0, 1, 0, 1],
[0, 0, 0, 0],
[1, 0, 1, 1]]
------------ <- This is the ground.

In order to successfully catch the falling objects, we need to map out what the testing zone would look like once the alien technology is turned off. We can then sort it into stacks using the same dimensions as before: 

[[0, 0, 0, 0],
[0, 0, 0, 0],
[0, 0, 1, 0],
[1, 0, 1, 1],
[1, 1, 1, 1]]
------------ <- This is the ground. 
__________________________________________________________________________________
**Input**:
Integer X (the width of the testing zone)
Integer Y (the height of the testing zone)

2D List (each embedded list is a row of the testing zone before the freeze ray turns off)
__________________________________________________________________________________
**Output**:
2D List rows as newlines (each list of the embedded lists is a newline of the answer)
__________________________________________________________________________________
**optional challenge: write your code in under 10 lines**

This problem deals with 2D lists, index finding, for loops, list manipulation. This problem is a big list exercise. Pretty cool. **Do your research, google is your friend.**

For additional help, either ask Paul, Joshua, Mr. Blatner, or any other staff member for assistance. We would be able to go over them during the club. **It can be an anonymous request if you would like.**
