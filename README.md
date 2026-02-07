# 🛡️ Путь в Cybersecurity

Репозиторий для фиксации прогресса, отчетов (write-ups) и инструментов в рамках подготовки к позиции Junior Security Researcher / AppSec.

## 📅 Текущий статус
- Неделя 1: Веб-логика и Инъекции (В процессе)

## 🛠️ Стек и инструменты
- Proxy: Burp Suite Professional
- OS: Kali Linux
- Platforms: PortSwigger Academy, Root-Me, VulnHub
- Languages: Python (Automation), Bash

## 📈 План обучения

| Неделя | Фокус | Ключевые навыки | Статус |
| :--- | :--- | :--- | :--- |
| 1 | Web Logic & Injections | SQLi, Auth Bypass, IDOR, Traversal | 🟡 Идет |
| 2 | Server Control (RCE) | Command Inj, File Upload, Fuzzing | ⚪ Ожидание |
| 3 | Python for Security | Automation, Brute-forcers, Requests | ⚪ Ожидание |
| 4 | Networks & PrivEsc | Linux Root, Nmap, Metasploit | ⚪ Ожидание |

## 📝 Журнал активности (Неделя 1)
- [x] SQL Injection: Практика UNION-based атак и перебор БД.
- [x] Authentication: Обход 2FA, манипуляция сессиями, Rate Limit Bypass.
- [x] Directory Traversal: Успешная эксплуатация на Root-Me (чтение защищенных файлов через параметры).
- [x] Access Control (IDOR & Mass Assignment): 
    - Эксплуатация IDOR через подмену параметров в URL.
    - Повышение привилегий (PrivEsc) через Over-posting/Mass Assignment в JSON-запросах.
    - Автоматизация поиска уязвимостей с помощью Burp Suite (Match and Replace).
