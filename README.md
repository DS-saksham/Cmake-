Learning Cmake

This repo consists all the things that you need to work using Cmake
How to Compile code using the Cmake

Make a file name CMakeLists.txt

------The goto script you should write inside the file that we just created-------

cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(hello VERSION 1.0)
add_executable(hello main.cpp) (If you have more cpp files then you can go on adding here)

How to Compile

cmake .
make 
hello (this is the name you have given in add_executable)

Here is a more organized way to Use Cmake

Inside the main directory make a new directory named build

mkdir build
cd build
cmake ../
make
hello
