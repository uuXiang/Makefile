hello.out all : func.o main.o
	gcc -o hello.out func.o main.o
	
func.o : func.c
	gcc -o func.o -c func.c
	
main.o : main.c
	gcc -o main.o -c main.c

.PHONY : clean

clean :
	rm *.o hello.out