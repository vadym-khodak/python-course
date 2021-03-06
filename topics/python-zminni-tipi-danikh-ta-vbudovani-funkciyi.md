# Python змінні, типи даних та вбудовані функції

### Змінні

Правила іменування змінних:

*   Назви змінних складаються з літер латинського алфавіту, цифр, нижнього підкреслення ("\_")

    ```python
    first_name = "John"
    ```
*   Назва змінної у Python повинна починатись з літери або нижнього підкреслення ("\_")

    ```python
    emails = ["example@email.com", "example2@email.com"]
    _counter = 0

    1_st_user = {"name": "Max", "age": 36}  # ПОМИЛКА - починається з цифри
    user-statuses = ("active", "pending")   # ПОМИЛКА - має дефіс "-" у назві
    ```
*   Назви змінних у Python прийнято писати у нижньому регістрі розділяючи слова нижнім підкресленням (snake\_case)

    ```python
    user_by_id = {1: {"name": "Bill"}, 2: {"name": "Rob"}}

    StudentName = "Bob"  # НЕ ПОМИЛКА, але так не прийнято
    userRole = "admin"   # НЕ ПОМИЛКА, але так не прийнято
    ```
*   Назви постійних у Python прийнято писати у ВЕРХНЬОМУ регістрі розділяючи слова нижнім підкресленням

    ```python
    DEFAULT_PAGE_SIZE = 50
    ```

### Базові типи даних:

* `int` integer цілі числа (1, 0, -44)
* `float` числа з плаваючою комою (3.14, 0.0, -2.8)
* `complex` Складні числа мають дійсну та уявну частину, кожна з яких є числом з плаваючою комою (1 + 3j)
* `str` string строка
* `bool` boolean логічне значення (True/False)
* `list` список (\[1, 2, 2])
* `tuple` кортеж ((1, 2, 2))
* `set` набір ({1, 2, 3})
* `dict` dictionary словник ({"key": "value", "ключ": "значення"})

### Вбудовані функції

* `print` Надрукувати строку в терміналі
* `input` Отримати строку введену користувачем
* `len` Отримати довжину послідовності (`str`, `list`, `tuple`, `set`, `dict`)
* `id` Отримати ідентифікатор об'єкту
* `dir` Переглянути усі атрибути об'єкту
* `help` Переглянути довідку по об'єкту
* `round` Отримати скруглене значення числа
* `abs` отримати модуль числа
* `pow` Звести число у ступінь

### Домашнє завдання:

#### Звичайний рівень

* Завдання про змінні: написати програму яка буде питати користувача ввести два числа та друкуватиме у терміналі суму та різницю цих чисел
* Завдання про рядки: написати програму яка буде питати користувача ввести ім'я та друкуватиме у терміналі "Привіт <введене ім'я>"
* Завдання про списки: написати програму яка буде питати користувача ввести послідовність імен розділених комою та друкуватиме ту саму послідовність імен відсортовану за алфавітом Python: змінні та типи даних

#### Ускладнений рівень:

* Написати програму, яка буде питати користувача ввести будь-який рядок та друкуватиме унікальні букви які використовувались у введеному рядку відсортовані за алфавітом
