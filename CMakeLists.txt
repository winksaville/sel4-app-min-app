add_executable(min-app src/main.c)

target_link_libraries(min-app
    libsel4
    libsel4printf
    libsel4startstop
)

add_dependencies(min-app sel4_kernel)
