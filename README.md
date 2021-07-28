# PROJECT-OTP-GENERATOR

import random
import string
length = 6
OTP =""
characters = string.ascii_letters + string.digits
for i in range(length):
  OTP = OTP + random.choice(characters)
print("Your OTP:", OTP)

OUTPUT:
Your OTP: nfdKFS
