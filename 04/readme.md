# Blueprints и С++. Часть 2

### Цель задания

1. Ревью и рефакторинг кода.
2. Потренироваться в использовании кода движка.
3. Создать простые инструменты для интеграции в проект.

------

### Задание 1. Расчёт математических операций в С++

Cлабая сторона Blueprints — расчёт математических операций. В лекции мы заставили наш объект двигаться по закону синуса вверх и вниз. Переведите наши математические формулы в С++ в следующей последовательности.

* Удалите всю логику и переменные, связанные с проведёнными ранее операциями, из нашего блюпринтового наследника.
* Объявите новый метод в хедер файле С++ — SinMovement().
* Функция должна быть доступна для вызова в Blueprints.
* Объявите необходимые переменные в хедер файле С++ — Amplitude, Frequency, InitialLocation.
* Переменные Amplitude, Frequency должны быть доступны для редактирования у объектов на сцене и проинициализированы по умолчанию необходимыми вам значениями.
* Проинициализируйте переменную InitialLocation в функции BeginPlay().
* Реализуйте математические расчёты в CppBaseActor.срр файле в методе SinMovement().

------