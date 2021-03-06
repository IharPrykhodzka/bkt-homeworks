# Домашнее задание к лекции "Коллекции"

Для каждой задачи создайте решение на базе Gradle и залейте его в GitHub.

Для этого ДЗ вы можете сдавать всё в виде одного проекта, где финальный проект содержит решение всех трёх задач.

Все проекты должны быть созданы с использованием Gradle (без него не принимаются).

Не забудьте про [.gitignore](../.gitignore)

## Задача №1 - RecyclerView

Добавьте в своё приложение возможность отображения списка постов (пока для обычных постов) с использованием `RecyclerView`.

Вся функциональность, описанная в предыдущих задачах должна работать:
1. Лайки/дизлайки
1. Количество комментариев
1. Поделиться (шаринг)

## Задача №2 - Post Types

Добавьте помимо возможности отображать посты обычного типа, ещё несколько различных типов:
1. События (адрес и геопозиция)
1. Репосты
1. Видео с Youtube
1. Рекламные посты: 

![](./types/ad.png)

При клике на рекламном посте должен быть переход по ссылке.

Подсказки:
1. Типизацию постов организуйте с помощью `enum`
1. Доп.поля специализированных постов, которых может не быть у других (например, геопозция) сделайте с помощью `nullable` полей

## Задача № 3 (необязательная) - Скрытие

Реализуйте возможность скрытия поста:

![](./hide/hide.png)

Самые распространённые варианты реализации для скрытия с помощью списка:
1. `filter`
1. Удаление из списка

Продумайте самостоятельно, где на карточке вы разместите функцую скрытия и как (в виде кнопки-иконки или по-другому).

**В виде выпадающего меню делать не нужно.**
