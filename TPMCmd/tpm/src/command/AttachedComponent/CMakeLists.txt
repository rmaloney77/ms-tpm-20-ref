target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/AC_GetCapability.c"
  "${CMAKE_CURRENT_LIST_DIR}/AC_Send.c"
  "${CMAKE_CURRENT_LIST_DIR}/AC_spt.c"
  "${CMAKE_CURRENT_LIST_DIR}/Policy_AC_SendSelect.c")
