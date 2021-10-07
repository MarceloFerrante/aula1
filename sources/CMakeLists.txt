add_library(times_two
        times_two.h
        times_two.cpp
        )

target_include_directories(times_two PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})