cmake_minimum_required(VERSION 3.16)

project(boost.container VERSION 0.0 DESCRIPTION "Why are you here??" LANGUAGES C CXX)

add_library(boost.container INTERFACE)
add_library(boost::container ALIAS boost.container)
target_include_directories(boost.container INTERFACE include)
