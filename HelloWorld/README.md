
## Prerequisites

Make sure you have the following installed:

- [CMake](https://cmake.org/download/)
- A C++ compiler (e.g., GCC, Clang, MSVC)
- GitBash or Git (optional, for version control)

## Getting Started

Follow these steps to set up and build the project:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/TechWithRamaa/C-Plus-Plus-Concurrency-Patterns.git
   cd C-Plus-Plus-Concurrency-Patterns/HelloWorld


2. **Create a Build Directory**

   ```bash
   mkdir build
   cd build

3. **Run CMake**

   ```bash
   rm CMakeCache.txt
   rm -rf CMakeFiles
   cmake -G "Unix Makefiles" ..

4. **Run Make**

   ```bash
   make

5. **Run the Executable**

   ```bash
   ./src/HelloWorld.exe

6. **Adding Modules**

   - To add new modules:

      - Create a new directory under src for your module.
      - Add a CMakeLists.txt file in that directory to manage its build process.
      - Create your source (.cpp) and header (.h) files as needed.




