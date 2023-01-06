SIMPLE-COMPUTER-QUIZ-GAME-USING-PYTHON





!!!!! THIS PYTHON PROGRAM RUNS AN SIMPLE  CLI BASED COMPUTER QUIZ AND DISPLAYS THE SCORE ACCORDING TO YOUR ANSWERS !!!!! 




PROGRAM:
```PYTHON
        print("\nwelcome to my game")

playing = input("\nDo you want to play the game?")


if playing != "yes":
    quit()

print("\n**********Okay let's  play:)**********\n")

print("Note: All the answers should be in small letter.\n")
score = 0
#1
answer = input("What does CPU mean?\n")

if answer == "central processing unit" :
    print("Hurray! Correct!\n")
    score=score+5

else:
    print("oops! Incorrect\n")

#2

answer = input("What does GPU stands for?\n")

if answer == "graphics processing unit" :
    print("Hurray! Correct!\n")
    score = score+5
else:
    print("\noops! Incorrect\n")


#3


answer = input("What does RAM stands for?\n")

if answer == "random access memory" :
    print("Hurray! Correct!\n")
    score = score+5

else:
    print("\noops! Incorrect\n")



#4

answer = input("What does PSU stands for?\n")

if answer == "power supply unit" :
    print("Hurray! Correct!\n")
    score = score+5

else:
    print("\noops! Incorrect")


print("\n!!!!!Your Score is : ",score,"/20 !!!!!")

```








#------------------------------------------THANKS FOR VISITING :)-----------------------------------------------------------




