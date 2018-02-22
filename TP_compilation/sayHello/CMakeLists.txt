cmake_minimum_required( VERSION 3.0 )
project( TP_GL )
set( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -Wall -Wextra" )
set( CMAKE_BUILD_TYPE Debug )

add_executable(sayHello.out sayHello.cpp module1.hpp module1.cpp )

target_link_libraries( sayHello.out ${PKG_LIBRARIES} )