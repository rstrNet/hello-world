# hello-world

// C prog for the Linux-command 'type <filename>' using 'type'
  
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main(int argc, char **argv)
{
  char cmd_type[] = "type ";
  strcat(cmd_type, *(argv+1));
  system(cmd_type);
  
  exit(EXIT_SUCCESS);
}
