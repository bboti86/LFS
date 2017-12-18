# LFS
trying the Linux From Scratch project

Background: using Ubuntu 17.10 Live image in a Virtual Box machine

1) added the version-check.sh
output: 
bash, version 4.4.12(1)-release
/bin/sh -> /bin/dash
ERROR: /bin/sh does not point to bash
Binutils: (GNU Binutils for Ubuntu) 2.29.1
./version-check.sh: line 11: bison: command not found
yacc not found
bzip2,  Version 1.0.6, 6-Sept-2010.
Coreutils:  8.26
diff (GNU diffutils) 3.6
find (GNU findutils) 4.7.0-git
./version-check.sh: line 25: gawk: command not found
/usr/bin/awk -> /usr/bin/mawk
./version-check.sh: line 35: gcc: command not found
./version-check.sh: line 36: g++: command not found
(Ubuntu GLIBC 2.26-0ubuntu2) 2.26
grep (GNU grep) 3.1
gzip 1.6
Linux version 4.13.0-16-generic (buildd@lcy01-02) (gcc version 7.2.0 (Ubuntu 7.2.0-8ubuntu2)) #19-Ubu
ntu SMP Wed Oct 11 18:35:14 UTC 2017
./version-check.sh: line 41: m4: command not found
./version-check.sh: line 42: make: command not found
GNU patch 2.7.5
Perl version='5.26.0';
sed (GNU sed) 4.4
tar (GNU tar) 1.29
./version-check.sh: line 47: makeinfo: command not found
xz (XZ Utils) 5.2.2
./version-check.sh: line 50: g++: command not found
g++ compilation failed

2) linking /bin/sh to /bin/bash
# rm /bin/sh
# ln -s /bin/bash /bin/sh

3) installing Bison
# apt-get install bison
