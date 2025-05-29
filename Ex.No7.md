# 19CS545-Ex7 - Find the string in GitHub

# AIM:
To create a Repository

# Procedure:

1. grep "home" /etc/passwd: This command utilizes the grep utility, which stands for
“global regular expression print.” It searches for the text “home” within the /etc/passwd file.
Now, let’s break down what each part of this command does:
◦ grep: The command itself.
◦ "home": The search pattern enclosed in double quotes. In this case, we’re looking
for lines containing the word “home.”
◦ /etc/passwd: The file we’re searching within. The /etc/passwd file is a critical
system file on Unix-like systems that stores information about user accounts. Each
line in this file represents a user and contains details such as the username, user ID
(UID), home directory, and default shell.
◦ When you run this command, it scans through the /etc/passwd file and displays
any lines that match the search pattern (i.e., lines containing “home”). Typically,
these lines correspond to user accounts and their associated home directories.
2. grep "home" /etc/passwd > /root/search.txt: This command builds upon the
previous one but adds a redirection step. Let’s break it down:
>: The greater-than symbol is used for output redirection. It takes the output produced by the
grep command and saves it to a file.
/root/search.txt: The target file where the output will be stored. In this case, it’s a file
named search.txt located in the /root directory.
So, instead of displaying the matching lines on the screen, this command redirects them to the
specified file. If you examine the contents of search.txt, you’ll find the same information as
displayed by the initial grep command. 

# Output:

![Screenshot 2025-05-29 112718](https://github.com/user-attachments/assets/0071e50d-8959-459b-a6f2-e89549bcded2)

# Result:

Thus a Repository has been created successfully.
