Для обращения к кластеру {{ k8s }} используйте его имя или уникальный идентификатор, которые можно узнать с помощью команды:

```bash
yc managed-kubernetes cluster list
```

Результат:

```bash
+----------------------+----------+---------------------+---------+---------+-------------------------+-----------------------+
|          ID          |   NAME   |     CREATED AT      | HEALTH  | STATUS  |    EXTERNAL ENDPOINT    |   INTERNAL ENDPOINT   |
+----------------------+----------+---------------------+---------+---------+-------------------------+-----------------------+
| cati493bu7ian006a5j7 | k8s-demo | 2019-11-20 11:26:36 | HEALTHY | RUNNING | https://84.201.174.147/ | https://192.168.0.27/ |
+----------------------+----------+---------------------+---------+---------+-------------------------+-----------------------+
```