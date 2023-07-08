import random

def guess_number():
    number = random.randint(1, 100)
    print("Welcome to the number guessing game!")
    while True:
        guess = int(input("Guess a number between 1 and 100: "))
        if guess < number:
            print("Too low!")
        elif guess > number:
            print("Too high!")
        else:
            print("Congratulations! You guessed the number!")
            break

guess_number()
