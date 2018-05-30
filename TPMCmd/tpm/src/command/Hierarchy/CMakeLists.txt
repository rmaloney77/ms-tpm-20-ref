target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/ChangeEPS.c"
  "${CMAKE_CURRENT_LIST_DIR}/ChangePPS.c"
  "${CMAKE_CURRENT_LIST_DIR}/Clear.c"
  "${CMAKE_CURRENT_LIST_DIR}/ClearControl.c"
  "${CMAKE_CURRENT_LIST_DIR}/CreatePrimary.c"
  "${CMAKE_CURRENT_LIST_DIR}/HierarchyChangeAuth.c"
  "${CMAKE_CURRENT_LIST_DIR}/HierarchyControl.c"
  "${CMAKE_CURRENT_LIST_DIR}/SetPrimaryPolicy.c")
