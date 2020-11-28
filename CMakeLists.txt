#
# CMakeLists.text for plistcpp
#
# 2020-6-2 By GuoJH

cmake_minimum_required(VERSION 3.10)

project(plistcpp)

add_library(plistcpp STATIC src/Plist.cpp
							src/PlistDate.cpp
							src/pugixml.cpp)
target_include_directories(plistcpp PUBLIC include) 
