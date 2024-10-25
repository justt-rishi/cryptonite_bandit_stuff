# Level 4-5
In this challenge we had to go into inhere file and there were 8-9 files with only one of them having the human readalble password which was -file07.
## Command line
```
bandit4@bandit:~$ ls inhere
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@bandit:~$ ls
inhere
bandit4@bandit:~$ cd inhere
bandit4@bandit:~/inhere$ ls
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@bandit:~/inhere$ cat -file00
cat: invalid option -- 'f'
Try 'cat --help' for more information.
bandit4@bandit:~/inhere$ cat -file02
cat: invalid option -- 'f'
Try 'cat --help' for more information.
bandit4@bandit:~/inhere$ cat ./-file00
�p��&�y�,�(jo�.at�:uf�^���@bandit4@bandit:~/inhere$ cat ./-file01
i�R�,�Λ�:Y���?�%�A����B��ͩ�bandit4@bandit:~/inhere$ cat ./-file02
3�      �)Ʈ�#Y��-6c��IR-�$����:��bandit4@bandit:~/inhere$ cat ./-file03
���/�
     ������qGi��,�2�Yb�
dbandit4@bandit:~/inhere$ cat ./-file04
ۙ�rOx����h0~ey
��c�~�h�n��G1bandit4@bandit:~/inhere$ cat ./-file05
}���ߓ��ߤ��W>��#lk�d�ܮ��yE��bandit4@bandit:~/inhere$ cat ./-file06
6�0]�\�$�1�%�������o@��b/��bandit4@bandit:~/inhere$ cat ./-file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
