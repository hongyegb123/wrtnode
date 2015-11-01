#build a Makefile for helloworld.c
helloworld: helloworld.o
	$(CC) $(LDFLAGS) helloworld.o -o helloworld
helloworld.o: helloworld.c
	$(CC) $(CFLAGS) -c helloworld.c
clean:
	rm *.o helloworld