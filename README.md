Проект второго спринта Яндекс Практикума "Путешествие по России"

Страница написана по БЭМ-методологии с использованием адаптивной верстки под 4 вида устройств с разрешениями: 1280, 1024, 768 и 320 пикселей, и состоит из 7 блоков:

1. Блок Header:
   Содержит в себе логотип и ссылки переключения языка, подчеркивающиеся при наведении. Для расположения элементов применен Flex.

2. Блок Introduction:
   Содержит главный заголовок, подзаголовок, изображение и подпись к нему.

3. Блок Info:
   Текстовый блок, состоящий из заголовка, параграфа и списка.

4. Блок Photo:
   Блок, состоящий из картинок, распределенных автоматически с помощью Grid - сетки и свойства auto-fit. Размер картинкам задан в относительных величинах, чтобы при
   изменении разрешения, они плавно уменьшались/увеличивались.

5. Блок Places:
   Состоит из пяти подблоков, распределенных автоматически с помощью grid-row. Элементы дочерних блоков также расположены в грид-сетке:
   сначала в двух колонках и двух строках, а при разрешении для мобильных устройств в одной колонке и четырех строках, с равными промежутками между ними. Ссылки ведут на сторонние ресурсы, при наведении плавно меняют прозрачность.

6. Блок Cover:
   Содержит background-изображение, ссылку, кликабельную в любой части блока, заголовок и подзаголовок. При наведении курсора или нажатии на мобильном устройстве меняет фоновый цвет.

7. Блок Footer:
   Состоит из ссылок на полезные ресурсы и имя автора. Ссылки также при наведении курсора или клике на мобильном устройстве меняют прозрачность. Элементы блока распределены с помощью Flex.
