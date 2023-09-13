# This program is a game of rock, paper, scissors.

import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

user = input("What do you choose? Choose 0 for Rock, 1 for Paper, 2 for Scissors. ")

if user == "0":
  print(rock)
elif user == "1":
  print(paper)
elif user == "2":
  print(scissors)
else:
  print("Try again")

print("The computer chose:")
computer = random.randint(1-1, 3-1)

if computer == 0:
  print(rock)
elif computer == 1:
  print(paper)
else:
  print(scissors)

if user == "0" and computer == 0:
  print("DRAW!")
elif user == "0" and computer == 1:
  print("YOU LOSE!")
elif user == "0" and computer == 2:
  print("YOU WIN!")
elif user == "1" and computer == 0:
  print("YOU WIN!")
elif user == "1" and computer == 1:
  print("DRAW!")
elif user == "1" and computer == 2:
  print("YOU LOSE!")
elif user == "2" and computer == 0:
  print("YOU LOSE!")
elif user == "2" and computer == 1:
  print("YOU WIN!")
elif user == "2" and computer == 2:
  print("DRAW!")
else:
  print("Try again.")
