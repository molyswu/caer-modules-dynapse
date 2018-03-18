ADD_LIBRARY(poissonspikegen SHARED poissonspikegen.c)

TARGET_LINK_LIBRARIES(poissonspikegen ${CAER_LIBS})

INSTALL(TARGETS poissonspikegen DESTINATION ${CAER_MODULES_DIR})
