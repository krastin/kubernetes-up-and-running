

default: all

all: simple-node

simple-node: Dockerfile
	docker build -t kuard .

run:
	docker run --rm -p 8080:8080 kuard

.PHONY: clean
clean:
	-docker image rm kuard
