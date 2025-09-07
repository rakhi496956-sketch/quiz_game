# quiz_game
🎮 A simple command-line quiz game built with **Python**.   ❓ The game asks the user some questions and gives points for correct answers.  

score = 0



name = input("Enter your name: ")
print(f"\nWelcome {name} to the Quiz Game!\n")

# Question 1
print("What is the capital of India? ")
print("1. Delhi\n2. Mumbai\n3. Kolkata")
answer = input("Enter the option number: ")
if answer == "1":
    print("Correct ✅")
    score += 1
    
else:
    print("Wrong ❌")

# Question 2
print("Which language is used by AI? ")
print("1. Java\n2. Python\n3. C++")
answer1 = input("Enter the option number:")
if answer1 == "2":
    print("Correct ✅")
    score += 1
else:
    print("Wrong ❌")
    # Question 3
print("Who is the father of Shree Ram? ")
print("1. Dhasrath\n2. Nandbaba\n3. Sudhama")
answer2 = input("Enter the option number:")
if answer2.lower() == "1":
    print("Correct ✅")
    score += 1
else:
    print("Wrong ❌")
    # Question 4
print("What is the English meaning of Angoor? ")
print("1. Apple\n2. Banana\n3. Grapes")
answer3 = input("Enter the option number:")
if answer3 == "3":
    print("Correct ✅")
    score += 1
else:
    print("Wrong ❌")
 # Question 4
print("What is the full form of A.T.M.? ")
print("1. Automatic Teller Machine\n2. Automatic Tecnical Machine\n3. Autotaller Tecnical Machine")
answer4 = input("Enter the option number:")
if answer4 == "1":
    print("Correct ✅")
    score += 1
else:
    print("Wrong ❌")
     
 # Question 5
print("Which state is know as seven sister ? ")
print("1. Asam\n2. uttar pradesh\n3. Bihar")
answer4 = input("Enter the option number:")
if answer4 == "1":
    print("Correct ✅")
    score += 1
else:
    print("Wrong ❌")
print(f"\nYour final score is: {score}")




