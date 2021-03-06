﻿# Friend Jobs

**Краткое описание**

Веб-приложение, позволяющее 
1. Осуществлять поиск объявлений о вакансиях в постах друзей и друзей-друзей в социальных сетях. 
2. Осуществлять поиск объявлений о вакансиях в социальных сетях в постах всех пользователей, ориентируясь на заданные пользователем фильтры: город, отрасль, зона ответственности, период публикации, название должности


## 1. MVP

**Краткое описание**

Веб-приложение, позволяющее искать объявления о вакансиях в постах друзей и друзей-друзей в Facebook и выводящее их в хронологическом порядке.

**Доступ к данным с VK**

Инициализация происходит через аккаут ~~Facebook~~ VK
*upd API Facebook не позволяет выгружать список друзей* 



**Фильтры**

Приложение включает три настраиваемых фильтра:
1. Город:
	1. Москва
	2. Санкт-Петербург
	
2. Зона ответственности:
	1. Продукт
	2. Маркетинг
	3. Продажи
	4. Саппорт
	5. Финансы
	6. Бухгалтерия
	7. Юристы
	8. Логистика и поставки 
	9. PR
	10. IT
	11. HR
 
3. Период публикации:
	1. 3 дня
	2. Неделя
	3. Месяц

**Формат вывода**

Информация выводится пользователю в виде ленты постов в хронологическом порядке.
Информация, содержащаяся в постах:

1. Фото пользователя
2. Фамилия и имя
3. Текст поста
4. Дата и время размещения публикации

Выводимые посты содержат гиперссылку, по клику на которую пользователь может перейти на сам пост в Facebook. Окно с постом Facebook открывается в отдельной вкладке.


**Референсы внешнего вида программы Friend Rent**

![Friend rent reference 1](http://runetmir.com/wp-content/uploads/2013/09/FriendRent.jpg)
![Friend rent reference 2](https://i.pinimg.com/originals/64/ae/19/64ae19b74ed6f0e10840f66a7377f02b.jpg)

## 2. Описание API

При разработке программы используется API VK.

