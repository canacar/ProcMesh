cmake_minimum_required(VERSION 3.0)

PROJECT(procmesh)

ADD_EXECUTABLE(procmesh procmesh.cxx mesh.cxx
	point3.cxx meshbase.cxx strlcpy.c
	main.cxx command.cxx meshproc.cxx scache.cxx)
