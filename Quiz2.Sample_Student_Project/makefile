# Makefile to build the sample student project 
# With all the targets
# By Jared Chudzinski

CC=gcc
CFLAGS=-g -Wall

all : college.cc college.h collegemain.cc course.cc course.h node.h tarray.h 
	cc -c *.cc

main.o : collegemain.cc course.cc college.cc
	cc -c main.cc

archive :
	tar cvf makefileproj.tar /Users/jaredchudzinski/Documents/tools/tools_quiz/tools_quiz
	gzip makefileproj.tar
clean :
	rm -f *.o *.out

myexe : 
	./a.out

build : all 
	./a.out

doc : 
	doxygen config
