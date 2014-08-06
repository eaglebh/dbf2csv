project(dbf2csv)
cmake_minimum_required(VERSION 2.8)

add_executable( dbf2csv 
    dbfdump.c dbfopen.c safileio.c
)
target_link_libraries(dbf2csv)
