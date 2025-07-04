# RoundedCornerApp

Приложение с закруглёнными углами окна, реализованное на C++ с использованием Qt.

## Особенности
- Окно с закруглёнными углами
- Возможность перетаскивания окна мышью
- Полупрозрачный фон
- Отсутствие стандартной рамки окна

## Требования для сборки
- Qt5 (или выше)
- CMake 3.5 или выше
- Компилятор с поддержкой C++11

## Инструкция по сборке

1. Создайте директорию для сборки:
```bash
mkdir build
cd build
```

2. Сконфигурируйте проект с помощью CMake:
```bash
cmake ..
```

3. Скомпилируйте проект:
```bash
make
```

## Запуск приложения

После успешной сборки запустите приложение:
```bash
./RoundedCornerApp
```

## Управление
- Для перемещения окна зажмите левую кнопку мыши в любом месте окна и перетащите
