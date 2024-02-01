How to use grep to search and find all files for a given text string
In this example, search for a string called ‘redeem reward’ in all text (*.txt) files located in /home/tom/ directory, use:
```
grep "redeem reward" /home/tom/*.txt
```

Let us find text called “redeem reward” in files under Linux:
```
grep "redeem reward" ~/*.txt
```

You can search for a text string all files under each directory, recursively with -r option:
```
grep -r "redeem reward" /home/tom/
```
