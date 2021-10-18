# hnet  
Easy Linux networking UDP/TCP classes

Example Usage:

Program1 (Acting as a server):
```c
  UDP udp(55555);
  char message[64];
  udp.recv(message,64);
  fprintf(stdout, "Secret message: %s\n", message);
```
  
Program2 (Acting as a client):
```c
  UDP udp;
  udp.send("127.0.0.1", 55555,"Hello World", strlen("Hello World");
```
