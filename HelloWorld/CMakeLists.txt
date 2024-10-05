cmake_minimum_required(VERSION 3.16)
project(HelloWorld VERSION 1.0 LANGUAGES CXX)

# Set C++ Standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add subdirectories
add_subdirectory(src)
#add_subdirectory(tests)

# Add third-party libraries if needed
# add_subdirectory(lib/external_library)

# Include directories
include_directories(${PROJECT_SOURCE_DIR}/include)

# Optionally include extra configurations (e.g. tests, docs, etc.)
# include(CTest)
