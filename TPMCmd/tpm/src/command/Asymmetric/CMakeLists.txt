target_sources(tpm PUBLIC
                 "${CMAKE_CURRENT_LIST_DIR}/EC_Ephemeral.c"
                 "${CMAKE_CURRENT_LIST_DIR}/ECC_Parameters.c"
                 "${CMAKE_CURRENT_LIST_DIR}/ECDH_KeyGen.c"
                 "${CMAKE_CURRENT_LIST_DIR}/ECDH_ZGen.c"
                 "${CMAKE_CURRENT_LIST_DIR}/RSA_Decrypt.c"
                 "${CMAKE_CURRENT_LIST_DIR}/RSA_Encrypt.c"
                 "${CMAKE_CURRENT_LIST_DIR}/ZGen_2Phase.c")
