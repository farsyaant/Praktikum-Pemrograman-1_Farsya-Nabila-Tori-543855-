# Variables
CXX = g++
CXXFLAGS = -Wall
TARGET = Soal_2
SRC = Soal_2.cpp

# Default target: compile the program
all: Soal_2

# Compile the Soal_2.cpp
Soal_2: Soal_2.cpp
	g++ -Wall -o Soal_2 Soal_2.cpp

# Run the program in test mode (using test.txt)
test: Soal_2
	./Soal_2 test

# Clean up the compiled files
clean:
	rm -f Soal_2

# Phony targets to avoid conflicts
.PHONY: all clean test
