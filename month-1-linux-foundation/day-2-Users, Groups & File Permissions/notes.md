Users: The one who's using the linux, can be multiple person.
Groups: created by root users or administrators to give a particular right and access to group of people.
File permission is being allocated in sequence of owner, group and others.
in pattern of "rwx".
R = read
W= Write
x= Execute
To make this process more easy we assign the numbers for all 3 of the individuals cause without it we need to write it in this manner.

d rwx rwx rwx
d 777
both of these lines makes same file permission but to remember it easily we do this.


    4   2   1
0   -   -   -
1   -   -   x
2   -   w   -
3   -   w   x
4   r   -   -
5   r   -   x
6   r   w   -
7   r   w   -