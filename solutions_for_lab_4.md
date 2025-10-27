# Solutions for exercises from lab 4

## Exercise 1

```bash
ls -al
```
## Exercise 2

```bash
ls -lhSr /var/log/
```
## Exercise 3
```bash
nano firstname.txt 
```
just type my first name in editor
```bash
Artur
```
'Ctrl + O to save'
'Enter'
'Ctrl + X to exit the editor'
```bash
cat firstname.txt
```
we get: 
```bash
Artur
```
## Exercise 4
```bash
nano lastname.txt 
```
'Ctrl + O to save'
'Enter'
'Ctrl + X to exit the editor'
```bash
echo "Shaposhnyk" > lastname.txt 
```
```bash
cat lastname.txt
```
we get: 
```bash
Shaposhnyk
```
## Exercise 5
```bash
cat firstname.txt lastname.txt
```
we get:
```bash
Artur
Shaposhnyk
```
## Exercise 6
using >> we add lastname.txt to the end 
```
cat lastname.txt >> firstname.txt
```
```
cat firstname.txt
```
we get:
```
Artur
Shaposhnyk
```
## Exercise 7
creating the file that will contain my list
```
ls -d ~/*/ > allfolders.txt  
```
```
cat allfolders.txt
```
we get (unique output):
```
/Users/artur/Applications/
/Users/artur/Desktop/
/Users/artur/Documents/
/Users/artur/Downloads/
/Users/artur/Library/
/Users/artur/Movies/
/Users/artur/Music/
/Users/artur/Pictures/
/Users/artur/Public/
/Users/artur/dev-tools-lesson-first/
```

## Exercise 8

``` bash
 find ~ -type f -empty
```




