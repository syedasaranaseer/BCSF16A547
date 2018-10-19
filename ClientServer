#include <stdio.h>
#include <sys/stat.h>
#include <sys/types.h>
#include <fcntl.h>
#include <unistd.h>

int main()
{
int fileD, ValueR;

char buffer[16] = "MY NAME IS SARA."
fflush(stdin);
ValueR = mkfifo("/tmp/fifoProgram", 0666);
fileD = open("/tmp/fifoProgram", O_WRONLY);
write (fileD, buffer, sizeof(buffer));
close(fileD);
return 0;
}
