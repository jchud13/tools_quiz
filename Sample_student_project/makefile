# Makefile to build the sample student project 
# With all the targets
# By Jared Chudzinski

CC=gcc
CFLAGS=-g -Wall

all : main.cc game.cc othello.cc game.h othello.h 
	cc -c *.cc

main.o : main.cc game.h othello.h
	cc -c main.cc
game.o : game.cc game.h
	cc -c game.cc
othello.o : othello.cc othello.h

archive :
	tar cvf makefileproj.tar /Users/jaredchudzinski/Documents/tools
	gzip makefileproj.tar
clean :
	rm -f *.o *.out