cmake_minimum_required(VERSION 3.27)

set(HELLO_TRIANGLE_01_PATH "02.Hello Triangle-01")
set(HELLO_TRIANGLE_02_PATH "02.Hello Triangle-02")
set(HELLO_TRIANGLE_03_PATH "02.Hello Triangle-03")

set(HELLO_TRIANGLE_01 "02.HelloTriangle-01")
set(HELLO_TRIANGLE_02 "02.HelloTriangle-02")
set(HELLO_TRIANGLE_03 "02.HelloTriangle-03")

add_subdirectory(${HELLO_TRIANGLE_01_PATH})
add_subdirectory(${HELLO_TRIANGLE_02_PATH})
add_subdirectory(${HELLO_TRIANGLE_03_PATH})

set_target_properties(
    ${HELLO_TRIANGLE_01}
    ${HELLO_TRIANGLE_02}
    ${HELLO_TRIANGLE_03}
    PROPERTIES FOLDER "1.Getting started/02.Hello Triangle"
)
