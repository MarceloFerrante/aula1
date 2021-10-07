add_executable(aula1
        ../main.cpp
        )
target_link_libraries(aula1 PRIVATE times_two)

add_executable(teste
        ../main2.cpp
        )
target_link_libraries(teste PRIVATE times_two)