# Create a library called "canbus_reader_zynq"
add_library(canbus_reader_zynq_lib canbus_reader_zynq.cpp)

# Specify include directories for the library
target_include_directories(canbus_reader_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
