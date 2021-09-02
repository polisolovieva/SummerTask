## Задания к главе 15
1. Создать файл XML и соответствующую ему схему XSD. См. приложение
   № 3 этой книги.
2. При разработке XSD использовать простые и комплексные типы, перечисления, шаблоны и предельные значения.
3. Сгенерировать класс, соответствующий данному описанию.
4. Создать приложение для разбора XML-документа и инициализации коллекции объектов информацией из XML-файла. Для разбора использовать
   SAX, DOM и StAX-парсеры. Для сортировки объектов использовать интерфейс Comparator.
5. Произвести проверку XML-документа с привлечением XSD.
6. Определить метод, производящий преобразование разработанного XML-документа в документ, указанный в каждом задании.



### 11. Туристические путевки.
Туристические путевки, предлагаемые агентством, имеют следующие характеристики:
 - Type — тип (выходного дня, экскурсионная, отдых, паломничество и т.д.);
- Country — страна, выбранная для путешествия;
- Number days/nights — количество дней и ночей;
- Тransport — вид перевозки туристов (авиа, ж/д, авто, лайнер);
- Hotel characteristic (должно быть несколько) — количество звезд, включено ли питание и какое (HB, BB, Al), какой номер (1-, 2-, 3-местные),
есть ли телевизор, кондиционер и т.д.;
- Сost — стоимость путевки (сколько и что включено).
Корневой элемент назвать Тourist voucher.
 - С помощью XSL преобразовать XML-файл в формат HTML, c выводом
информации в табличном виде