

default: all

all: simple-node

simple-node: Dockerfile
	docker build -t simple-node .

run:
	docker run --rm -p 3000:3000 simple-node

.PHONY: clean
clean:
	-docker image rm simple-node
