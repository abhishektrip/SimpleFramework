cmake_minimum_required(VERSION 3.0)

SET(LOADERS_SRC_FILES 
	${CMAKE_CURRENT_SOURCE_DIR}/atCorrespondenceMarkerReadWrite.h
	${CMAKE_CURRENT_SOURCE_DIR}/atTextureLoader.h
	
	${CMAKE_CURRENT_SOURCE_DIR}/atCorrespondenceMarkerReadWrite.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/atTextureLoader.cpp PARENT_SCOPE)

SET(LOADERS_INCLUDE_FILES ${CMAKE_CURRENT_SOURCE_DIR} PARENT_SCOPE)