SOURCES = part1.cpp part2.cpp main.cpp
OBJECTS = ${SOURCES:.cpp=.o}
CXX := g++
CXXFLAGS := -Wall
ExecutableName := Partsapp

all: $(OBJECTS)
	$(CXX) $(CXXFLAGS) $^  -o $(ExecutableName)

%.o: %.cpp %.h
	$(CXX) -c $(CXXFLAGS) $< -o $@

clean:
	@rm -f $(OBJECTS) $(ExecutableName)
	@rm -f *.cpp~ *.h~ *.o~
help:
	@echo "All available targets"
	@echo "all - Builds the executable"
	@echo "clean - Remove all builds files"
	@echo "help - Lists all targets"
