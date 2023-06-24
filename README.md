import random

chars = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
number = int(input("Какой длины создать пароль?"))
pass_word = ''

for i in range(number):
    k = random.randint(0, len(chars))
    pass_word += chars[k]
print(pass_word)
