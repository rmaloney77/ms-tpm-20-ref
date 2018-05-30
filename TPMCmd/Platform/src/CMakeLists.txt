target_sources(tpm_pform PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/Cancel.c"
  "${CMAKE_CURRENT_LIST_DIR}/Clock.c"
  "${CMAKE_CURRENT_LIST_DIR}/Entropy.c"
  "${CMAKE_CURRENT_LIST_DIR}/LocalityPlat.c"
  "${CMAKE_CURRENT_LIST_DIR}/NVMem.c"
  "${CMAKE_CURRENT_LIST_DIR}/PlatformData.c"
  "${CMAKE_CURRENT_LIST_DIR}/PowerPlat.c"
  "${CMAKE_CURRENT_LIST_DIR}/PPPlat.c"
  "${CMAKE_CURRENT_LIST_DIR}/RunCommand.c"
  "${CMAKE_CURRENT_LIST_DIR}/Unique.c")
