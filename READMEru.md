# Получение сводной таблицы Excell из двух входящих
Программа реализует чтение данных из двух таблиц с поставщиками и их платежа1ми(pos.xls и  opl.xlsx соответсвенно), записи их в базу  Мs Access(Report.accdb) и формирование на основании всех данных базы сводного отчета(Report.xlsx) по правилу: поставщики с данными по договору, и суммы платежей по месяцам.
##Установка
Программа написана на пайтоне3.7 и ожидается, что он уже установлен
В случае конфликта с пайтон2 использульте pip3.Установите необходимы модули:

	pip install -r requirements.txt

Также программа использует tkinter, но, так как он в большинстве поставок идет предустановленным, он не указан. Если он не установлен:

	pip install python3-tkinter

## Использование
Основным файлом является  forms.py. Для его штатной работы необходимо присутствие в том же каталоге файла базы данных(Report.accdb).  Выходящий файл Report.xlsx формируется в этом же каталоге.


Svod1.py - осуществление той же логики, но используя только входящие файлы, и формирование выходного файла без использования базы данных.

## Описание проекта
Написан под конкретную конфигурацию экселевских файлов и данных в них содержащихся, возможность другой структуры данных не учитывается. 

