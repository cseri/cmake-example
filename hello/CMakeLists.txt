# Create a library called "hello" which includes the source file "hello.cpp".
# The extension is already found. Any number of sources could be listed here.
add_library (hello hello.cpp)

# Make sure the compiler can find include files for our Hello library
# when other libraries or executables link to Hello
target_include_directories (hello PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

