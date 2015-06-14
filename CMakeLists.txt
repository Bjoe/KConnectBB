project(KConnectBB)
cmake_minimum_required(VERSION 2.8)

include_directories(${kdeconnectcore_INCLUDE_DIRS})

set(SRC_LIST
  main.cpp
)

add_executable(kcbb ${SRC_LIST})
target_link_libraries(kcbb
  ${kdeconnectcore_LIBRARIES}
)
