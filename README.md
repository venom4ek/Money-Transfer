# Money-Transfer

### Отчёт о тестировании приложения "Money-Transfer"
#### Краткое описание
На основании полученных входных данных была написана программа, которая должна пополнять счет клиента на определенную сумму.<br>
Произведено тестирование программы.<br>
Выявлены ошибки во входных данных.

### Описание тестов
Мною было проведено функциональное тестирование, проводилась проверка компонента перевода денежных средств. В ходе тестирования были выявлены ошибки.

### Результаты

Проведено 3 теста.

30% не успешных тестов

#### Создан баг-репорт [ссылка](https://github.com/venom4ek/Money-Transfer/issues/1)
Необходимо для входных данных изменить тип переменной с int на long. <br>
Это связанно с тем что тип данных int имеет 32 бита.
