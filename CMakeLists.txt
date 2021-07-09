project(glad)

include_directories(glad-debug/include)

add_library(${PROJECT_NAME}
        STATIC
            glad-debug/src/glad.c
        )

target_include_directories(${PROJECT_NAME}
        PUBLIC
            glad-debug/include
        )
