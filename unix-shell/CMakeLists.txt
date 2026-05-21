# CMakeList.txt : CMake project for unix-shell

add_executable(unix-shell main.c)

set_target_properties(unix-shell PROPERTIES
    C_STANDARD 11
    C_STANDARD_REQUIRED ON
)