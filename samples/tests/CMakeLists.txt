
add_executable(test_lineartet test_lineartet.cpp)
target_link_libraries(test_lineartet admmelastic)
add_test(test_lineartet test_lineartet)
