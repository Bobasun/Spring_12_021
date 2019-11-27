#Spring_12_02

![alt tag](https://github.com/Rooman/Spring_12_02/blob/master/springDiagram.png)

<h3>Задача: перевести все приложение на спринг.</h3>
<ol>
<li>Сделать бинами все бизнес объекты</li>
<li>Все зависимости организовать в xml</li>
<li>MockDataStore должен быть бином, описаным в xml;</li>
<li>Создать два класса UserCache и AccountCache, которые должны вычитывать данные из MockDataStore при старте, чтобы избежать постоянного обращения к хранилищу.</li>
<li>Инициализация кэшей должна происходить сразу после создания бина</li>
<li>Тесты должны быть запущенны через стандартный механизм для поднятия тестового контекста спринг</li>
<li>Все зависимости (по возможности) организовать через аннотации @Service, @Repository </li>
</ol>
