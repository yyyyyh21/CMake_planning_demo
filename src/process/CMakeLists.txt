project(process)
aux_source_directory(${PROJECT_SOURCE_DIR} SRC_LISTS)

add_library(
    ${PROJECT_NAME}
    SHARED
    ${SRC_LISTS}
)

target_include_directories(
    ${PROJECT_NAME}
    PUBLIC
    ${Pnc_Map_Dir}
)

target_link_libraries(
    ${PROJECT_NAME}
    PUBLIC
    pnc_map
)