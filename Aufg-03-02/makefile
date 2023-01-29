HEADERS=head.h

default: mach

main.o: main.c $(HEADERS)
	gcc -c main.c -o main.o
      
funktion.o: funktion.c $(HEADERS)
	gcc -c funktion.c -o funktion.o
      
mach: main.o funktion.o
	gcc main.o funktion.o -o mach
      
clean:
	-rm -f *.o
	-rm -f mach
