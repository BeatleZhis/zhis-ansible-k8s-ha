# Роль для создания HA кластера k8s

## Описание 
Схема раскатки:
![alt text](scheme.png)
Без использования haproxy!
Только 2 VIP IP:
- Для мастеров как control-plane-endpoint
- Для воркеров для использования в Ingress 

## Совместимость
Тестировалось на https://cloud.debian.org/images/cloud/bookworm/latest/debian-12-generic-amd64.qcow2 