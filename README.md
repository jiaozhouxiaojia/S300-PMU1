# PMU-1
Compile with:



gcc -O3 -mtune=cortex-a9 -mfpu=neon -o  pmu_matrix pmu_matrix_test.c v7_pmu.S -lm
