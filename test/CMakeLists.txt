include_directories(../include)
set(PROJCL_TEST projcl_test)
set(PROJCL_TEST_SOURCES projcl_test.c)
add_executable(projcl_test ${PROJCL_TEST_SOURCES})
target_link_libraries(${PROJCL_TEST} ${PROJCL_LIBRARY} ${PROJCL_DEPENDENT_LIBRARIES} )
