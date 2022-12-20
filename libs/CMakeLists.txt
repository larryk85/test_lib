project(test)

find_package(cdt)

add_library( test test.cpp )
target_include_directories( test PUBLIC ${CMAKE_SOURCE_DIR}/../include )
target_ricardian_directory( test ${CMAKE_SOURCE_DIR}/../ricardian )