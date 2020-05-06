set(CMAKE_MINIMUM_REQUIRED_VERSION 3.9)
set (CMAKE_C_FLAGS "-g")
add_executable(eoip main.c network.c tap.c)
