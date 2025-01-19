enable_testing()

# Add test executable
add_executable(BattleShipGame_tests test_main.cpp)
target_include_directories(BattleShipGame_tests PRIVATE ${PROJECT_SOURCE_DIR}/include)
add_test(NAME RunTests COMMAND BattleShipGame_tests)
