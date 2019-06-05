# CMakeList.txt: файл проекта CMake верхнего уровня; проведите глобальную конфигурацию
# и включите сюда подпроекты.
#
cmake_minimum_required (VERSION 3.8)
project("CMakeProject1")
# Включите подпроекты.

add_subdirectory ("VSE_LABI/lb1/lb1")
add_subdirectory ("VSE_LABI/lb2/lb2")
add_subdirectory ("VSE_LABI/lb3/Solution1/do_while")
add_subdirectory ("VSE_LABI/lb3/Solution1/if")
add_subdirectory ("VSE_LABI/lb3/Solution1/while")
add_subdirectory ("VSE_LABI/lb4/lb4")
add_subdirectory ("VSE_LABI/lb5/lb5")
add_subdirectory ("VSE_LABI/lb6/lb6")
add_subdirectory ("VSE_LABI/lb7/lb7")
