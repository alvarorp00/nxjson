cmake_minimum_required(VERSION 3.10)

set( CMAKE_C_COMPILER "gcc" )

project(NXJSON)

add_library(NXJSON STATIC
	nxjson.h
	nxjson.c
)
