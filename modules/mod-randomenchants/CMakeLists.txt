CU_SET_PATH("CMAKE_MOD_RANDOMENCHANTS_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/mod_randomenchants.cpp")

AC_ADD_SCRIPT_LOADER("RandomEnchants" "${CMAKE_CURRENT_LIST_DIR}/src/loader_randomenchants.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/mod_randomenchants.conf.dist")