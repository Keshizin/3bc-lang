cmake_minimum_required(VERSION 3.18)

project(3bc-lang)

set(APP_EXE 3bcvm)

#set (CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")

#file (GLOB HEADER "src/*.h")
#file (GLOB SOURCE "src/*.c")

#source_group ("inc" FILES ${HEADER})
#source_group ("src" FILES ${SOURCE})

include_directories("${PROJECT_SOURCE_DIR}/src")

add_executable(${APP_EXE} main.c)