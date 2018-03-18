ADD_LIBRARY(meanratefilter SHARED meanratefilter.c)

TARGET_LINK_LIBRARIES(meanratefilter ${CAER_LIBS})

INSTALL(TARGETS meanratefilter DESTINATION ${CAER_MODULES_DIR})
