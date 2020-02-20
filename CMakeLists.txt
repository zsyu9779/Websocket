cmake_minimum_required(VERSION 3.15)
project(Websocket)

set(CMAKE_CXX_STANDARD 11)

add_executable(Websocket Server.cpp base64.h sha1.h intLib.h)