cmake_minimum_required(VERSION 3.10)


project(ToDoList)


set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)


set(SOURCES
    src/main.cpp
    src/ToDoList.cpp
)


add_executable(ToDoList WIN32 ${SOURCES})

# Добавление пути к заголовочным файлам
target_include_directories(ToDoList PUBLIC include)