# ubuntu-file-permission


## Flowchart
The flowchart visually explains the meaning of each part of the permission string (rwxrwxr-x) for user, group, and others.

<img width="1317" height="581" alt="image" src="https://github.com/user-attachments/assets/5e83d520-f8a4-4bb6-8110-901a59be600c" />


## chmod Command
The following command was used to set the correct permissions:

``
chmod 775 main.py
``

Explanation of 775:

7 (user): read, write, execute (rwx)

7 (group): read, write, execute (rwx)

5 (others): read, execute (r-x)

This allows the owner and group to edit and run the file, while others can only read and execute it.

Python File
The permission was applied to the file main.py.

<img width="367" height="242" alt="Screenshot_1" src="https://github.com/user-attachments/assets/856f1ab9-6cf5-48ee-922c-08c06ccdb389" />

