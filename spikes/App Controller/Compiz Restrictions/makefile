CC = gcc
CFlags = -Wall -pedantic -std=c11

#all: foutputTest.o foutputTest2.o foutput.o wline.o
	#${CC} -o foutputTest foutputTest.o foutput.o wline.o

run: 
	./addCompizRestrictions.sh

end:
	./removeCompizRestrictions.sh

#build: clean foutput.o
	#cp foutput.o ../../build

build:
	cp addCompizRestrictions.sh ../../../build/setup/start;
	cp removeCompizRestrictions.sh ../../../build/setup/end;


