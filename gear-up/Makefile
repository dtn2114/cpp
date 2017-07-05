
CC  = g++
CXX = g++

INCLUDES =

CFLAGS   = -g -o -Wall $(INCLUDES)
CXXFLAGS = -g -Wall $(INCLUDES)

LDFLAGS = -g

LDLIBS =

hello: hello.o

hello.o: hello.cpp

.PHONY: clean
clean:
	rm -f  *.o a.out core hello

.PHONY: all
all: clean hello
