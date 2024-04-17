project(pnc_map)

aux_source_directory(${PROJECT_SOURCE_DIR} SRC_LISTS)
add_library(
    ${PROJECT_NAME}
    SHARED
    ${SRC_LISTS}
)

