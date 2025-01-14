cmake_minimum_required(VERSION 3.27)

set(HELLO_WINDOW_01_PATH "01.Hello Window-01")
set(HELLO_WINDOW_02_PATH "01.Hello Window-02")

set(HELLO_WINDOW_01 "01.HelloWindow-01")
set(HELLO_WINDOW_02 "01.HelloWindow-02")

add_subdirectory(${HELLO_WINDOW_01_PATH})
add_subdirectory(${HELLO_WINDOW_02_PATH})

set_target_properties(
    ${HELLO_WINDOW_01}
    ${HELLO_WINDOW_02}
    PROPERTIES FOLDER "1.Getting started/01.Hello Window"
)
