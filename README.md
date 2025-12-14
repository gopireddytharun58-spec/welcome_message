This Python program collects basic information from the user and displays it in a friendly message.

Line-by-line Explanation:

name = input("What is your name ?")

Asks the user to enter their name.

The entered value is stored in the variable name.

age = int(input("How much old are you ?"))

Asks the user for their age.

The input is converted into an integer using int() and stored in the variable age.

hobby = input("What is your hobby ?")

Asks the user to enter their hobby.

The value is stored in the variable hobby.

message = ("🎉🎉 Welcome Tharun🎉🎉 ")

Stores a welcome message with emojis in the variable message.

print(message)

Prints the welcome message on the screen.

print(f"{name} is {age} years old and his {hobby}")

Uses an f-string to display the user's name, age, and hobby in a single sentence.
