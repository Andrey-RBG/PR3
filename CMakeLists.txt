cmake_minimum_required(VERSION 3.10)
project(AllTasks C)

# Установка стандарта C
set(CMAKE_C_STANDARD 11)

# Установка общей директории для всех исполняемых файлов
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

# Добавляем подпроекты
add_subdirectory(Num1)
add_subdirectory(Num2)
add_subdirectory(Num3)
add_subdirectory(Num4)
