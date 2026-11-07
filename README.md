# Домашнее задание к занятию "`ELK`" - `Павлова Алена`



## Задание 1. Elasticsearch
Скриншот вывода `curl` с измененным `cluster_name` (`netology-alena-homework`):

![Задание 1](https://github.com/Alena97dv/elk-homework/blob/main/Задание%201.png)

---

## Задание 2. Kibana
Скриншот интерфейса Kibana с запросом `GET /_cluster/health?pretty`:

![Задание 2](https://github.com/Alena97dv/elk-homework/blob/main/Задание%202.png)
![Задание 2](https://github.com/Alena97dv/elk-homework/blob/main/Задание%202%20(2).png)

---

## Задание 3. Logstash и Nginx
Скриншот Kibana (Discover), где видны логи Nginx (`GET /final-check`), отправленные через Logstash:

![Задание 3](https://github.com/Alena97dv/elk-homework/blob/main/Задание%203.png)

---

## Задание 4. Filebeat
Скриншот 1 — терминал с `docker compose ps` (Logstash остановлен, Filebeat работает):
![Задание 4.1](https://github.com/Alena97dv/elk-homework/blob/main/задание%204(2).png)

Скриншот 2 — Kibana (Discover), логи Nginx (`GET /ilm-disabled-check`), отправленные напрямую через Filebeat:
![Задание 4.2](https://github.com/Alena97dv/elk-homework/blob/main/задание%204.png)
