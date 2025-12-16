# Basic Commands
 
## 1. `pwd` - Print working directory
```bash
[vagrant@vbox ~]$ pwd
/home/vagrant
```

## 2. `mkdir` - Create a directory/folder in your home directory
```bash
[vagrant@vbox ~]$ mkdir dev
```
## 3. `cd` - Change your current working directory to dev
```bash
[vagrant@vbox ~]$ cd dev/
[vagrant@vbox dev]$
```
## 4. `ls` - to list files and directories
```bash
[vagrant@vbox dev]$ ls
textfile1.txt
```
## 5. `touch` - create empty files
```bash
[vagrant@vbox dev]$ touch textfile.txt
```
## 5. `cp` - to copy file to a directory
```bash
[vagrant@vbox dev]$ cp textfile.txt learning/
```
## 6. `cp` - to copy directory to a directory
```bash
[vagrant@vbox dev]$ cp -rvfp learning/ dev1/
'learning/' -> 'dev1/learning'
'learning/textfile.txt' -> 'dev1/learning/textfile.txt'
```
## 6. `mv` - to move file or directory to a directory
```bash
[vagrant@vbox dev]$ mv textfile.txt learning/
[vagrant@vbox dev]$ cd learning
[vagrant@vbox learning]$ ls
textfile.txt
```
## 7. `rm` - removing files and directories
```bash
[vagrant@vbox dev]$ rm -rf dev1
[vagrant@vbox dev]$ ls
learning  textfile1.txt
```













