# CMakeLists.txt has to be located in the project folder and cmake has to be
# executed from 'project/build' with 'cmake ../'.
cmake_minimum_required(VERSION 2.6)
find_package(Rock)
set(ROCK_USE_CXX11 TRUE)
rock_init(class_loader_library 0.1)
rock_standard_layout()
