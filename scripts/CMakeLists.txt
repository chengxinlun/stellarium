########### install files ###############
IF(NOT ANDROID)
INSTALL(DIRECTORY ./ DESTINATION ${SDATALOC}/scripts
        FILES_MATCHING PATTERN "*.ssc"
        PATTERN "*.inc"
        PATTERN "CMakeFiles" EXCLUDE
        PATTERN "tests" EXCLUDE)
ENDIF()

