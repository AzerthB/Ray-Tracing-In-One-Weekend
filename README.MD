## DEBUG COMPILATION

cmake -B build
cmake --build build

## DEBUG RUN

build\Debug\inOneWeekend.exe > image.ppm

## OPTIMIZED COMPILATION

cmake --build build --config release

## OPTIMIZED RUN

build\Release\inOneWeekend.exe > image.ppm