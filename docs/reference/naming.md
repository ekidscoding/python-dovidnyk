---
tags:
  - Основи
  - Змінні
---

# Правила Іменування Змінних

Основні правила наведені нижче

???+ success "Правила"
    === "Правила іменування змінних"
        ```py title="Основне правило"
        # має містити ЛИШЕ великі та малі літери, цифри та знак `_`
        # зокрема
        this_is_Sparta = 300
        we_love_Ukraine = True
        cats_or_dogs = "both"
        together_4ever = "Python"
        ```
    === "Рекомендовано"
        ```py title="англійська + '_'"
        # БАЖАНО має складатись з усіх малих латинських літер,
        # окремі слова розділені підкресленням
        # ПРАВИЛЬНА та водночас рекомендована форма
        my_name = "Іван"
        the_1_and_only = "Guido van Rossum, inventor of Python"
        ```
    === "НЕ Рекомендовано"
        ```py title="англійська + '_'"
        # ПРАВИЛЬНА але НЕ рекомендована форма
        myName = "Ява"
        ThisIsSparta =False
        ```

???+ failure "неправильні імена змінних"

    === "Помилка 1"
        ```py title="містить -"
        # не має містити мінус (дифіс)
        bada-boom = "BIIIIG"
        ```
    === "Помилка 2"
        ```py title="містить пробіл"
        # не має містити ` ` (пробіл)
        my favorite = "Avengers"
        ```
    === "Помилка 3"
        ```py title="починається з цифри"
        # не може починатись з цифри
        1_time = "95%"
        ```