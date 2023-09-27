# Шаблоны заяявок

### Задача

Создать которая будет перезаполнять данные минимального и страхового запаса в обработке "Формирование запасов по потребностям"
В разные дня нужно использовать разные мин и макс значения. Например в будние дни нужно делать расчет на 2 дня а на выходные на 3 и более.

![Alt text](image/image-1.png)

### Решение

- На форму обработки расположить табличную чатсть, и заполнить ее номенклатурой с нужными значениями
- Добавить возможно сохранения табличной части в файл и загрузки из файла обратно
- Обращайсь к Регистру сведений "Товарные ограничения", заменить значения на данные из табличной части
