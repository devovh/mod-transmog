AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/transmog_scripts.cpp")
AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/Transmogrification.cpp")
AC_ADD_SCRIPT_LOADER("Transmog" "${CMAKE_CURRENT_LIST_DIR}/src/transmog_scripts_loader.h" "SC_Npc_VisualWeapon")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/transmog.conf.dist")
