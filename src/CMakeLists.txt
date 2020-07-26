project(n-queens)

target_include_directories(queens_lib PUBLIC "${8-Puzzle_SOURCE_DIR}/include")

add_executable(n-queens main.c)

target_link_libraries(n-queens queens_lib)
