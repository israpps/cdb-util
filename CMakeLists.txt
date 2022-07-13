cmake_minimum_required(VERSION 3.10)

# set the project name
project(cdb-util)

# add the executable
#include_directories(include)
add_executable(cdb-util
	cdbencode.c
	cheatlist.c
	cheats.c
	database.c
	libcheats.c
	main.c
	miniz.c
	mystring.c
	parser.c
)
