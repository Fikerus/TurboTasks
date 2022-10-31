# TurboTasks
## Задачи для начиниющих и не очень программистов

### Легко
- Игра "больше меньше" (Загадывается число от 1 до 1000, задача игрока - угадать число за 10 попыток).
- Подсчет "дырочек" в тексте. (Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек)  
- Приложение заменяющие все "Л" на "Р" в тексте, (анимезиция). компилятор сломался -> компиряртор сромарся  

### Средне
- Нормальные крестики-нолики
- Игра "Жизнь Конвея"
- Размытие картинок алгоритмом Box Blur
- Рисовалка типа "Paint"
- Игра "Змейка"
- Игра "Тетрис"
- Telegram-bot для подсчета "дырочек" в тексте. (Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек)  

### Сложно
- Птичка типа "Flappy Bird"
- Игра 2048
- Парсер математических выражений вида "4+5*2"
- Подсчет "дырочек" в тексте. Усложнённая версия. Подсчёт дырочек должен производиться для произвольных символом (Например в слоге "ロ" - 1 дырочка)
- Дизеринг изображений (пример https://github.com/turborium/Dither3)
- Приложение заменяющие все "Л" на "Р" в тексте, и озвучивающее результат(https://github.com/turborium/microsoft-text-to-speech-delphi-example). компилятор сломался -> компиряртор сромарся  



### Очень сложно
**Проверяю на стриме**  

Калькулятор (без готового парсера, скобок и т.д.):

Все уверены, что написать простейший калькулятор - очень просто.   
Однако просмотр ютуб роликов вида "пишем калькулятор на языке xxx" показал, что в действительности написать хороший, не глючный калькулятор - очень сложно. 
  
**Условия:** 
1) Калькулятор должен иметь UI/GUI/графический интерфейс
2) Калькулятор должен быть "простейшим" - никаких eval("1+3\*2") и прочих парсеров математических выражений.  
Просто имитация самого дешевого калькулятора. Т.е. после нажатия [1] [+] [3] [\*] [2] [=] должно получиться 8, а не 7.  
3) Язык/среда и т.д. - любые.  
4) Желательны следующие функции: +,-,\*,/,корень,очистка,точка,удаление символа.  
5) Важное уточнение - количество цифр на «экране» должно быть ограниченным, т.е. например ввести можно не более 15 цифр.
Не должен происходить переход в форму вида 2.43847e16 при вводе большего количества цифр.

**Критерии оценки:**  
Главное: не глючность.  
Не главное: качество кода.  

---
# Список выполненных задач:
- Подсчет "дырочек" в тексте: https://github.com/Fikerus/holes
- Подсчет "дырочек" в тексте: https://gist.github.com/rprtr258/ae549c12fbcbb7c70542ec3a8d4072a8
- Подсчет "дырочек" в тексте: https://github.com/osennij-morok/dyrochki (+)
- Подсчёт "дырочек" в тексте: https://github.com/ketchuup/Holes
- Подсчёт "дырочек" в произвольном тексте: https://github.com/ketchuup/Any (+/-)
- Подсчёт "дырочек" в произвольном тексте: https://github.com/Fikerus/holes-canvas (+)
