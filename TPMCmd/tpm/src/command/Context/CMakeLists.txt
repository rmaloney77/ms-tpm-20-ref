target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/Context_spt.c"
  "${CMAKE_CURRENT_LIST_DIR}/ContextLoad.c"
  "${CMAKE_CURRENT_LIST_DIR}/ContextSave.c"
  "${CMAKE_CURRENT_LIST_DIR}/EvictControl.c"
  "${CMAKE_CURRENT_LIST_DIR}/FlushContext.c")
