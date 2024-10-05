# Create a static or shared library for module2
add_library(module2 STATIC module2.cpp)

# Optionally add public headers for this module
target_include_directories(module2 PUBLIC ${PROJECT_SOURCE_DIR}/include/module2)
