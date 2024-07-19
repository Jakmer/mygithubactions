
add_executable(EngineStarterTest EngineStarterTest.cpp)

target_link_libraries(EngineStarterTest gtest gtest_main)

install(TARGETS EngineStarterTest DESTINATION ${CMAKE_BINARY_DIR})