CMake example project
=====================

Made using the instructions on the CMake webpage:
http://www.cmake.org/examples/

How to build on Windows
----

Prerequisites – install CMake, Ninja and Visual Studio

Step 1 – launch a Visual Studio prompt

Step 2 – use the following instructions to build:

    git clone https://github.com/cseri/cmake-example.git
    mkdir build
    cd build
    cmake -G "Ninja" ..
    ninja

How to run on Windows
----

Run `build\demo\hello_demo.exe`


Credits
----
Example Cmake files from http://www.cmake.org/examples/
The Hello World program is by me :)

