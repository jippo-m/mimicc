CFLAGS=-std=c11 -g -static

mimicc: mimicc.c

test: mimicc
		./test.sh

clean:
		rm -f mimicc *.o *~ tmp*

.PHONY: test clean