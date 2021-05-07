include_directories(${hw5_INCDIR})

add_executable(test_journal test_journal.cpp)
target_link_libraries(test_journal hw5 googletest )
add_test(TestJournal ./test_journal)

add_executable(test_checkpoint test_checkpoint.cpp)
target_link_libraries(test_checkpoint hw5 googletest )
add_test(TestCheckpoint ./test_checkpoint)


