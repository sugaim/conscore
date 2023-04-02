find_package(SEAL 4.1 REQUIRED)

add_executable(sandbox
    main.cpp
)
target_link_libraries(sandbox SEAL::seal)