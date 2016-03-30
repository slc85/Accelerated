cmake_minimum_required(VERSION 3.0)
project(hello)


set(HELLO_SOURCES 
	main.cpp
)

set (HELLO_HEADERS
	hello.h
)

add_executable(hello ${HELLO_SOURCES} ${HELLO_HEADERS})
