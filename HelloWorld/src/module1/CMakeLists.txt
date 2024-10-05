# Create a static or shared library for module1
add_library(module1 STATIC module1.cpp)

# Optionally add public headers for this module
target_include_directories(module1 PUBLIC ${PROJECT_SOURCE_DIR}/include/module1)
