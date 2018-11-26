target_sources(tpm PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}/EncryptDecrypt.c"
  "${CMAKE_CURRENT_LIST_DIR}/EncryptDecrypt2.c"
  "${CMAKE_CURRENT_LIST_DIR}/EncryptDecrypt_spt.c"
  "${CMAKE_CURRENT_LIST_DIR}/Hash.c"
  "${CMAKE_CURRENT_LIST_DIR}/HMAC.c"
  "${CMAKE_CURRENT_LIST_DIR}/MAC.c")
