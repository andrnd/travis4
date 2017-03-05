project(hello_world)

include_directories(include)

set(SOURCES src/main.cpp)

add_executable(main ${SOURCES})

