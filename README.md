# Требования к проекту 
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
[3.2.3 Ограничения](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/README.md#323-ограничения)
## 1 Введение  
Задумкой проекта является создание desktop-го программного обеспечения для управления продажей комплектующих компьютерной техники. Продавец является пользователем приложения. Он может просматривать списки комплектующих, добавлять их в списки, удалять, изменять. Также можно добавлять данные о покупателе, удалять, редактировать.  Предусмотрена вкладка «история заказов» в которой можно просмотреть данные покупателя и его заказы. Список комплектующих реализована в виде древовидного списка.
## 2 Требования пользователя  
## 2.1 Программные интерфейсы 
Продукт должен иметь графический интерфейс. Все данные  (списки комплектующих, покупателей, истории заказов) должны храниться в базе данных или в txt-файле.  
## 2.2 Интерфейс пользователя  
## Окно пользователя  
При запуске приложение должно отображаться вкладка "Товары"  
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF1.png)  
При нажатии на вкладку "Информация" отобразится  информация о покупателе    
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF2.png)  
При нажатии на вкладку "Заказы" отобразится заказ покупателя    
![](https://github.com/BSUIRstudent/TRITPO_LAB2/blob/main/mockups/%D0%BC%D0%BE%D0%BA%D0%B0%D0%BF3.png)  
## 2.3 Характеристики пользователей  
Пользователь приложения - продавец компьютерной техники. Это люди всех возрастов имеющий хороший уровень знаний в эксплуатации компьютера. Которые могут собрать самостоятельно компьютер и разбираются в комплектующих и переферийных устройствах ПК.
## 2.4 Предположения и зависимости 
Программа дожна быть только под ПК.
## 3 Системные требования  
Приложение требует установленной базы данных MySQL, файлов Qt.ОС Windows 10, а также небольшого количества свободного места на диске.  
Минмимальные системные требования:  
Видеокарта Intel(R) Iris(R) Xe Graphics  
Поцессор от Intel core i3  
Оператинвая память 4 гб  
Свободного пространства 100 Мб  
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
## 3.2.3 Ограничения    
Дизайн должен близко соответствовать пункту интерфейс пользователя.
