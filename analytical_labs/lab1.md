# **Лабораторная работа 1 (AWS)**
## *Вариант 8*

### Команда SkyФом:
Файзулин Радмир (кэп) |
Куцак Анастасия |
Митилёва Людмила

### Цель работы:
Знакомство с облачными сервисами. Понимание уровней абстракции над инфраструктурой в облаке. Формирование понимания типов потребления сервисов в сервисной-модели. Сопоставление сервисов между разными провайдерами. Оценка возможностей миграции на отечественные сервисы.

### Дано:
1. Слепок данных биллинга от провайдера после небольшой обработки в виде SQL-параметров.
2. Google с документациями провайдера

### Необходимо:
Проанализировать сервисы и подобрать отечественные аналоги, если это возможно.

## | Ready
## | Steady
## | GO!

# Ход работы
____________
### AmazonFSx
Управляемый сервис файлового хранилища. Позволяет легко создавать и управлять высокопроизводительными файловыми системами, предназначенными для различных приложений и рабочих нагрузок. Предоставляет хранение файлов, данных и резервных копий.
Обещает масштабируемость, надежность и гибкое управление.
### Аналог - Yandex Cloud
На самом деле аналог далеко не полностью покрывает функционал. Например, Yandex Cloud не поддерживает FTP протоколы. Но основной недостаток - типов файловой системы всего два (Windows и Linux), тогда когда у AmazonFSx их сразу пять! В остальном аналог довольно близок к исходнику.
_______________________________________________________________________________
