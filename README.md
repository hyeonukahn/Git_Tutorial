# Git_Tutorial
To start Github in Windows

In CMD
```
Microsoft Windows [Version 10.0.18363.1440]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\users>git config --global user.name Username
C:\Users\users>git config --global user.email UserEmail
C:\Users\users\git>git clone https://github.com/hyeonukahn/Git_Tutorial.git
Cloning into 'Git_Tutorial'...
warning: You appear to have cloned an empty repository.
```
New Directory in Git Added on your computer
```
C:\Users\users\git>cd Git_Tutorial
C:\Users\users\git\Git_Tutorial>git add NEW_text.txt
C:\Users\users\git\Git_Tutorial>git commit -m "Add Text File [NEW_text.txt]"
[master (root-commit) 2a87e68] Add Text File [NEW_text.txt]
 1 file changed, 1 insertion(+)
 create mode 100644 NEW_text.txt

C:\Users\users\git\Git_Tutorial>git push
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 242 bytes | 242.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/hyeonukahn/Git_Tutorial.git
 * [new branch]      master -> master
```
File in your Computer added in this git
