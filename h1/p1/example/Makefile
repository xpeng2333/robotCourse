sayHello : useHello.o
	gcc -o sayHello -static useHello.o -lhello

useHello.o : useHello.c
	gcc -c useHello.c
clean :
	rm sayHello useHello.o