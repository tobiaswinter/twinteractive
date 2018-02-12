project(tw_graphic)

#add_subdirectory(${CMAKE_TEST_DIR}/tw_graphic ${CMAKE_TEST_DIR}/bin)

set(HEADERS
        library.h
        )

set(SRC
        library.cpp
        )

add_library(${PROJECT_NAME} ${SRC} ${HEADERS})

install(FILES ${HEADERS} DESTINATION ${CMAKE_ROOT_DIR}/include/${PROJECT_NAME})