## Разработать инструмент командной строки для визуализации графазависимостей, включая транзитивные зависимости. Вариант 19
Сторонние средства для
получения зависимостей использовать нельзя.
Зависимости определяются по имени пакета ОС Ubuntu (apt). Для описания
графа зависимостей используется представление Graphviz. Визуализатор должен
выводить результат на экран в виде кода.
Конфигурационный файл имеет формат csv и содержит:
92
• Путь к программе для визуализации графов.
• Имя анализируемого пакета.
• Путь к файлу-результату в виде кода.
• Максимальная глубина анализа зависимостей.
• URL-адрес репозитория.
Все функции визуализатора зависимостей должны быть покрыты тестами.

## Вывод

![Задание 1](https://github.com/teeeema/mingazutdinov.a.r/blob/main/DZ_2/output.png)
