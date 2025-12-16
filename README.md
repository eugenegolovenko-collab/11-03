# Домашнее задание к занятию "`ELK`" - `Евгений Головенко`

---

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

### Решение 1.

<img width="526" height="701" alt="ELK_Capture_1" src="https://github.com/user-attachments/assets/78f1b8bc-fce2-4a32-a548-f79f35fa5d76" />

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### Решение 2.

<img width="1279" height="875" alt="ELK_Capture_2" src="https://github.com/user-attachments/assets/9824fe67-0e01-46f9-80d4-e97e05d51758" />

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### Решение 3.

<img width="927" height="76" alt="ELK_Capture_4" src="https://github.com/user-attachments/assets/ddf0df6a-39fa-4709-bbd3-e167e949ca4e" />

<img width="1279" height="875" alt="ELK_Capture_3" src="https://github.com/user-attachments/assets/b7f499dd-9885-46d9-8a53-0c0723dda513" />


---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

### Решение 4.

<img width="1285" height="1031" alt="ELK_Capture_5" src="https://github.com/user-attachments/assets/d929303f-f9ab-49af-a382-f8a17090449d" />

