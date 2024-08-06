import random
import string
def generate_password(length):
  lower = string.ascii_lowercase
  upper = string.ascii_uppercase
  digits = string.digits
  symbols = string.punctuation

  all_charactors = lower +upper + digits +symbols

  password = ''.join(random.choice(all_charactors)for __ in range(length))
  return password

password_length = 10

password = generate_password(password_length)
print(f"Generated Password: {password}")
