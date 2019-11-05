

default: all

all: simple-node

simple-node: Dockerfile
	docker build -t simple-node .

.PHONY: clean
clean:
	-docker image rm simple-node
