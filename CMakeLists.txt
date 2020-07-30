# function
cmake_minimum_required(VERSION 3.0.2)

project(UGit VERSION 1.0)
message(STATUS "[Project] ${PROJECT_NAME}")

list(APPEND CMAKE_MODULE_PATH "${PROJECT_SOURCE_DIR}/cmake")
include(UbpaGit)
