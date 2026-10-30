# HTTP SERVER

## Вариант 4: work-stealing пул потоков

## Распределение ролей:

## Сборка:
cmake -B build -DCMAKE_BUILD_TYPE=Release && cmake --build build -j

## Запуск:
./build/server --port 8080 --threads 8
