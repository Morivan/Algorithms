add_executable(TestQueueCPP queue.cpp)
target_include_directories(TestQueueCPP PUBLIC ..)
target_link_libraries(TestQueueCPP LibraryCPP)
add_test(TestQueueCPP TestQueueCPP)
set_tests_properties(TestQueueCPP PROPERTIES TIMEOUT 10)

add_executable(TestVectorCPP vector.cpp)
target_include_directories(TestVectorCPP PUBLIC ..)
target_link_libraries(TestVectorCPP LibraryCPP)
add_test(TestVectorCPP TestVectorCPP)
set_tests_properties(TestVectorCPP PROPERTIES TIMEOUT 10)

