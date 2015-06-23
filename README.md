# getenvaddr
A tool to find the memory address of an environment variable in a binary. This can be useful for exploit development when storing your payload in an environment variable.

Note: This is taken from the book Hacking: The Art of Exploitation.

## Usage
```bash
hp@machine$ ./getenvaddr SHELL somebinaryfile
SHELL will be at 0xffffd730
```

