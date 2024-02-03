    ```
    hostname
    ``` returns machine name
    ```
    whoami
    ``` returns which user I am
    ```
    id
    ``` returns user’s privileges
    ```
    ls
    ``` returns list of directories and files
    ```
    ls -al
    ``` returns hidden files with permissions
    ```
    cat
    ``` to read files in console
          example ```cat /etc/passwd``` 
    We can filter using grep
          example to filter lines containing the word bash 
    ```
    cat /etc/passwd | grep bash
    ```
    ```
    man toolname
    ``` Shows manual of the tool
    ```
    clear
    ``` clear the shell
    ```
    pwd
    ``` returns the actual path
    ```
    su -
    ``` change to root user
    ```
    exit
    ``` change to normal user
    ```
    rm -r <foldername>
    ``` to remove non empty folders
    
    - Give sudo permissions to any user
    ```
    usermod -aG sudo username
    ```
        ◦ and add this to <strong>/etc/sudoers</strong>
             ``` username  ALL=(ALL) NOPASSWD:ALL ``` ← This not needed password
        ◦ other option:
                # User privilege specification ← after this line
                ``` username    ALL=(ALL) ALL ``` ← add this but need password of the username


