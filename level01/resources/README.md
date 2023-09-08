## LEVEL01

- John software can brute force a password if you have its hash
- Linux's passwords hash can be found in etc/passwd file :
```flag01:42hDRfypTqqnw:3001:3001::/home/flag/flag01:/bin/bash```
user = flag01
hash = 42hDRfypTqqnw
last pswd change = 3001 days after jan 1st 1970
minimum number of days you have to wait until changing password : 3001

- We installed John on host machine, then gave the hash to brute force it without any options.
- flag01 password is "abcdefg"
- we logged as flag01, getflag gave the flag.



# Websites
- https://www.cyberciti.biz/faq/where-are-the-passwords-of-the-users-located-in-linux/ 
- https://github.com/openwall/john/tree/bleeding-jumbo 