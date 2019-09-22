# Get the Cheese Scratch project


**Code for Mouse** <br>
When the green flag is clicked<br>
show the score and time variables and show the mouse


When the green flag is clicked<br> 
repeat forever<br> 
if touching cat end the game with broadcast


When up arrow is pressed <br>
forever move 3 steps and change costume until not pressing up arrow


When down arrow is pressed<br> 
move -1 steps and change costume until not pressing down arrow


When left arrow pressed<br> 
turn 20 degrees, change costume and wait until not pressing left arrow 


When right arrow pressed<br>
turn -20 degrees, change costume and wait until not pressing right arrow 


When mouse recieves the broadcast<br>
hide the score and time variables, hide the mouse and stop the mouse


**Code for Cat**<br>
When green flag is clicked hide the cat, create a clone then forever make a clone every 30 seconds


When grenn flag clicked set time to 0 and forever change time by 1 every second


When the cat starts as a clone go to (0,0), show the clone, make the rotation style left-right then<br>
forever pick a random direction<br>
repeat random 7 to 20 times
1. Move random 1 to 10 steps
2. Switch costumes
3. wait
4. if touching the edge bounce off it

When cat recieves dead broadcast<br>
hide and stop cat

**Code for Cheese**<br>
When green flag clicked<br>
hide cheese, set score to 0, create a clone


When the Cheese starts as a clone<br>
go to random position and show<br>
Repeat forever<br>
if touching mouse add 1 to score, broadcast message, delete the clone


When cheese recieves broadcast<br>
wait 3 seconds a make a clone


When cheese recieves dead broadcast<br>
hide and stop cheese

**This is bolded** <br>
*This is italicized* <br>
~~strikethrough~~


Number list
1. item one
2. item two

bulletted list
* item one
* item two
