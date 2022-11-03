import string
import random


def random_string(length):
    size = int(length)
    letters = string.ascii_letters
    password = ''.join([letters[random.randint(0, len(letters) - 1)] for x in range(size)])
    print(password)

n = input("Password length: ")

i = 0
for x in range(int(n)):
    i += 1
    random_string(i)
