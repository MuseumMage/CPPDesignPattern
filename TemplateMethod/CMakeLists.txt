cmake_minimum_required(VERSION 3.27)
project (TemplateMethod)

add_executable (TemplateMethod main.cpp)

target_compile_features(TemplateMethod PRIVATE cxx_std_17)
