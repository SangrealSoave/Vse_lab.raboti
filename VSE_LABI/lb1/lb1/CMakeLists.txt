# CMakeList.txt: проект CMake для CMakeProject1; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)

project ("lb1")
# Добавьте источник в исполняемый файл этого проекта.
add_executable (lb1 "func.h" "task1.c" "task2.c" "task3.c" "task4.c" "task5_main.c" "task6_main.c" "task7_main.c")

target_include_directories ( lb1 task8_lib )

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
