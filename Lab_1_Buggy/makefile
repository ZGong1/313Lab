all: buggy

buggy: buggy.cpp
	g++ -std=c++17 -pedantic -Wall -Wextra -fsanitize=address,undefined -o buggy buggy.cpp -g

clean:
	rm buggy

test: all
	chmod u+x tests.sh
	./tests.sh
