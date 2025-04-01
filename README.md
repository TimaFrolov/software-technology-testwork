# Практика по планированию проектов

Проект - SMT солвер для экзистенциальной арифметики Семёнова (и арифметики Пресбургера)

Считаем, что в проекте три участинка.
Считаем, что люди знают некоторую базу:
+ конечные автоматы, операции над ними
+ формальная арифметика
+ более-менее умеют программировать
+ умеют писать парсер (на избранной технологии) по данной грамматике
Но не знают деталей в контексте SMT солверов:
* Элиминация кванторов в арифметике Пресбургера (автоматный подход)
* Тем более, элиминация квантора $\exists$ в арифметике Семёнова
  Но не знают конкретики (автоматный подход к элиминации кванторов в арифметике Пресбургера)
* Приведение Unary NFA к нормальной форме Хробака
* Минимизация DFA, детерминизация NFA

Диграмма находится в файле `diagram.csv`. Чтобы посмотреть в графическом виде, надо зайти на [OnlineGantt](https://www.onlinegantt.com/#/gantt) и использовать "Import/Export" -> "Import from Excel File"
