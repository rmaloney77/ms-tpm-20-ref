target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/ActivateCredential.c"
  "${CMAKE_CURRENT_LIST_DIR}/Create.c"
  "${CMAKE_CURRENT_LIST_DIR}/CreateLoaded.c"
  "${CMAKE_CURRENT_LIST_DIR}/Load.c"
  "${CMAKE_CURRENT_LIST_DIR}/LoadExternal.c"
  "${CMAKE_CURRENT_LIST_DIR}/MakeCredential.c"
  "${CMAKE_CURRENT_LIST_DIR}/Object_spt.c"
  "${CMAKE_CURRENT_LIST_DIR}/ObjectChangeAuth.c"
  "${CMAKE_CURRENT_LIST_DIR}/ReadPublic.c"
  "${CMAKE_CURRENT_LIST_DIR}/Unseal.c")
