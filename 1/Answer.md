# Домашняя работа №1.

## 1. Проблемы датасета
- Много пропущенных значений (в столбце 'age' - 177, 'cabin' - 687, 'embarked' - 2). Данная проблема могла возникнуть, например, если эти данные не были занесены изначально (при регистрации пассажиров на рейс). В случае с возрастом проблема может быть решена, к примеру, с помощью использования медианных значений для групп пассажиров. А для столбца 'embarked' можно испльзовать наиболее часто встречающееся место посадки.
- В некоторых столбцах (например, имя) данные неоднородные - в таком виде их трудно будет использовать для анализа. Эта проблема также скорее всего возникла при занесении данных в базу. Решается проблема легко, можно разнести по разным стобцам имена и фамилии. В случае со столбцом "ticket" нужно понять, что знают буквы, и, возможно, просто убрать их.



## 2. Шансы на выживание пассажиров на основании данных об их поле и классе

| Пассажир | Шансы на виживание|
|------|-----|
|Леонардо Ди Каприо|13,58%|
|Кейт Уинслет|96,81%|

Ссылка: https://docs.google.com/spreadsheets/d/16GjYTMATTbc3LUgGkzHG3nV4KUfvIV46yd59M0z2ink/edit#gid=786513138
