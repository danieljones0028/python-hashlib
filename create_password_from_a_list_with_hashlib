# https://docs.python.org/3.5/library/hashlib.html#module-hashlib
# Python version >= 3.6.2

import hashlib

users = open('path_to_file', 'r').read().split('\n')

for user in users:
  password = hashlib.md5(user.encode('utf-8')).hexdigest()
  print(f"user={user} passwd={password}")
