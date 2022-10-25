# Cult Meeting - rev

## Description
*After months of research, you're ready to attempt to infiltrate the meeting of a shadowy cult. Unfortunately, it looks like they've changed their password!*

## Attached files
- meeting

## Flag
```HTB{1nf1ltr4t1ng_4_cul7_0f_str1ng5}```

## Solution
This was simple rev challenge. First I used strings to inspect the file. After quick look I found secret password. Then I nc to docker and simply enter the password.
