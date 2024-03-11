set(ROOT_DIR "${CMAKE_CURRENT_SOURCE_DIR}")

file(GLOB ROOT_SOURCES "${ROOT_DIR}/*.cpp")

add_executable(cmake ${ROOT_SOURCES})
