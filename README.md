# Python-Quiz-App-Project
This is my python project which demonstrates my skills in building a console-based Quiz application. It showcases my understanding of programming concepts such as user input, conditionals, loops, and basic control flow.  

# What I learned: 
- How to handle user input and validate responses
- Using conditional statements for coding programs
- I learnt to structure a simple console-based application
- Debugging and testing Python code to ensure correctness

# Skills Used: 
- Python Programming
- User Input handling
- Control Flow (e.g. Conditionals, loops)
- Problem-solving and Logical thinking

# Tools Used: 
- Pycharm Community Edition = This is for writing and testing the code
- Git and GitHub = This was for Version Control Management

# Code Implementation: 

print("Welcome to the General Knowledge Quiz! \n")

Quiz_Score = 0

# Question 1:

print("1) What is the Capital of France ? ")
print("A. Madrid \n B. Paris \n C. Delhi \n D. Rome")
answer_1 = input("Your answer: ").strip().upper()

if answer_1 == "B":
    print("Correct!\n")
    Quiz_Score += 1

else:
    print("Wrong Answer! The correct answer is B. Paris. \n")

# Question 2:

print("2) Which planet is known as the Red Planet ? ")
print("A. Venus \n B. Saturn \n C. Mars \n D. Jupiter")
answer_2 = input("Your answer:").strip().upper()

if answer_2 == "C":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong Answer! The correct answer is C. Mars. \n")

# Question 3:

print("3) Who Wrote the play Romeo and Juliet ? ")
print("A. Charles Dickens \n B. Jane Austen \n C. William Shakespeare \n D. Mark Twain")
answer_3 = input("Your answer:").strip().upper()

if answer_3 == "C":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong Answer! The correct answer is C. William Shakespeare. \n")

# Question 4:

print("4) What is the largest mammal in the world ? ")
print("A. African Elephant \n B. Blue Whale \n C. Giraffe \n D. Orca")
answer_4 = input("Your answer:").strip().upper()

if answer_4 == "B":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is B. Blue Whale. \n")

# Question 5:

print("5) What is the boiling point of water ?")
print("A. 90 degree celsius \n B. 100 degree celsius \n C. 110 degree celsius \n D. 80 degree celsius")
answer_5 = input("Your answer:").strip().upper()

if answer_5 == "B":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is B. 100 degree celsius. \n")

# Question 6:

print("6) What does CPU stand for ?")
print("A. Central Process Unit \n B. Central Processing Unit \n C. Computer Processing Unit \n D. Control Processing Unit")
answer_6 = input("Your answer:").strip().upper()

if answer_6 == "B":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is B. Central Processing Unit. \n ")

# Question 7:

print("7) What is the hardest natural substance on Earth ? ")
print("A. Gold \n B. Iron \n C. Diamond \n D. Quartz")
answer_7 = input("Your answer:").strip().upper()

if answer_7 == "C":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is C. Diamond. \n")

# Question 8:

print("8) In which continent is the Sahara Desert located ? ")
print("A. Asia \n B. South America \n C. Australia \n D. Africa")
answer_8 = input("Your answer: ").strip().upper()

if answer_8 == "D":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is D. Africa. \n ")

# Question 9:

print("9) Who is known as the Father of Computers ? ")
print("A. Alan Turing \n B. Charles Babbage \n C. Bill Gates \n D. Steve Jobs")
answer_9 = input("Your answer:").strip().upper()

if answer_9 == "B":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is B. Charles Babbage. \n")

# Question 10:

print("10) Which gas do planets absorb from the atmosphere ?")
print("A. Oxygen \n B. Hydrogen \n C. Nitrogen \n D. Carbon Dioxide")
answer_10 = input("Your answer:").strip().upper()

if answer_10 == "D":
    print("Correct! \n")
    Quiz_Score += 1

else:
    print("Wrong answer! The Correct answer is D. Carbon Dioxide. \n")


# Score calculation

print("Well Done! You have scored", Quiz_Score,"out of 10")
print("End of Quiz, Thankyou!")


# Project File Link: 
- I have attached the 
[App_Project.py](https://github.com/user-attachments/files/22338249/App_Project.py)
