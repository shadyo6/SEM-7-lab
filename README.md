#!/bin/less

## files to be downloaded

```
#MAD
m1.txt
m2.txt
m3.txt
m4.txt
m5.txt

#NP
n1mr.c      #Message receiver for tw1
n1ms.c      #Message sender for tw1
n1p.c       #Pipes for tw1

n2s.c       #client file
n2c.c       #server file

n3.c

n4.txt
n5.txt
n6.txt
n7.txt
n8.txt
n9.txt
n10.txt

```

# Windows download
- for ubuntu check below

### STEP0: Open the powershell

### STEP1: Navigate to the folder you want to download the files in this case we are going to download it in the downloads folder

```
cd Downloads
```

### STEP2: login to the server
```
sftp lab2@10.11.1.121
```

- it will ask **yes** or **no** for the fist time, type **yes**
- Then password is expected and you already know it

### STEP 3: Navigate to the file
```
cd wampserver_/bin
```

### STEP 4: download the required file (example)

```
get m1.txt
```

# Ubuntu download

### To download a file, example to download m1.txt (To download other file replace m1.txt with the file name)
```
wget -r -nH --cut-dirs=5 -nc ftp://software:lab2@10.11.1.121//wwampserver_/bin/m1.txt
```

### To download all files

```
wget -r -nH --cut-dirs=5 -nc ftp://software:lab2@10.11.1.121//wwampserver_/bin/*
```

### To delete history

```
history -c
```
