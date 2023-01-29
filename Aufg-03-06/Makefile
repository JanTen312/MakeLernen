HEADERS=head.h

default:main 

main.o:main.c
  gcc -c main.c -o main.o

funktion.o:funktion.c
  gcc -c funktion.c -o funktion.o 
  
main: main.o funktion.o
  gcc main.o funktion.o -o main
  
clean:
  rm -f *.o
  rm -f main
