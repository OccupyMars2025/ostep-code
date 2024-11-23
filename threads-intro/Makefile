FLAGS = -Wall -pthread
INCLUDES = ../include

all: t0 t1

clean:
	rm -f t0 t1 t1.dump

t0: t0.c
	gcc -g -I $(INCLUDES) -o t0 t0.c $(FLAGS)

t1: t1.c
	gcc -g -I $(INCLUDES) -o t1 t1.c $(FLAGS)

t1.dump: t1
	objdump -d t1 > t1.dump
