import sys
import random
answer = random.randint(1,10)
print("Guess a number in between 1 and 10: ")
for total_guesses in range(1):
  guess = int(input())
  if guess == answer:
    print("Correct!")
    sys.exit("Congratulations!")
  if guess != answer:
    print("Incorrect, try again: ")
    second_guess = int(input())

for second_guesses in range(1):
  if second_guess == answer:
    print("Correct!")
  if second_guess != answer:
    print("Incorrect, the answer is " + str(answer))

print("Guesses: ")
tries = (guess, second_guess)
print(tries)

def gap_guess(guess):
  if guess > answer:
    great_gap = guess - answer
    print("Your first guess was " + str(great_gap) + " greater than the answer")
  if guess < answer:
    less_gap = answer - guess
    print("Your first guess was " + str(less_gap) + " less than the answer")

def gap_second(second_guess):
  if second_guess > answer:
    second_great = second_guess - answer
    print("Your second guess was " + str(second_great) + " greater than the answer")
  if second_guess < answer:
    second_less = answer - second_guess
    print("Your second guess was " + str(second_less) + " less than the answer")

gap_guess(guess)
gap_second(second_guess)
