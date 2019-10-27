add_library(factorial factorial.cpp)
add_executable(main main.cpp)

target_link_libraries(main factorial)
