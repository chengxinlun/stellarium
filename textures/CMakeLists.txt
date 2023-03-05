########### install files ###############

IF(NOT ANDROID)
INSTALL(DIRECTORY ./ DESTINATION ${SDATALOC}/textures
        FILES_MATCHING PATTERN "*.png"
        PATTERN "*.jpg"
        PATTERN "CMakeFiles" EXCLUDE )
ENDIF()

