# Лабораторная работа 3, вариант 15

- [Реализованный функционал](#реализованный-функционал)
- [Техническая информация](#техническая-информация)
  - [Используемые библиотеки](#используемые-библиотеки)

## Реализованный функционал 
Для лабораторной работы 3 было создано приложение, которое обрабатывает изображение через методы, указанных в 15 варианте. Необходимо было предоставить реализацию нелинейных фильтров, основанных на порядковых статистиках и локальную(2 метода на выбор) и адаптивные пороговые обработки.
При запуске программа автоматически использует файлы filtr.jpg и segm.jpg.
Затем отображается результат работы программы.
В первом ряду слева направо отображаются оригинал filtr.jpg оригинал, медианный фильтр, фильтр минимума, фильтр максимума. 
Во втором ряду слева направо отображаются оригинал segm.jpg оригинал, метод Бернсена, метод Ниблацка, адаптивная пороговая обработка.
При желании использовать данную программу на других изображениях необходимо закинуть картинки с названиями filtr.jpg или segm.jpg 
в папку с exe.
![2022-12-16 (48)](https://user-images.githubusercontent.com/96499616/208186489-859fbd12-f51c-497f-92e4-d4dfcf01d1eb.png)
## Техническая информация
Лабораторная работа была написана на языке Python. 
### Используемые библиотеки
- Matplotlib
- Numpy
- OpenCV
- TKinter
- PIL

Основа приложения написана на TKinter, для функций обработки изображений используется OpenCV, а для постороения
графиков используется MatPlotlib.

