#!/bin/python3

# Define your name
name = "bl4ck54m"

# Define your interests in a list
interests = ["penetration testing", "defensive security", "programming"]

# Additional information
about_me = "proud husband and father"
learning = "intermediate penetration testing"
hobbies = ["reading", "writing", "collecting Star Wars Black Series figures"]

# Say good-bye
goodbye = "Thank you for visiting my page!"

# Print your name, current learning interest, other interests, hobbies, and father status
print(f"My name is {name}.")
print(f"I'm a {about_me}.")
print(f"I'm currently learning {learning}.")
print("My interests include:")
for interest in interests:
    print("- " + interest)
print("My hobbies include:")
for hobby in hobbies:
    print("- " + hobby)
print(goodbye)
