# Quiz_Game_Python
#Welcome note for entering into the game
welcques= input('Hi, Do you like playing Quiz Games?(Yes/No): ')
if welcques.lower() == "yes":
    print("That's Great!")
else:
    print("No worries!, See you next time :)")
    quit()

#Game initialization
print("Let's start the Quiz!")
print("There will be 5 questions, Each question carries 1 mark, So total marks are 5. ")
print("You must have to answer atleast 3 questions correctly to qualify for the next round.")
score = 0
ready = input('Are you ready?(Yes/No): ')
if ready.lower() == "yes":
    print("Good,strong people never give up!")
else:
    print('Prepare and come!')
    quit()
answer1 = input('What is the 4th letter of the Greek alphabet? : ')
if answer1.lower() == "delta":
    print("Excellent!")
    score =score + 1
else:
    print("Sorry, Wrong answer")
answer2 = input('What city is known as "The Eternal City"? : ')
if answer2.lower() == "rome":
    print("Excellent!")
    score = score + 1
else:
    print("Sorry, Wrong answer")
answer3 = input('In what country would you find Mount Kilimanjaro? : ')
if answer3.lower() == "tanzania":
    print('Excellent!')
    score = score + 1
else:
    print("Sorry, Wrong answer")
answer4 = input('In what country is the Chernobyl nuclear plant located? : ')
if answer4.lower() == "ukraine":
    print("Excellent!")
    score = score + 1
else:
    print('Sorry, Wrong answer')
answer5 = input('Who was the Ancient Greek God of the Sun? : ')
if answer5.lower() == "apollo":
    print('Excellent!')
    score = score +1
else:
    print('Sorry, Wrong answer')

#printing scores
print('Your score is ' + str(score))

