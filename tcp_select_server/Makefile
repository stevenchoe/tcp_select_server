CC = gcc
CFLAGS = -W -Wall -O2
LDFLAGS = -lm

all : tcp_select_server

tcp_select_server : tcp_select_server.c
	$(CC) $(CFLAGS) -o $@ $^ $(LDFLAGS)

clean :
	rm -rf *.o
