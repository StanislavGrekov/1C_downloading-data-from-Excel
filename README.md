﻿## Обработка по загрузке данных из Excel в документ Поступление товаров

### Задача:

Сделать обработку по загрузке номенклатуры из Excel в документ Поступление товаров, в табличную часть Товары. Документ создавать новый, проводить. Предусмотреть возможность выбора организации, контрагента и договора для загрузки. Не найденную номенклатуру создавать в справочнике. Вид номенклатуры: Товар, ставка НДС: 20%.

### Описание

Задача реализована с использованием Асинхронных функций, Временного хранилища.


### Инструкция:

1. Скачать .dt, разdернуть на платформе 8.3.24.1667

2. Зайти в режим Предприятия-Справочники и создать Договор, Контрагентов между которыми будет формироваться документ Поступления товаров

3. Перейти в раздел Обработки/Отчеты-Загрузка файла xlsx

4. Указать Договор, Когнтрагентов и выбрать файл Номенклатура.xlsx, данные из которого будут перенесены в документ Поступления товаров.
