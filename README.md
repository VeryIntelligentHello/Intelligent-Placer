# Intelligent Placer
Программа, которая по полученным фотографиям, с разными объектами и контуром многоугольной области, определяет, помещаются ли данные объекты во внутрь многоугольной области.

## Постановка задачи
- На вход подается путь к фотографии, на которой изображены объекты и нарисованный на белом листе бумаги контур многоугольника.
- На выход в стандартный поток вывода программа возвращает True/False, если объекты помещаются во внутрь многоугольника или нет, соответственно.

## Требования
### К входным фотографиям:
- Формат фотографий *\*.jpg*
- Угол съемки перпендикулярен к поверхности и высота съемки не меняется
- Качество фотографий одинаковое - фокус и освещение не меняются
### К содержанию фотографий
- Контур многоугольной области должен быть размещен на белом листе бумаги и быть четко видным
- Лист бумаги должен быть прямоугольным
- Многоугольная область должна быть замкнутой и выпуклой
- Количество граней многоугольной области не более 7
- Объекты не должны перекрывать друг друга, выходить за кадр и повторяться
- Поверхность должна быть светлая и не должна совпадать с цветом листа бумаги

## Данные
- [Изображения объектов и фона](Intelligent-Placer/InputData)
- [Тесты](Intelligent-Placer/Tests/Description.md)
