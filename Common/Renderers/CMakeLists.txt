cmake_minimum_required(VERSION 3.0)

SET(RENDERERS_SRC_FILES 
	${CMAKE_CURRENT_SOURCE_DIR}/atShader.h
	${CMAKE_CURRENT_SOURCE_DIR}/atLineShader.h
	
	${CMAKE_CURRENT_SOURCE_DIR}/atShader.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/atLineShader.cpp PARENT_SCOPE)
	
SET(RENDERERS_INCLUDE_FILES	${CMAKE_CURRENT_SOURCE_DIR} PARENT_SCOPE)