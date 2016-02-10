CXX := g++
CXXFLAGS := -Wall
ExecutableName := hello

all: hello.cpp
	$(CXX) $(CXXFLAGS)  hello.cpp -o $(ExecutableName)

#Clean the build files (.o and .cpp extension)
clean:
	@rm -f hello.o hello

#help target
help:
	@echo "Available targets:"
	@echo "all - build the executables"
	@echo "clean - Cleans the directory of .o files and executables"
	@echo "help - Lists possible targets"
