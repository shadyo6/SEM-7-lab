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

### To download a file, example to download m1.txt 
```
wget -r -nH --cut-dirs=5 -nc ftp://software:software@210.212.207.12//wwampserver_/bin/m1.txt
```

### To download all files

```
wget -r -nH --cut-dirs=5 -nc ftp://software:software@210.212.207.12//wwampserver_/bin/*
```

### To delete history

```
history -c
```
