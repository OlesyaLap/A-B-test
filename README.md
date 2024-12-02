# A/B–тестирование целесообразности внедрения новой механики оплаты услуг на сайте

**В ходе анализа необходимо ответить на следующие вопросы**:

- На какие метрики необходимо обращать внимание в ходе анализа и почему?
- Имеются ли различия в показателях и с чем они могут быть связаны?
- Являются ли эти различия статистически значимыми?
- Стоит ли запускать новую механику на всех пользователей?

**Входные данные**

В качестве входных данных есть 4 csv-файла:
groups.csv - файл с информацией о принадлежности пользователя к контрольной или экспериментальной группе (А – контроль, B – целевая группа)
groups_add.csv - дополнительный файл с пользователями, который прислали спустя 2 дня после передачи данных
active_studs.csv - файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента. 
checks.csv - файл с информацией об оплатах пользователей в дни проведения эксперимента. 


