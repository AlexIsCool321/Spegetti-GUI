cmake_minimum_required (VERSION 3.2)
project ("Spegetti_GUI")

include_directories("/")

set( Spegetti_GUI_Sources

	"Sources/Spegetti_GUI.cpp"
    "Headers/SPegetti_GUI.h"

)

#set_target_properties(${PROJECT_NAME} PROPERTIES
    #ARCHIVE_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/OUT/game/bin"
    #ARCHIVE_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/OUT/game/bin"
#)

add_library(${PROJECT_NAME} ${Spegetti_GUI_Sources})