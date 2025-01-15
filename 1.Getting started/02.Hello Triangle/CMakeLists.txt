cmake_minimum_required(VERSION 3.27)

set(HELLO_TRIANGLE_01_PATH "02.Hello Triangle-01")

set(HELLO_TRIANGLE_01 "02.HelloTriangle-01")

add_subdirectory(${HELLO_TRIANGLE_01_PATH})

set_target_properties(
    ${HELLO_TRIANGLE_01}
    PROPERTIES FOLDER "1.Getting started/02.Hello Triangle"
)
