cmake_minimum_required(VERSION 3.10)

# Name your project
project(RayTracingInOneWeekend LANGUAGES CXX)

# Require C++11 or newer (Ray Tracing in One Weekend uses modern C++ features)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Define your executable and its source code location
# This assumes your main.cpp is located inside the 'src' folder
add_executable(InOneWeekend 
    src/color.h
    src/hittable_list.h
    src/hittable.h
    src/main.cpp
    src/ray.h
    src/rtweekend.h
    src/sphere.h
    src/vec3.h
)
