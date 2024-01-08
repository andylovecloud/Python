import random

# Generate a random age for the host
host_age = random.randint(1, 10)

# Create a variable to track the number of guesses
guess_count = 0

while True:
    # Get the player's guess
    guess = int(input("Guess the host's age: "))

    # Check if the guess is correct
    if guess == host_age:
        print("Congratulations! You guessed the host's age correctly!")
        break

    else:
        print("Your guess is incorrect.")

        # Check if the guess is too low
        if guess < host_age:
            print("The host's age is higher than your guess.")

        # Check if the guess is too high
        elif guess > host_age:
            print("The host's age is lower than your guess.")

        guess_count += 1

        # If the player has made 10 guesses, tell them they lost
        if guess_count == 10:
            print("You exceeded the maximum number of guesses. You lost!")
            break
