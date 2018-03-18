ADD_LIBRARY(synapsereconfig SHARED synapsereconfig.c)

TARGET_LINK_LIBRARIES(synapsereconfig ${CAER_LIBS})

INSTALL(TARGETS synapsereconfig DESTINATION ${CAER_MODULES_DIR})
