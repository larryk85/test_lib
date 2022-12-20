project(test)

find_package(cdt)

add_library( test test.cpp )
target_include_directories( test PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../include )