add_library(mod_particle MODULE "")

target_sources(mod_particle
    PUBLIC
        "${CMAKE_CURRENT_LIST_DIR}/main.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/random.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/plant.cpp"
)

install (
    TARGETS mod_particle
    DESTINATION lib/synfig/modules
)
