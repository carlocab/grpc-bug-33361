cmake_minimum_required(VERSION 3.10)
project(test CXX)

if(INCLUDE_FIND_DEPENDENCY_MACRO_MODULE)
  include(CMakeFindDependencyMacro)
endif()

find_package(gRPC REQUIRED)
