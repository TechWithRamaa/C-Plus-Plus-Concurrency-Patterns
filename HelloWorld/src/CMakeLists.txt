# Add each subdirectory for modularity
add_subdirectory(module1)
add_subdirectory(module2)

# Create the executable
add_executable(${PROJECT_NAME} main.cpp)

# Link libraries (optional)
# target_link_libraries(${PROJECT_NAME} external_library)

# Link module1 and module2 to the main executable
target_link_libraries(${PROJECT_NAME} PRIVATE module1 module2)
