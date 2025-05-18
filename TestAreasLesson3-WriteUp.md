# Web Testing

## Architecture

They typically follow a three-tier architecture:

- Presentation tier (frontend)
- Application tier (backend)
- Database tier

**Hard Skills & Teoretic**

1. HTTP/HTTPS, HTML, CSS, JavaScript

2. PHP, Python или Java

3. SQL и NoSQL

## Common Web Application Vulnerabilities

1. SQL injection - Одна из самых серьезных уязвимостей возникает, когда приложение не может очистить данные, используемые в запросах к базе данных

2. XSS - Уязвимости возникают, когда приложения не могут очистить данные, которые отображаются другим пользователям.

3. Weaknesses in authentication - Несанкционированный доступ.

## Tools and skills

1. BurpSuite - postwigger academy learn

2. Owasp ZAP

# Network Testing

## Common Network Security Vulnerabilities

1. Misconifgured Services - Неправильная настройка сетевых служб (Открыты ненужные порты)

2. Unpatched Systems - Устаревшие версии ПО

3. Weak Authentication - Плохая политика паролей

4. Network Segmentation Issues - Недостаточная сегментация сети (Горизонтальное перемещение по сети между различными зонами)

5. Exposed Managment Interfaces - Админ панели, доступные из сетей или общего доступа(Интернета)

6. Missing Security Controls - Отсутствие основных мер безопасности (IDS/IPS, Firewall)

**Hard Skills & Teoretic**

1. TCP/IP, UDP, ICMP

2. HTTP, FTP и SSH

## Tools

1. Nmap - Сканирование сети

2. Nessus, OpenVAS - Выявление известных уязвимостей

3. Metasploit Framework - выполнение эксплойтов

4. Wireshark - Анализ сетевого трафика

5. Hashcat/John the Ripper - Безопасность паролей (вычисление хэша)

# Cloud Testing

- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

**Hard Skills & Teoretic**

1. Docker/Kebernetes

## Stages

1. Recon

2. Access Control Identetity and Access Managment IAM

3. Security Misconfigurations

4. Virtual Network Configurations

5. Data Security DLP

6. Application Security

# Social Engineering

## Techniques

1. Phishing - Отправку вводящих в заблуждение писем\сообщений

2. Pretexting - Сфабрикованного сценария для получения информации или доступа.  (Выдача себя за другого, например: Электрик запрашивает схему электрокаблей)

3. Baiting - Использует человеческое любопытство, оставляя зараженные USB-накопители или другие вредоносные устройства в местах, где их могут найти и использовать цели.

4. Tailgating - Использование человеческого фактора (Забытые карты доступа и тд)



# Mobile Testing

1. BYOD Policies -  Компаниям необходимо обеспечить безопасность личных устройств сотрудников, которые получают доступ к рабочим ресурсам.

2.  Data Breach Costs - Сбои в системе безопасности приводят к штрафам, юридическим проблемам и ущербу репутации.

3.  Remote Work Revolution  -  Чем больше людей работают удаленно, тем больше мобильных устройств подключаются к сетям компании.

4.  Compliance Requirements - Законы требуют строгих мер защиты данных и конфиденциальности.

5.  Advanced Threats - Мобильные устройства подвергаются атакам вредоносных программ, фишинга и новых эксплойтов безопасности.



## Setting Up Your Testing Environment

- Инструменты управления мобильными устройствами, такие как Android Debug Bridge (ADB) для Android
- Инструменты реверс-инжиниринга, такие как JADX и Ghidra, IDA pro
- Инструменты отладки для конкретных платформ
- Инструменты тестирования мобильных фреймворков, такие как Frida и Objection



## Android Security Testing

1. Static Analysis - Приложений Android включает в себя декомпиляцию APK и изучение исходного кода на наличие проблем с безопасностью

2.   Dynamic Analysis -  Состоит из запуска приложения и наблюдения за его поведением в режиме реального времени



#### iOS Security Testing Specifics

- Использование связки ключей и защита данных
- Реализация закрепления сертификатов
- Локальные методы хранения данных
- Обработка схемы URL
- Внедрение Touch ID/Face ID



## Common Mobile Vulnerabilities

1.  Insecure Data Storage - Конфиденциальная информация хранится в открытом виде или со слабым шифрованием.

2.  Insecure Channels - Приложения могут неправильно проверять сертификаты SSL/TLS

3.  Client-side Injections -  SQL-инъекцию в локальных базах данных



# Reverse Engineering



**Реверс-инжиниринг — это процесс анализа и понимания того, как работают программное обеспечение, системы или приложения, путем изучения их компонентов, структуры и функциональности.**



**Hard Skills**

1.  Knowledge of programming languages (C, C++, C#, Java)

2.  Operating system internals (управление памятью, обработку процессов и системные вызовы)

3.  Software design (понимание общих шаблонов, структур данных и алгоритмов помогает распознавать реализованные функции при анализе декомпилированного кода)

4.  Network Protocols (знание API и обмен данными также ценны, особенно для приложений, которые взаимодействуют с удаленными серверами)



**Реверс-инжиниринг обычно делится на 2 этапа**

1. Статистический анализ - анализ программного кода без непосредственного выполнения программы.

2.  Динамический анализ - анализ в процессе, пост-процессе запущенного вредносного приложения. 
