add_executable(house_test house_test.cpp)
target_link_libraries(house_test gtest gtest_main)
add_test(NAME HouseTest COMMAND house_test)


target_include_directories(house_test PRIVATE ${CMAKE_SOURCE_DIR}/include/mathfunctions)

