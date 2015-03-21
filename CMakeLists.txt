cmake_minimum_required(VERSION 3.1)
project(vtflib_posix)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    lib/HLLib.h
    lib/VTFLib.h
    VTFCmd/enumerations.c
    VTFCmd/enumerations.h
    VTFCmd/resource.h
    VTFCmd/stdafx.h
    VTFCmd/vtfcmd.c
    VTFLib/Error.cpp
    VTFLib/Error.h
    VTFLib/FileReader.cpp
    VTFLib/FileReader.h
    VTFLib/FileWriter.cpp
    VTFLib/FileWriter.h
    VTFLib/Float16.cpp
    VTFLib/Float16.h
    VTFLib/MemoryReader.cpp
    VTFLib/MemoryReader.h
    VTFLib/MemoryWriter.cpp
    VTFLib/MemoryWriter.h
    VTFLib/Proc.cpp
    VTFLib/Proc.h
    VTFLib/ProcReader.cpp
    VTFLib/ProcReader.h
    VTFLib/ProcWriter.cpp
    VTFLib/ProcWriter.h
    VTFLib/Reader.h
    VTFLib/Readers.h
    VTFLib/resource.h
    VTFLib/stdafx.h
    VTFLib/VMTFile.cpp
    VTFLib/VMTFile.h
    VTFLib/VMTGroupNode.cpp
    VTFLib/VMTGroupNode.h
    VTFLib/VMTIntegerNode.cpp
    VTFLib/VMTIntegerNode.h
    VTFLib/VMTNode.cpp
    VTFLib/VMTNode.h
    VTFLib/VMTNodes.h
    VTFLib/VMTSingleNode.cpp
    VTFLib/VMTSingleNode.h
    VTFLib/VMTStringNode.cpp
    VTFLib/VMTStringNode.h
    VTFLib/VMTValueNode.cpp
    VTFLib/VMTValueNode.h
    VTFLib/VMTWrapper.cpp
    VTFLib/VMTWrapper.h
    VTFLib/VTFDXTn.h
    VTFLib/VTFFile.cpp
    VTFLib/VTFFile.h
    VTFLib/VTFFormat.h
    VTFLib/VTFLib.cpp
    VTFLib/VTFLib.h
    VTFLib/VTFMathlib.cpp
    VTFLib/VTFMathlib.h
    VTFLib/VTFWrapper.cpp
    VTFLib/VTFWrapper.h
    VTFLib/Writer.h
    VTFLib/Writers.h)

add_executable(vtflib_posix ${SOURCE_FILES})
