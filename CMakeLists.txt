project(dbfdump)
cmake_minimum_required(VERSION 2.8)

add_executable( dbfdump 
    dbfdump.c dbfopen.c safileio.c
)
target_link_libraries(dbfdump)
