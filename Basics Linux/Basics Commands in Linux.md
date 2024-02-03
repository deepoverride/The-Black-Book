Returns machine name
```
hostname
``` 
Returns which user I am
```
whoami
```
Returns user’s privileges
```
id
```
returns list of directories and files
```
ls
```
returns hidden files with permissions
```
ls -al
```
to read files in console
```
cat
``` 
example
```
cat /etc/passwd
``` 
We can filter using grep
example to filter lines containing the word bash 
```
cat /etc/passwd | grep bash
```
Shows manual of the tool
```
man toolname
```
clear the shell
```
clear
```
returns the actual path
```
pwd
```
change to root user
```
su -
```
change to normal user
```
exit
```
to remove non empty folders
```
rm -r <foldername>
``` 
   
- Give sudo permissions to any user
```
usermod -aG sudo username
```
◦ and add this to <strong>/etc/sudoers</strong>
``` username  ALL=(ALL) NOPASSWD:ALL ``` ← This not needed password

◦ other option:
in  <strong>/etc/sudoers</strong>
after this line ``` User privilege specification ```
add this but need password of the username
``` username    ALL=(ALL) ALL ```

