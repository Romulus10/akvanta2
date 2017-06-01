CC=gcc
SRV_SRC=server/main.c
CLI_SRC=client/main.c

make:
	server
	client

server:
	mkdir -p build/debug
	$(CC) $(SRV_SRC) -o build/debug/server

client:
	mkdir -p build/debug
	$(CC) $(SRV_SRC) -o build/debug/server

client:
	rm -rf build
