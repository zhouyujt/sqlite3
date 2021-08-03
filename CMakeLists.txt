cmake_minimum_required(VERSION 3.21)
project(sqlite3)

file(GLOB local_source
"*.h"
"*.c"
)

add_library(sqlite3 STATIC  ${local_source} )





