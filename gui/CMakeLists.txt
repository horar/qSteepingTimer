project(qSteepingTimer)

add_executable(${PROJECT_NAME}
    "main.cpp"
)

target_link_libraries(${PROJECT_NAME}
    Qt5::Core
)
