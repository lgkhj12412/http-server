# HTTP SERVER

## Вариант 4: work-stealing пул потоков

## Распределение ролей:
Студент N21 - HTTP парсер, сеть, API ручки,ответы на SIGKILL & SIGTERM
Студент N22 - work-stealing пул, хранилище, производительность

## Сборка:
cmake -B build -DCMAKE_BUILD_TYPE=Release && cmake --build build -j

## Запуск:
./build/server --port 8080 --threads 8
