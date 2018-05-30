target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/EventSequenceComplete.c"
  "${CMAKE_CURRENT_LIST_DIR}/HashSequenceStart.c"
  "${CMAKE_CURRENT_LIST_DIR}/HMAC_Start.c"
  "${CMAKE_CURRENT_LIST_DIR}/MAC_Start.c"
  "${CMAKE_CURRENT_LIST_DIR}/SequenceComplete.c"
  "${CMAKE_CURRENT_LIST_DIR}/SequenceUpdate.c")
