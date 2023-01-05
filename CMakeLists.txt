cmake_minimum_required(VERSION 3.24)

project(CCBasicCompiler)

add_executable( CCBAS
	src/alias.cpp
	src/alias.hpp
	src/basiscan.cpp
	src/ccbasic.cpp
	68HC05B6/CODEDEFS.H
	src/comperr.h
	src/compiler.cpp
	src/compiler.hpp
	src/compscan.cpp
	src/GLOBLABL.H
	src/KEYWORDS.H
	src/morio.cpp
	src/scanterm.cpp
	src/textres.cpp
	src/textres.h
	src/watchcod.h
)

target_compile_definitions(CCBAS PRIVATE far)

