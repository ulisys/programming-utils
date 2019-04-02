# programming-utils
Utilities for Developers

**Bash**

How to generate random passwords:

cat /dev/urandom | tr -dc 'a-zA-Z0-9' | fold -w ${1:-16} | head -n 1

