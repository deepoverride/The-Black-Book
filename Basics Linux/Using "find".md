Locate a file knowing part of his name.
	Example, we know the file contain the word “texto”
```	
  find / -type f -name '*texto*' 2>/dev/null
```
Locate a directory knowing part of his name.
```
find / -type d -name '*texto*' 2>/dev/null
```

Other Options:
	The path is optional:
```
find / -iname /path/partofname* 
```
```
find / -iname /path/name.txt
```
or to get all files with as especific extension:
	In the following example we are searching all the files in an especific path with extension txt. 
```
  find / -iname /path/*.txt
```
