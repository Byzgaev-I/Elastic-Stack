# Домашнее задание "Система сбора логов Elastic Stack"   

---

### Задание 1 

Вам необходимо поднять в докере и связать между собой:

- elasticsearch (hot и warm ноды);
- logstash;
- kibana;
- filebeat.
Logstash следует сконфигурировать для приёма по tcp json-сообщений.

Filebeat следует сконфигурировать для отправки логов docker вашей системы в logstash.
В директории [help](https://github.com/netology-code/mnt-homeworks/tree/MNT-video/10-monitoring-04-elk/help) находится манифест docker-compose и конфигурации filebeat/logstash для быстрого выполнения этого задания.
Результатом выполнения задания должны быть:

- скриншот docker ps через 5 минут после старта всех контейнеров (их должно быть 5);
- скриншот интерфейса kibana;
- docker-compose манифест (если вы не использовали директорию help);
- ваши yml-конфигурации для стека (если вы не использовали директорию help).


![image.jpg](https://github.com/Byzgaev-I/Grafana/blob/main/2.png)
