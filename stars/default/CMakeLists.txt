
########### install files ###############

IF(NOT ANDROID)
INSTALL(DIRECTORY ./ DESTINATION ${SDATALOC}/stars/default
        FILES_MATCHING PATTERN "*.json"
        PATTERN "*.dat"
        PATTERN "*.fab"
        PATTERN "*.cat"
        PATTERN "CMakeFiles" EXCLUDE)
ENDIF()
