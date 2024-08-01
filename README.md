# Домашнее задание к занятию "Репликация и масштабирование. Часть 1" - Баланюк Евгения

---

### Задание 1

На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

### ОТВЕТ:

Репликация master-slave: это наличие одного мастера и одного или несколько slave-серверов. Изменения в базе данных происходит только на мастере.

Реплекация master-master: сервера одновременно выступают и мастером и ведомым, изменения можно производить на любом мастере.


---

### Задание 2

Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

*Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.*

### ОТВЕТ:

![](https://github.com/EvgeniyaBalanyuk/replication/blob/main/replication.png)

![](https://github.com/EvgeniyaBalanyuk/replication/blob/main/replication_master.png)

![](https://github.com/EvgeniyaBalanyuk/replication/blob/main/replication_slave.png)

---
