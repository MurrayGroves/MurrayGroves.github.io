---
title: Pyaccounts
description: A Python package for managing quick and easy accounts
date: "2019-05-02T19:47:09+02:00"
jobDate: 2019
work: [Python, Pycryptodome]
techs: [Python, Pycryptodome]
designs: []
thumbnail: pyaccounts/thumbnail.png
projectUrl: https://github.com/MurrayGroves/pyaccounts

---

After making my Welcome To Nightvale Discord Bot, I was thinking about how complicated it was to create databases. It was with this thought that I decided to make a Python package to allow quick and easy integration of a user accounts system into any Python project. The package uses sha224 hashing for safe storage of passwords and AES ECB encryption for storage of account data.

Features:
- Create a user account in one function call
- Login a user with one function call
- Add additional user data with one function call
- Read additional user data with one function call
