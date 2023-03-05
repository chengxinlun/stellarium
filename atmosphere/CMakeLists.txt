
########### install directories and files ###############
IF(NOT ANDROID)
# install default Earth atmosphere model
INSTALL(DIRECTORY default DESTINATION ${SDATALOC}/atmosphere)
ENDIF()
