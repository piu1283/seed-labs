 
all: server_64

server_64: server_64.c
	gcc -DDUMMY_SIZE=N -z execstack -o server_64 server_64.c

clean:
	rm -f server_64


