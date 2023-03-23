cmake_minimum_required(VERSION 3.0)

project(MyProject C)

set(SOURCES
	calcu.c
	add.c
	sub.c
	mul.c
	div.c
)

set(INCLUDES
	calcu.h
)

add_executable(MyExecutable ${SOURCES} ${INCLUDES})

