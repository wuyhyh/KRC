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
        Chapter7/p7_2.c Chapter7/p7_7.c
        Chapter6/p6_4.c Chapter6/p6.3/main.c Chapter6/p6.3/word.c Chapter6/p6_6.c
        Chapter5/p5_10_1.c Chapter5/p5_11.c Chapter5/p5_10.c Chapter5/P5.6/lineptr.c Chapter5/p5_7.c Chapter5/p5_8.c
        Chapter4/p4_1.c Chapter4/P4.10.1/q_sort.c Chapter4/p4_10.c Chapter4/p4_3.c Chapter4/p4_6.c
        Chapter3/p3_5_2.c Chapter3/binsearch.c Chapter3/p3_4.c Chapter3/P3.5.1/main.c Chapter3/p3_5.c
        Chapter2/p2_10.c Chapter2/p2_7.c Chapter2/leap.c Chapter2/p2_8.c Chapter2/p2_9_1.c Chapter2/bit.c
        Chapter1/hello.c Chapter1/p1_2_1.c Chapter1/p1_2.c Chapter1/p1_3.c
        Chapter1/p1_4.c Chapter1/p1_7.c Chapter1/p1_8.c Chapter1/p1_9.c Chapter1/P1.5/p1_5_1.c Chapter1/P1.5/p1_5_2.c
        Chapter1/P1.5/p1_5_3.c Chapter1/P1.5/p1_5_4.c Chapter1/P1.10/variable.c)
