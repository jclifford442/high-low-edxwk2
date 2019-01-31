
high = 100
low = 0
secret_number = (low + high) / 2
numguess = 0
user = ""

print("Please think of a number between 0 and 100!")
while True:
    print("Is your secret number ", str(secret_number), "?")
    user = input("Enter 'h' to indicate the guess is too high. Enter 'l' to indicate the guess is too low. Enter 'c' to indicate I guessed correctly.")
    if user == "l":
        low = secret_number
        secret_number = int((low + high) / 2)
    elif user == "h":
        high = secret_number
        secret_number = int((low + high) / 2)
    elif user == "c":
        print("Game over. Your secret number was: ", int(secret_number))
        break
    else:
        print("Sorry, I did not understand your input.")
        secret_number = secret_number


