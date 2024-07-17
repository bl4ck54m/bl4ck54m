#!/bin/python3

#Name
name = "bl4ck54m"

#About me
about_me = "proud husband and father"
interests = ["linux", "computer networking", "penetration testing", "defensive security", "programming"]
certifications = ["IT Support", "and I'm about to pwn the PJPT exam"]
learning = "penetration testing"
hobbies = ["reading", "writing", "collecting Star Wars Black Series figures"]

#Say good-bye
goodbye = "Thank you for visiting my page!"

print(f"My name is {name}.")
print(f"I'm a {about_me}.")
print(f"I'm currently learning {learning}.")
print("My interests include:")
for interest in interests:
    print("- " + interest)
print("I am certified in:")
for certification in certifications:
    print("- " + certification)
print("My hobbies include:")
for hobby in hobbies:
    print("- " + hobby)
print(goodbye)
