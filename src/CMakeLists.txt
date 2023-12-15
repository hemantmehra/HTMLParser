add_executable(main main.cpp)

add_subdirectory(LibWeb)

target_link_libraries(main
    PUBLIC
    LibWeb
)
