# Требование к проекту 
# Содержание 
[1 Введение](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#1-введение)  
[2 Требования пользователя](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#2-требования-пользователя)  
[2.1 Программные интерфейсы](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#21-программные-интерфейсы)  
[2.2 Интерфейс пользователя](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#22-интерфейс-пользователя)  
[2.3 Характеристики пользователя](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#23-характеристики-пользователей)  
[2.4 Предположения и зависимости](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#24-предположения-и-зависимости)  
[3 Системные требования](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#3-системные-требования)  
[3.1 Функциональные требования](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#31-функциональные-требования)  
[3.2 Нефункциональные требования](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#32-нефункциональные-требования)  
[3.2.1 Атрибуты качества](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#321-атрибуты-качества)  
[3.2.2 Требования к безопасности](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#322-требования-к-безопасности)  
## 1 Введение  
Задумкой проекта является создание desktop-го программного обеспечения для управления продажей комплектующих компьютерной техники. Продавец является пользователем приложения. Он может просматривать списки комплектующих, добавлять их в списки, удалять, изменять. Также можно добавлять данные о покупателе, удалять, редактировать.  Предусмотрена вкладка «история заказов» в которой можно просмотреть данные покупателя и его заказы. Список комплектующих реализована в виде древовидного списка.
## 2 Требования пользователя  
## 2.1 Программные интерфейсы 
Продукт должен иметь графический интерфейс. Для этого будет использоваться фреймворк Qt. Все данные  (списки комплектующих, покупателей, истории заказов) будут храниться в базе данных mysql. Приложение должно быть написано на языке программирования с++.  
## 2.2 Интерфейс пользователя  
## Окно пользователя  
Главная вкладка "Товары"  
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF1.png)  
Вкладка "Информация" в которой содержится информация о покупателе  
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF2.png)  
Вкладка "Заказы" в которой показан заказ покупателя  
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF3.png)  
## 2.3 Характеристики пользователей  
Пользователь приложения - продавец компьютерной техники. Это люди всех возрастов имеющий хороший уровень знаний в эксплуатации компьютера. Которые могут собрать самостоятельно компьютер и разбираются в комплектующих и переферийных устройствах ПК.
## 2.4 Предположения и зависимости 
Для приложения требуется компьютер и немного свободного места.
## 3 Системные требования  
Приложение требует установленной базы данных MySQL, файлов Qt. А также небольшого количества свободного места на диске.
## 3.1 Функциональные требования 
1.Просмотр списка комплектующих  
2.Редактирование списка комплектующих  
3.Удаление компектующее из списка комплектующих  
4.Добавление покупателя в список покупателей   
5.Редактирование информации о покупателе  
6.Удаления покупателя из списка покупателей  
7.Оформление заказа (связь покупателя с выбранными комплектующими)  
8.Редактирование заказа  
9.Сохранение истории покупок  
## 3.2 Нефункциональные требования  
## 3.2.1 Атрибуты качества
Атрибуты важные для пользователя:  
1.Удобство в использовании  
2.Понятный интерфейс   
3.Легкость редактирования ошибок  
## 3.2.2 Требования к безопасности  
Информация о покупателях хранится в базе данных. Личные данные должны кодироваться, чтобы при краже злоумышленники не могли пользоваться ими.
