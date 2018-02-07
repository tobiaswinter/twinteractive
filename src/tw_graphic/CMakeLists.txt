project(tw_graphic)

set(HEADERS
        library.h
        )

set(SRC
        library.cpp
        )

add_library(${PROJECT_NAME} ${SRC} ${HEADERS})

install(FILES ${HEADERS} DESTINATION ${CMAKE_ROOT_DIR}/include/${PROJECT_NAME})