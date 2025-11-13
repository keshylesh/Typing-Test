all: clean build run

build:
	docker build -t typing-test . 

run:
	docker run --name typing-test-latest -dp 3000:80 typing-test:latest

clean:
	docker rm -f typing-test-latest 
