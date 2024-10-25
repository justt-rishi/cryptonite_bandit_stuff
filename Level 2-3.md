# Level 2-3
In this we had to cat a dile with spaces in the file name and this is how I did it.
## Command Line
```
bandit2@bandit:~$ ls
spaces in this filename
bandit2@bandit:~$ cat ./ spaces in this filename
cat: ./: Is a directory
cat: spaces: No such file or directory
cat: in: No such file or directory
cat: this: No such file or directory
cat: filename: No such file or directory
bandit2@bandit:~$ ls
spaces in this filename
bandit2@bandit:~$ cat spaces in the filename
cat: spaces: No such file or directory
cat: in: No such file or directory
cat: the: No such file or directory
cat: filename: No such file or directory
bandit2@bandit:~$ cat "spaces in this filename"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```
