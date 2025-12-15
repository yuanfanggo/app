cmake_minimum_required(VERSION 3.20)
project(pc_demo C)

add_subdirectory(modules/spi)
add_subdirectory(modules/uci)

add_executable(app main.c)
target_link_libraries(app uci)

