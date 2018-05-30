target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/Attest_spt.c"
  "${CMAKE_CURRENT_LIST_DIR}/Certify.c"
  "${CMAKE_CURRENT_LIST_DIR}/CertifyCreation.c"
  "${CMAKE_CURRENT_LIST_DIR}/GetCommandAuditDigest.c"
  "${CMAKE_CURRENT_LIST_DIR}/GetSessionAuditDigest.c"
  "${CMAKE_CURRENT_LIST_DIR}/GetTime.c"
  "${CMAKE_CURRENT_LIST_DIR}/Quote.c")
