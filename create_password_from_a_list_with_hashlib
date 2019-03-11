#!/usr/bin/python3.5
# Docs
# https://docs.python.org/3.5/library/hashlib.html#module-hashlib

import hashlib

users = open('path_to_file', 'r').read().split('\n')

for user in users:
  password = hashlib.md5(user.encode('utf-8')).hexdigest()
  print(f"user={user} passwd={password}")
