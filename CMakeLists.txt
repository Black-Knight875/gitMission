cmake_minimum_required(VERSION 3.5)

PROJECT(gitMission)

ADD_COMPILE_OPTIONS(-g)

set(MAIN
	./src/hello.cc
)

ADD_EXECUTABLE(hello ${MAIN})