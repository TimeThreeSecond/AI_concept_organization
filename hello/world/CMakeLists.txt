cmake_minimum_required(VERSION 3.29)#[[最低版本要求]]

project(world)#[[项目名称]]

set(CMAKE_CXX_STANDARD 20) # 2，  [CMAKE_CXX_STANDARD] 为特殊宏，表示c++20版本
# set()
# 1，  [ var_name  value ]]   # ${ var_name }使用  定义变量，默认字符串
# 3，  [EXECUTABLE_OUTPUT_PATH] 宏 生成exe指定路径

add_executable(world main.cpp)
#[[生成可执行文件，world为exe文件名，
后面为源文件，可以空格或者;间隔罗列]]
