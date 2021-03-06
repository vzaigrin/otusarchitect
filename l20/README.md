# Генератор чисел Фибоначчи и описание применения шаблона в проекте.

**Цель:** Получите навыки применения шаблона "Итератор" и знания формировании чисел Фибонначи.

1. Создать программу, которая генерит числа фибонначи в указанном диапазоне в указанный файл. Предусмотреть возможность движения в обратном направлении (например, с использованием формулы Binet) 
2. Реализовать в программе абстрактную фабрику и конкретные фабрики, отвечающие за каждый вариант сортировки как продукты.
3. Программа записывает результаты в выходной файл данных. 
4. Если потребуется использовать Итератор в проектной работе, предоставить описание в текстовом файле в GitHub репозитории где конкретно и в какой роли используется этот шаблон.

**Решение**

Задача выполнена на языке Scala.

Класс *Fibonacci* реализует элемент последовательности чисел Фибонначи.

Классы *FibonacciForwardAggregator* и *FibonacciBackwardAggregator* представляют собой агрегаты для прохождения последовательности в прямом и обратном порядках.

Для этого используются классы *FibonacciForwardIterator* и *FibonacciBackwardIterator* соответственно.

UML диаграмма находится в файлах *UML*.

Пример вызова: *java -jar target/scala-2.13/l20-assembly-1.0.jar 0 5 data/from0to5.txt*
