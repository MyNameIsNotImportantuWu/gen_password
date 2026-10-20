# gen_password
#generator of passoword with all characters

import string
import random
caratteri = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
dmda = int(input("Inserisci il numero di caratteri della password: "))

password = ''

for i in range(dmda):
    caratteri_random = random.choice(caratteri)
    password += caratteri_random

print(password)
