#! [cmake_use]
find_package(Qt6 COMPONENTS Sql REQUIRED)
target_link_libraries(mytarget Qt6::Sql)
#! [cmake_use]
