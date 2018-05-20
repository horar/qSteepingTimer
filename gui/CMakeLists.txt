add_executable(${PROJECT_NAME})

set_target_properties(${PROJECT_NAME} PROPERTIES
    WIN32_EXECUTABLE true
)

target_sources(${PROJECT_NAME} PRIVATE
    main.cpp
)

target_link_libraries(${PROJECT_NAME} PRIVATE
    Qt5::Core
)
