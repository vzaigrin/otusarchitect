# Модуль логирования для многопоточного приложения произведения двух квадратных матриц. Описание применения шаблона в проекте

**Цель:**
  1. Научиться работать с шаблоном Singleton в рамках многопоточного приложения. Вы получите навыки как применения Singleton по назначению, а также разберётесь с одновременным доступом потоков к одному объекту
  2. Получите навык анализа системы - использовать или нет этот шаблон в проектной работе.

Написать класс logger для написанного приложения умножения матриц:
- Даны две матрицы A и B размерности N x N.
- Необходимо вычислить их произведение: матрицу С.
- C[i][j] = сумма по k от 1 до N A[i][k] * B[k][j].

Приложение должно логировать в файл название потока и элемент, который рассчитывает сейчас поток.

1. Описать класс Singleton. 
2. Встроить его применение в многопоточное приложение произведения матриц.
3. Написать тестовый пример, который формирует файл с логом. 
4. Если потребуется использовать Singleton в проектной работе, предоставить описание в текстовом файле в GitHub репозитории где конкретно и в какой роли используется этот шаблон. 