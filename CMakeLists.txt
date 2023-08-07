cmake_minimum_required(VERSION 3.26)
project(MCA)

set(CMAKE_CXX_STANDARD 17)

add_executable(MCA main.cpp)
target_link_libraries(MCA PRIVATE /usr/local/lib/libhttpserver.a)
target_link_libraries(MCA PRIVATE /usr/local/lib/libmicrohttpd.a)
target_link_libraries(MCA PRIVATE /usr/local/lib/libsqlite3.a)
target_link_libraries(MCA PRIVATE /usr/local/lib/libSQLiteCpp.a)