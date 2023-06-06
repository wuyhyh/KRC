cmake_minimum_required(VERSION 3.25)
project(k C)

set(CMAKE_C_STANDARD 11)

include_directories(Other/Sort_experiment)

add_executable(k
#        Other/Sort_experiment/experiment.c
#        Other/Sort_experiment/rand_int.h
#        Other/Sort_experiment/sort.h
#        Other/hash.c
        Other/qsort.c
#        Other/selection_sort.c
#        Other/something.cpp
        Chapter7/p7_2.c Chapter7/p7_7.c Chapter6/p6_4.c Chapter6/p6.3/main.c Chapter6/p6.3/word.c Chapter6/p6_6.c)
