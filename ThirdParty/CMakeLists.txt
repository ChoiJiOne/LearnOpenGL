cmake_minimum_required(VERSION 3.27)

add_subdirectory(glad)
add_subdirectory(glfw)
add_subdirectory(glm)
add_subdirectory(stb)

set_target_properties(
    glad
    glfw
    glm
    stb
    PROPERTIES FOLDER "ThirdParty"
)