**WEB** **-приложение «** **teapot** **»**

**Техническое Задание**

Санкт-Петербург

2017\

Содержание

[1. Общие сведения](#Общие-сведения)

[2. Назначение и цели разработки]()

[2.1 Назначение разработки]()

[2.2.1 Цель разработки]()

[2.2.2 Целевая аудитория]()

[3. Требования к программному изделию]()

[3.1 Требования к структуре]()

[3.2 Требования к разграничению доступа]()

[3.3 Требования к функциональным характеристикам]()

[3.3.1 Структура Web-приложения]()

[3.3.2 Основные функции]()

[Варианты использования]()

\

****

Общие сведения
==============

1.1 Наименование разработки: ***teapot***

1.2 Условное обозначение: ***TPT-*** ***12E493C3***

1.3 Код документа: ***TPT-*** ***12E493C3\#01***

1.4 Плановые сроки начала и окончания работы по разработке: 22 мая – 31
июля 2017 г.

\

****

[2. Назначение и цели разработки]{#_Toc482543551}
=================================================

[2.1 Назначение разработки]{#_Toc482543552}
-------------------------------------------

Система предназначена для создания виртуальных корпоративных досок –
*«канбанов».*

### [2.2.1 Цель разработки]{#_Toc482543553}

Автоматизация процесса корпоративного ведения и управления проектами.

### [2.2.2 Целевая аудитория]{#_Toc482543554}

Корпоративные предприятия.

\

****

[3. Требования к программному изделию]{#_Toc482543555}
======================================================

[3.1 Требования к структуре]{#_Toc482543556}
--------------------------------------------

Программа должна представлять собой клиент-серверное WEB-приложение
(сайт), развёртываемое локально на сервере компании-покупателя.

[3.2 Требования к разграничению доступа]{#_Toc482543557}
--------------------------------------------------------

Пользователей приложения можно разделить на 4 части в соответствии с
правами доступа:

1\. Участники рабочей группы;

2\. Руководитель проекта;

3\. Руководитель рабочей группы;

4\. Администратор.

**Участники рабочей группы** могут:

· Перемещать, комментировать карточки в закреплённом за ним списке, а
так же прикреплять к карточкам дополнительные материалы (мультимедиа,
текстовые файлы, ссылки) **на досках тех проектов, в которых он
участвует**;

· Просматривать доски проектов внутри его рабочей группы;

· Создавать свои персональные доски, добавлять, редактировать,
перемещать карточки и прикреплять к ним доп. материалы.

Доступ к административной части приложения имеют пользователи с правами
руководителя рабочей группы/проекта и администратора.

**Руководитель проекта** может:

-   добавлять/удалять участников проекта;

· создавать доски в проектах, имея полный доступ к их функционалу, как в
случае с персональными досками;****

-   прикреплять участников к списку (столбцу).****

**Руководитель рабочей группы** имеет все права руководителя проекта, а
также **** может:

· создавать, удалять рабочие группы, добавлять и удалять участников
группы; ****

-   создавать проекты внутри рабочей группы;****
-   назначать руководителя проекта;****

**Администратор** занимается:

-   подтверждением регистрации сотрудников компании;
-   назначением прав доступа;
-   удалением (архивированием) пользователей.

****

[3.3 Требования к функциональным характеристикам]{#_Toc482543558}
-----------------------------------------------------------------

### [3.3.1 Структура]{#_Toc482543559} Web-приложения

Сайт должен состоять из следующих разделов:

-   главная страница
-   профиль
-   проекты
-   доски

### [3.3.2 Основные функции]{#_Toc482543560}

#### 3.3.2.1 Канбан-доски.

Канбан-доска имеет следующую структуру:

1\. Верхний уровень – сама доска;

2\. Списки (столбцы). Для каждого столбца можно указать ограничение на
количество карточек в этом столбце;

3\. Нижний уровень – карточки;

Функционал досок:

1\. создание/удаление доски;

2\. добавление/удаление списков;

2.1. прикрепление участников-исполнителей к списку (столбцу доски)

2.2. установка ограничения на максимальное кол-во карточек в списке

3\. добавление/удаление карточек;

3.1. перемещение карточек по спискам;

3.2. комментирование карточек;

3.3. форматирование (markdown) карточек;

3.4. прикрепление доп. материалов (мультимедиа, текстовые файлы,
ссылки).

#### 3.3.2.2 Регистрация пользователя.

Регистрация должна осуществляться с помощью заполнения соответствующей
формы регистрации.

Форма регистрации:

-   Адрес электронной почты;
-   ФИО;
-   Логин;
-   Пароль.

#### 3.3.2.3 Профиль пользователя.

На странице с профилем пользователя должна находиться основная
информация о пользователе, рабочих группах и проектах, в которых он
состоит или которыми руководит.

Информация о пользователе:

-   аватар;
-   ФИО;
-   статус

o в сети;

o не в сети;

o удалён (назначается администратором);

-   графа «О себе»;
-   рабочие группы;
-   проекты;
-   личные доски (видна только пользователю).

#### 3.3.2.4 Проекты и рабочие группы.

-   создание/удаление рабочей группы;
-   добавление/удаление участников группы;
-   создание/удаление проекта;

· добавление участников из рабочей группы в проект или удаление из него;

-   назначение руководителя проекта;
-   создание досок внутри проекта.

#### 3.3.2.5 Администрирование

*(Примечание:* функции данного раздела доступны только
**администраторам** WEB-приложения).

-   подтверждение регистрации сотрудников компании

· назначение прав доступа руководителям рабочих групп/проектов

-   назначение статусов пользователям

\

### [Варианты использования]{#_Toc482543561}


Основное действующее лицо | Варианты использования
------------------------- | ----------------------
Администратор|подтверждение регистрации сотрудников компании; назначение прав доступа руководителям рабочих групп/проектов; назначение статусов пользователям
Руководитель рабочей группы/проекта|создание/удаление рабочих групп; добавление/удаление участников в группы/проекты; добавление/удаление канбан-досок проектов; добавление/перемещение карточек; прикрепление доп. материалов к карточкам (мультимедиа, текстовые файлы, ссылки); прикрепление участников к карточкам
Участник рабочей группы | перемещение карточки с пометкой «выполнено» в следующий список; перемещение карточки с пометкой «на доработку» в предыдущий список; комментирование карточки при её перемещении; прикрепление доп. материалов к карточкам (мультимедиа, текстовые файлы, ссылки); создание личных досок
