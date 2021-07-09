project(glad)

include_directories(include)

add_library(${PROJECT_NAME}
        STATIC
        src/glad.c
        )

target_include_directories(${PROJECT_NAME}
        PUBLIC
        include
        )
