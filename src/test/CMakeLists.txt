# Add test executable
add_executable(${PROJECT_NAME}_test test_main.cpp)

# Link the test executable with the project library
target_link_libraries(${PROJECT_NAME}_test canbus_reader_zynq_lib)

# Add tests
add_test(NAME ${PROJECT_NAME}_test COMMAND ${PROJECT_NAME}_test)
