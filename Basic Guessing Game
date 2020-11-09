"Basic Guessing Game"

correct_guess = "Bryan"
guess = ""
guess_limit = 3
guess_score = 0
out_of_guesses = False

while guess != correct_guess and not out_of_guesses :
    if guess_score == 2:
        hint = input("Do you want a hint ?")
        if hint == ("Yes"):
            print("My name")
        else:
            ""
    if guess_score < guess_limit:
        guess = input("Enter a random guess *Name* :")
        guess_score += 1
    else:
        out_of_guesses = True
if out_of_guesses:
    print("You are out of guesses, you LOST")
else:
    print("You win")
