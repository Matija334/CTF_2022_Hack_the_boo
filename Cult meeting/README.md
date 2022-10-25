# Cult Meeting - rev

## Description
*After months of research, you're ready to attempt to infiltrate the meeting of a shadowy cult. Unfortunately, it looks like they've changed their password!*

## Attached files
- meeting
- ![Screenshot_1](https://user-images.githubusercontent.com/111431985/197842364-a5510c33-dafe-4ee0-bb2e-46f10ac173ea.png)

## Flag
```HTB{1nf1ltr4t1ng_4_cul7_0f_str1ng5}```

## Solution
This was simple rev challenge. First I used strings to inspect the file. After quick look I found secret password.

![Screenshot_2](https://user-images.githubusercontent.com/111431985/197842438-c04f52ca-e23a-4f89-838c-fd37e94aa0fb.png)

Then I nc to docker and simply entered the password.

![Screenshot_3](https://user-images.githubusercontent.com/111431985/197842549-82172059-60b3-4c09-b073-1f4bf87bdd26.png)
