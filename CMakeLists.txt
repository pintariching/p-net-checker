cmake_minimum_required(VERSION 3.0.0)
project(p-net-checker VERSION 0.1.0 LANGUAGES C)

# include(CTest)
# enable_testing()

add_executable(p-net-checker main.c)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
