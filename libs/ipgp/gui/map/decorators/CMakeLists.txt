SET(IPGP_GUI_DECORATORS_SOURCES
    griddecorator.cpp
    legenddecorator.cpp
    movedecorator.cpp
    scaledecorator.cpp
)
SET(IPGP_GUI_DECORATORS_MOC_HEADERS
    griddecorator.h
    legenddecorator.h
    movedecorator.h
    scaledecorator.h
)
SET(IPGP_GUI_DECORATORS_HEADERS
    mapdecorator.h
)
SC_SETUP_GUI_LIB_SUBDIR(IPGP_GUI_DECORATORS)
