# Pupyrus_platform
Pupyrus Platform repository

Домашнее задание №4

В ДЗ было сделанно:
1. Создал Service Account bob, дал ему роль admin в рамках всего кластера. Создал Service Account dave без доступа к кластеру
2. Создал Namespace prometheus. Создал Service Account carol в этом Namespace. Дал всем Service Account в Namespace prometheus возможность делат get, list, watch в отношении Pods всего кластера
3. Создал Namespace dev.Создал Service Account jane в Namespace dev. Дал jane роль admin в рамках Namespace dev. Создал Service Account ken в Namespace dev. Дал ken роль view в рамках Namespace dev