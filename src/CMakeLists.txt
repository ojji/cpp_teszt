add_executable(cpp_teszt
    main.cpp
)

target_compile_definitions(cpp_teszt PRIVATE -DUNICODE -D_UNICODE)