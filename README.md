# End of the first Week
## 9/8/2017
Contents

We covered this week classroom rules, computer hardware, python 2 vs python 3, Putty, Ubuntu commands, navigation of Ubuntu through Putty, creation of files and directories in Ubuntu with Putty, and ip addresses.
Bacon

---

# End of Second Week
## 9/15/2017
This week we covered a lot about Python 3. First we started by learning the command print which just prints whatever text you put in (""). We then learned how to use variables and assign them. We went over how to add some input as a variable. I read some articles on the print function and string manipulation. I learned how to write out a varible in between a print function. We ended the week by learning how to add numbers with float and int. Float makes the number have decimals and int is just whole numbers. 

---

# End of Third Week
## 9/22/2017
We covered a lot about variables and integers in Python3. We went over how to do code circumference of a circle and how to add an integer like this i = i + 1. We learned about how to create a list and use them. They are represented by [] and how to pull certain things out of the list ex, print(gpas[3]) would pull out the 4th gpa in the list of gpas. How to add strings to a pre existing list using   .append(input("")). We covered how to split a sentence up using .split() and to insert characters between words. Ex, blank = "character between words here".join(message). I learned how to make a madlib by replacing words in a story with story = story.replace("word here",name of variable that new word is assigned to). I then began my homework and have completed problems 1 to 4 and working on problem 5.

---

# End of Fourth Week
## 9/29/2017
We had a couple of work days at the beginning of the week which I spent working on problem 5. I had to code the addition part of a calculator using .split to split the additon a the the + symbol. I then added int(numbers[0]) and int(numbers[1]). This would add the two numbers together with just one line of input from the user. Later in the week we started conditionals with if, and, or, and else statements. The if statement was basically if blank is true then activate next line of code. The and statement makes the if statement more complicated by adding more to it to make it true. The or statement made an if statement have more than one possible way to make it true for example(if(password == "Dog" or "Cat"):. The else statement made it so if nothing made the if statement true the program had something to go to. For example if(password == "Dog" or "Cat"): ended up not being true you could put the else statement after to put "Wrong Password".   

---

# End of Fifth Week
## 10/10/2017
This week was mainly working on a coverter for time. The code would convert 12 hour to 24 hour and 24hour to 12 hour. All you had to do is  enter in the time. Some of the commands I used were: if,or,and,is,not,list(), and isnumeric(). The only new command was isnumeric(), which detects if the string can be converted to a proper integer or not. I used it as a filter for the 24 hour time section of my code. The problem I ran into was my code trying to convert letters into numbers. I also used <,>,<=,>=, in my code to act as filters. My problem was solved when I learned the command isnumeric().


---


# End of Sixith Week
## 10/13/2017
This week we first had a general reeview of if statements, which I beleive I have a good grasp on. Nothing really new. On Wednesday we learned about while loops, which loops a command or commands until a certain requirment is met. For example a While code line would be While temp > 10.0). Then it could run print("it is cold") for example. On Thursday we learned about for loops. For loops stand for a certain thing inside something else, usually a list. For example for num1 in range(10) would print each number beween 0-10 ten times.


---


# End of Seventh and Eighth Week
## 10/27/2017
The first week was a few days of review to understand while loops. While loops run until the while statement is considered false. The other day was review of for loops, EX for number in range(10) this would just give each number from 0 to 10 the name of number and run the code following with each number. The review of the iteration was done through writing code to determine if a number was strong and armstrong. Strong numbers are the sum of the factorials being equal to the number itself. For example 145 is strong, 1+(1*2*3*4)+(1*2*3*4*5)= 145. Armstrong numbers are the digits of a number to the power of how many total digits there are. Ex 371, 3 digits, 3**3 + 7**3 + 1**3 = 371. This past week we worked on problems to test the knowledge of while and for loops. I have completed 2 out of 3 problems so far. I completed 2 problems with good understanding and the last of my 3 problems has proven some difficulty.


---


# End of 9th Week
## 11/3/2017
The first few days was work time to complete iteration problems. Problems 1 and 2 I was able to solve pretty well. Problem 4 was where I got stuck. The part I was confused on was how to use spaces to define where the letters were to add them to a list. While doing this problem I learned about splicing which looks like  words.append(sentence[wordstart:x]). This adds the characters from wordstart to x inside of the variable sentence. It seems useful but I feel like it may have made the problem more difficult. The last day of the week we learned about functions. For example len or .split are functions that have code that makes them up. We wrote a function to find armstrong numbers. The function requires def function_name_here(number): before all the code to name it. To test it we put the function name after all the code and a number like generate_armstrong_numbers(100000) This will run the funtion when we run the python file.


---


# End of 10th week
## 11/10/2017
This week we kept reviewing how functions work and creating functions for common things we use normally. We made functions for adding and multiplying. We learned how to call other functions inside of other functions. Fro example when we made a funtion for exponents we had to call the function for multiplying. We also had a question to answer about what happens when a function calls itself. When a function calls itself it becomes a recursive function and will repeat itself until told to stop or eventually gets too big and crashes. 


---


# End of 11th week
## 11/17/2017
This week we started to work with raspberry pi a little bit. It is just a computer shrunken down to palm size. It is able to run simple things and you can code on it. It has several sensors on it like barometer, accelorometer, humidity sensor, and more that you can attach. We currently are using something called the sensehat which can display colors through a grid of led bulbs that are on a circuit board. The circuit board is attached to the pi. You can use the senors to enable the sensehat or have it work on its own. We currently have it in a color formation to look like a dog walking. We are working on trying to make the whole grid turn red when the pi is moved using the accelorometer. I got the dog to walk forever but I need to work on the grid turning red.


---


#End of 12th Week
## 12/1/2017
This week we worked on making our pets so we can begin to animate them. I created a dog using colors from the RGB scale. I put variables in a grid that relate to colors. That grid is then assigned to a single variable. The sense hat was then set to display the grid. I tried to make a dog and got it to work but I did run into some color problems. I learned how to make the sense hat on the raspberry pi display things through led lights. The week was spent working on making pets so that in the end they can something similar to a tamagotchi. We also worked on having the raspberry pi display a red grid if the pi was moved at all. This was done by sensing if the accelerometer of the pi was moved at all. We used the variables x,y, and z for yaw, pitch, and roll.


---


#End of 13th Week
## 12/8/2017
This we advanced out raspberry pi pets to have some animation. My dog now has two animations, one for being entertained and the other for eating. For being entertained my dog will wag his tail back and forth. The tail wagging is set to loop 5 times and it has some time.sleep in it so it is slower. For the eating animation my dog is at his food bowl eating. There are two parts to this animation. One has the dog at thh bowl, but with a closed mouth and the other has the dog with his tongue in the food bowl. I also exprienced a very strange syntax error in my pi code where it said there was an error on entertain = [, this was the beginning to an led chart for the sense hat. I removed it from being used in my code in the function and it suddenly worked. I searched all over for any errors and could find none. This week I also got pygame to work and I found a tutorial on how to create pong. I have a blank screen for pong and I am working on more.

 --


#End of 14th Week
## 12/15/2017
This week we made out raspberry pi pets have the two animations be triggered by different movement using the different devices on the pi. For enteraining the accelorometer is used and for eating the orientation of the pi is used. When the pi is upside down the eating animation will play. It uses roll and yaw to tell if it is upside down. The command I used for the orientation was a sense.get_orientation api. It gives me the values of pitch, yaw, and roll in a list form for me to use. After that I added in a entertain and food bar that slowly decreases and is resent if the animation for that one is played. If one of the values goes from 100 to 0 it will display rolling text that tells you the pet has died. I am also in the process of working on my pong project and trying to understand how it comes together.
