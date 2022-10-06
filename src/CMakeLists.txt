# example library
add_library(generate_id generate_id.cpp)

# main code
add_executable(gen_id main.cpp)
target_link_libraries(gen_id generate_id)