# hnet  
Easy Linux networking UDP class

Design usage:

Program1:
  UDP udp(55555);
  char message[64];
  udp.recv(message,64);
  fprintf(stdout, "Secret message: %s\n", message);
  
Program2:
  UDP udp
  udp.send("127.0.0.1", 55555,"Hello World", strlen("Hello World");
  
