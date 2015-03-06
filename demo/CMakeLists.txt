# Add executable called "hello_demo" that is built from the source file
# "demo.cpp". The extensions are automatically found.
add_executable (hello_demo demo.cpp)

# Link the executable to the Hello library. Since the Hello library has
# public include directories we will use those link directories when building
# hello_demo
target_link_libraries (hello_demo LINK_PUBLIC hello)
