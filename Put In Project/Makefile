all: compile link

compile:
	g++ -I src/include -c Code.cpp
link:
	g++ Code.o -o Executable -L src/lib -l sfml-graphics -l sfml-window -l sfml-system