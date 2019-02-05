Timothy Chu
CSC 278
mp3

1)
I worked on this project on my own.

2)
the buffer overflow is in the "foo()" function

3)
my input exploits the buffer overflow by passing in more than 24 bits so that
the payload data overflows into the stack, setting the return address to 400cb0,
the address of the "I've been hacked!" function "dosystem()"

4)
so the file has 600,000 bytes. If you wrote a script to attack it until it went through
and we assume we can make 10 attacks per second, it would take about 16.666667 hours