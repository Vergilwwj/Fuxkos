# CMakeLists head

target_sources(${VSF_LIB_NAME} INTERFACE
    vsf_input.c
)

add_subdirectory(driver)
add_subdirectory(protocol)
