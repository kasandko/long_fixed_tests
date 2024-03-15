cmake_minimum_required(VERSION 3.5.1)

project(libs)

add_subdirectory(fpmath)

include_directories("${PROJECT_SOURCE_DIR}/ex_type_traits/include")
include_directories("${PROJECT_SOURCE_DIR}/slimcpplib/include")
