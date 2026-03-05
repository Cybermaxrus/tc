Оглавление
- [Контейнеризация](#контейнеризация)
  - [Оркестрация](#оркестрация)
  - [Мониторинг и Наблюдаемость / Monitoring \& Observability (Metrics)](#мониторинг-и-наблюдаемость--monitoring--observability-metrics)
  - [Логирование / Logging (Events \& Audit)](#логирование--logging-events--audit)
  - [Система управления конфигурациями](#система-управления-конфигурациями)
  - [Хранение секретов и ключей / Secret Management](#хранение-секретов-и-ключей--secret-management)
  - [Управление привилегированным доступом / Privileged Access Management (PAM)](#управление-привилегированным-доступом--privileged-access-management-pam)
  - [Управление идентификацией и доступом / Identity and Access Management (IAM)](#управление-идентификацией-и-доступом--identity-and-access-management-iam)
  - [Базы данных](#базы-данных)
  - [Брокер сообщений](#брокер-сообщений)
  - [Облачные вычисления](#облачные-вычисления)
  - [Система управления версиями](#система-управления-версиями)
  - [Резервное копированиие](#резервное-копированиие)
  - [Языки программирования](#языки-программирования)




1. [Контейнеризация](#контейнеризация)
  - Docker
  - Podman (от Pod Manager)
  - Containerd
  - Minikube
  - Buildah
   
2. [Оркестрация](#оркестрация)
 - Kubernetes (K8s)
 - Docker Swarm
 - HashiCorp Nomad
    
3. [Мониторинг](#мониторинг)
 - Prometheus
 - VictoriaMetrics
 - Grafana
 - Zabbix

   
4. [Логирование](#логирование)
 - Elasticsearch, Logstash, Kibana (ELK)
 - Elasticsearch, Fluentd, Kibana (EFK)
 - Grafana Loki 
 - Fluentd 
 - Graylog


5. [Система управления конфигурациями](#Система-управления-конфигурациями)
 - Progress Chef
 - Puppet
 - Ansible
 - Ansible Molecule
 - HashiCorp Vagrant
 - Terraform
 - CDK8s
 - Crossplane
 - Pulumi



6. [Базы данных](#базы-данных)
 - ClickHouse
 - PostgreSQL
 - MongoDB

   
7. [Брокер сообщений](#брокер-сообщений)
 - RabbitMQ
 - Apache Kafka
 
   
8. [Облачные вычисления](#облачные-вычисления)
 - Amazon Web Services (AWS)
 - Microsoft Azure
 - Google Cloud Platform (GCP)
 

9. [Система управления версиями](#система-управления-версиями)
 - Git
 - Bitbucket

 
10. [Резервное копированиие](#Резервное-копированиие)
   - UrBackup
   - Amanda
   - Duplicati
   - Bacula
   - Borg
   - kopia
   - Restic


1.5. IP-телефония (VoIP) — это современная технология передачи голосовых и видеосообщений через интернет-протокол (IP), заменяющая традиционные аналоговые линии.
  -  1.6.1. Asterisk (Астериск)
  -  1.6.2. FreePBX
  -  1.6.3. Issabel PBX
  -  1.6.4. VitalPBX 
  -  1.6.5. Incredible PBX

1.6. Почтовые серверы


1.5. [Язык Программирования](#Языки-программирования)
   -  C++
   -  Java
   -  JavaScript (JS)
   -  TypeScript
   -  Python    



//[Fourth Example](#fourth-examplehttpwwwfourthexamplecom)


# Контейнеризация
1. Контейнеризация виртуализация на уровне операционной системы, контейнерная виртуализация, зонная виртуализация) — метод виртуализации, при котором ядро операционной системы поддерживает несколько изолированных экземпляров пространства пользователя вместо одного.
* [62. Основы контейнеризации](https://basis.gnulinux.pro/ru/latest/basis/62/62._Основы_контейнеризации.html)

  1.1 Docker — инструмент для автоматизации процесса развертывания и управления приложениями в контейнеризированных средах. Он используется как средство контейнеризации приложений, позволяя упаковать приложение вместе со всеми его настройками и зависимостями в контейнер.
* [Docker для начинающих: что это такое и как пользоваться](https://habr.com/ru/companies/netologyru/articles/967546/)
* [Почти все, что вы хотели бы знать про Docker](https://habr.com/ru/articles/822707/)
* [Docker на каждый день: Ключевые команды в одной статье-шпаргалке](https://habr.com/ru/articles/913978/)
* [Docker изнутри: исчерпывающее руководство. Механизмы контейнеризации + примеры, эксперименты и реализация](https://habr.com/ru/articles/935178/)
* [Docker для начинающих: простое развертывание приложения за несколько шагов](https://habr.com/ru/articles/888540/)
* [Исповедь Docker-хейтера](https://habr.com/ru/articles/467607/)
* [Docker для Начинающих – Полный Курс](https://www.youtube.com/watch?v=n9uCgUzfeRQ)
* [Docker для новичков - #1 Что такое докер, контейнер и image, Docker Desktop?](https://www.youtube.com/watch?v=RLfWakY-Ueo)
* [УРОКИ ДОКЕР ДЛЯ НАЧИНАЮЩИХ - ОТ А до "Ж" | Основы докера для начинающих | Установка докера](https://www.youtube.com/watch?v=UZgYKbrNAdw)
* [Ящик со змеями: контейнеризация Python-приложений и работа с Docker «Python Developer. Professional»](https://www.youtube.com/watch?v=6wp6nZMl2YI)
* [Docker для Python разработчика // Демо-занятие курса «Python Developer. Professional»](https://www.youtube.com/watch?v=qiIQPXwqSTg)


 1.2. Podman (от Pod Manager — это командный инструмент с открытым исходным кодом, созданный для управления контейнерами и подами (группами связанных контейнеров). 
Podman позволяет создавать группы контейнеров с общими сетевыми и пространственными ресурсами, что ближе к концепции Kubernetes и облегчает оркестрацию сложных приложений.
Командная структура Podman практически идентична Docker CLI, что делает переход для пользователей интуитивным и простым.

* [Что такое Podman: управление контейнерами и установка на Linux](https://selectel.ru/blog/tutorials/what-is-podman/)
* [63. Работа с podman](https://basis.gnulinux.pro/ru/latest/basis/63/63._%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D1%81_podman.html)
* [Что такое Podman и чем он лучше Docker?](https://zomro.com/rus/blog/faq/649-what-is-podman-and-how-is-it-better-than-docker)
* [Используем контейнеры Podman вместо виртуальных машин](https://habr.com/ru/companies/timeweb/articles/585758/)
* [Основы контейнеризации (обзор Docker и Podman)](https://habr.com/ru/articles/659049/)
* [Используем функционал Podman вместо docker-compose на примере Gitea](https://habr.com/ru/articles/705614/)
* [Вы должны перейти на Podman сейчас же. Но это не точно…](https://habr.com/ru/companies/cdnnow/articles/825828/)
* [Используем контейнеры Podman вместо виртуальных машин](https://habr.com/ru/companies/timeweb/articles/585758/)
* [Установка Podman - который является инструментом управления контейнерами на Fedora Server 41](https://www.youtube.com/watch?v=UOZNCrC7QFw)
* [Podman - подготовка окружения в ОС Альт Linux для работы с docker-контейнерами](https://www.youtube.com/watch?v=2RFKzx9YKIw)
* [Запуск первого контейнера из образа Python в Podman](https://www.youtube.com/watch?v=HRltFgrwLFs)
* [Docker Для Начинающих за 1 Час | Docker с Нуля](https://www.youtube.com/watch?v=lr1rYnUubpQ)
* [/r/podman/](https://www.reddit.com/r/podman/)


1.3. Containerd — это высокоуровневая, открытая среда выполнения контейнеров, созданная для управления жизненным циклом контейнеров, включая их запуск, остановку и управление образами. Изначально разработанный компанией Docker, этот проект был передан в фонд Cloud Native Computing Foundation (CNCF) и сейчас выступает как самостоятельное, минималистичное решение, обеспечивающее производительность и безопасность для систем управления контейнерами более высокого уровня, таких как Kubernetes.
* [Зачем нужен containerd и почему его отделили от Docker](https://habr.com/ru/companies/flant/articles/325358/)
* [Различия между Docker, containerd, CRI-O и runc](https://habr.com/ru/companies/domclick/articles/566224/)
* [Да что такое этот ваш containerd?](https://medium.com/@anatoliibriushinin/what-is-containerd-bf36c39875c5)
* [Записки о containerd](https://habr.com/ru/articles/568274/)
* [Зрелая исполняемая среда для контейнеров: containerd стал «выпускником» CNCF](https://habr.com/ru/companies/flant/articles/442036/)



1.4. Minikube - это утилита командной строки, которая позволяет легко развертывать локальный кластер Kubernetes. Она полезна для разработчиков, которым нужна локальная среда Kubernetes для тестирования и разработки приложений.
* [Развертывание Kubernetes-кластера с помощью minikube](https://learning.infoteam.msk.ru/Rebrain/K8s/KUB 02 Развертывание Kubernetes-кластера с помощью minikube.pdf)
* [Привет, Minikube](https://kubernetes.io/ru/docs/tutorials/hello-minikube/)
* [Мой полный курс по изучению Kubernetes с использованием Minikube!](https://www.reddit.com/r/kubernetes/comments/go5nug/my_complete_course_on_learning_kubernetes_using/?tl=ru)
* [Работа в Kubernetes с помощью Minikube](https://selectel.ru/blog/tutorials/how-to-run-kubernetes-with-minikube/)
* [Начало работы в Kubernetes с помощью Minikube](https://habr.com/ru/companies/flant/articles/333470/)
* [Kubernetes vs Docker Swarm: что выбрать](https://msk.top-academy.ru/articles/kubernetes-vs-docker-swarm-chto-vybrat)
* [Как обеспечить высокую доступность в Docker Swarm](https://labex.io/ru/tutorials/docker-how-to-ensure-high-availability-in-a-docker-swarm-411536)
* [1 - Что такое Kubernetes? Запуск локального кластера Kubernetes. Minikube](https://www.youtube.com/watch?v=Amkkr4_nsyc)




1.5 Buildah — это мощный инструмент командной строки, предназначенный для сборки контейнерных образов, соответствующих стандарту OCI (Open Container Initiative). С его помощью можно как вручную писать скрипты для сборки, так и использовать готовые файлы инструкций, такие как Dockerfile или Containerfile. 
Buildah предлагает возможность создания образов из базового компонента scratch, что идеально подходит для минимизации контейнеров и включения только требуемых элементов. Такая функциональность делает Buildah универсальным решением для разработки образов с точным контролем и высокой степенью совместимости с современными контейнерными инфраструктурами.
* [Начало работы с Buildah](https://andreyex.ru/operacionnaya-sistema-linux/nachalo-raboty-s-buildah/)
* [Рекомендации по запуску Buildah внутри контейнера](https://habr.com/ru/companies/redhatrussia/articles/470928/)
* [Podman и Buildah для пользователей Docker](https://habr.com/ru/companies/redhatrussia/articles/467105/)
* [What is Buildah?](https://www.redhat.com/en/topics/containers/what-is-buildah)
* [Speeding up container image builds with Buildah](https://www.youtube.com/watch?v=qsh7NL8H4GQ)
* [Getting Started with Buildah](https://buildah.io/blogs/2017/11/02/getting-started-with-buildah.html) 




## Оркестрация
1. [Оркестрация в ИТ](https://ru.wikipedia.org/wiki/%D0%9E%D1%80%D0%BA%D0%B5%D1%81%D1%82%D1%80%D0%BE%D0%B2%D0%BA%D0%B0_(%D0%98%D0%A2)) — это автоматизированное управление, координация и интеграция сложных компьютерных систем, сервисов, приложений и данных для выполнения бизнес-процессов в правильной последовательности.
* [Оркестрация данных: основные элементы инфраструктуры и стратегии](https://practicum.yandex.ru/blog/orkestraciya-dannyh/)
* [Что такое оркестрация контейнеров](https://selectel.ru/blog/orchestration/)




1.1 [Kubernetes (K8s)](https://ru.wikipedia.org/wiki/Kubernetes) – это платформа с открытым кодом, предназначенная для автоматизации процессов размещения, масштабирования и администрирования приложений в контейнерах. Она значительно облегчает управление большими серверными кластерами, автоматизируя такие рутинные операции, как запуск, обновление и мониторинг приложений, тем самым гарантируя их стабильность и гибкость в разнообразных окружениях – от собственных серверов до облачных инфраструктур. Управление и оркестровка: Kubernetes обеспечивает координацию работы множества контейнеров и серверов (кластеров), обеспечивая непрерывную и продуктивную работу приложений.
* [K8S для начинающих. Первая часть](https://habr.com/ru/articles/589415/)
* [Как изучать Kubernetes джуну — и зачем](https://habr.com/ru/companies/kts/articles/708418/)
* [Контейнеризация понятным языком: хранение данных и безопасность в Kubernetes, зачем нужен Ansible](https://habr.com/ru/companies/slurm/articles/531704/)
* [Основы Kubernetes](https://kubernetes.io/ru/docs/tutorials/kubernetes-basics/)
* [Руководства](https://kubernetes.io/ru/docs/tutorials/)


1.2 Docker Swarm является встроенным решением для оркестрации контейнеров, предоставляемым Docker. 
Узлы (Nodes) — отдельные машины с установленным Docker Engine, входящие в состав кластера. 
Управляющие узлы (Manager Nodes) — отвечают за управление кластером, принимают решения и распределяют задачи. 
Рабочие узлы (Worker Nodes) — выполняют назначенные управляющими узлами задачи (контейнеры), но не участвуют в принятии решений. 
Балансировщик нагрузки — распределяет входящие запросы между рабочими узлами, поддерживая высокую доступность сервиса и его производительность. Docker Swarm подходит для автоматизации работы с контейнерами, обеспечивая удобство и надежность при управлении крупными инфраструктурами.
* [Общая концепция и диаграммы](https://gist.github.com/binakot/7b48361d5f611f68611b59a99230d1e3)
* [# Деплой в Docker Swarm - из gitlab на прод](https://habr.com/ru/articles/836850/)
* [Настройка и управление кластерами Docker Swarm](https://labex.io/ru/tutorials/docker-how-to-configure-and-manage-docker-swarm-clusters-411552)
* [Kubernetes vs Docker Swarm: что выбрать](https://msk.top-academy.ru/articles/kubernetes-vs-docker-swarm-chto-vybrat)


1.3. HashiCorp Nomad — это мощный и универсальный инструмент для оркестрации рабочих нагрузок, который значительно упрощает автоматизацию развертывания, масштабирование и управление различными типами приложений. Он поддерживает контейнерные, пакетные задачи, виртуальные машины и отдельные процессы, работая в разных средах, включая облачные платформы и локальную инфраструктуру. Nomad выделяется своей удобной функциональностью, высокой производительностью. Nomad способен обрабатывать широкий спектр рабочих нагрузок, таких как Docker-контейнеры, Java-приложения, гипервизоры, предоставляя универсальное решение для управления инфраструктурой. 
Nomad помогает организациям эффективно управлять инфраструктурой и облегчает работу даже с масштабными и сложными системами.
* [Возможно, вам не нужен Kubernetes](https://habr.com/ru/articles/445030/)
* [Крепкие сборки с планировщиками контейнеров, только без контейнеров](https://habr.com/ru/companies/timeweb/articles/709938/)
* [Альтернативный оркестратор nomad на десктопе](https://habr.com/ru/articles/440956/)
* [Nomad: проблемы и решения](https://habr.com/ru/articles/435132/)
* [Какие мнения о Hashicorp Nomad?](https://www.reddit.com/r/devops/comments/11nsxo3/opinions_on_hashicorp_nomad/?tl=ru)


## Мониторинг и Наблюдаемость / Monitoring & Observability (Metrics)
3. «Пульс» системы. Сбор числовых показателей (CPU, RAM, запросы) для оценки здоровья инфраструктуры в реальном времени.
 3.1. Сбор и хранение метрик (Time Series DB):
   3.1.1. Prometheus — это система мониторинга, предназначенная для сбора, хранения и обработки метрик, оптимизированная для работы с временными рядами данных. Она самостоятельно запрашивает данные у серверов и устройств, записывая их в собственную базу. Собранную информацию можно использовать для визуализации и глубокого анализа, адаптируя процесс под ваши конкретные задачи.
* [Полное руководство по Prometheus в 2019 году](https://habr.com/ru/companies/slurm/articles/455290/)
* [Человеческим языком про метрики 1: Потерянное введение](https://habr.com/ru/companies/tochka/articles/683608/)
* [«База» по метрикам в Prometheus](https://habr.com/ru/companies/sportmaster_lab/articles/872204/)
* [Основы мониторинга (обзор Prometheus и Grafana)](https://habr.com/ru/articles/709204/)
* [Prometheus: от основ до mem-saving оптимизации](https://habr.com/ru/companies/nixys/articles/785070/)
* [Мониторинг и алертинг приложений с помощью Prometheus и Grafana](https://www.youtube.com/watch?v=TKDsFYYOarc)
* [Prometheus: как Бог огня стал Богом мониторинга](https://habr.com/ru/companies/axenix/articles/842390/)
* [Zabbix vs Prometheus. Что выбрать для гетерогенной инфраструктуры?](https://habr.com/ru/articles/852394/)

 3.1.2. VictoriaMetrics представляет собой мощное open-source решение для мониторинга и анализа данных временных рядов, предлагая конкурентоспособную замену Prometheus. Система выделяется своей масштабируемостью, эффективным использованием дискового пространства и высокой скоростью обработки, что делает её идеальным инструментом для сбора, хранения и анализа метрик приложений и инфраструктуры в режиме реального времени.
* [Как снизить расходы на мониторинг: замена Prometheus на VictoriaMetrics](https://habr.com/ru/articles/850990/)
* [VictoriaMetrics, разделяй и агрегируй! Оптимизация хранения метрик](https://habr.com/ru/companies/t2/articles/922168/)
* [Очередной бенчмарк VictoriaMetrics против Prometheus](https://habr.com/ru/companies/cinimex/articles/943772/)
* [Тернистый путь к единому хранилищу метрик](https://habr.com/ru/companies/oleg-bunin/articles/851024/)
* [VictoriaMetrics и мониторинг приватных облаков. Павел Колобаев](https://prohoster.info/blog/administrirovanie/victoriametrics-i-monitoring-privatnyh-oblakov-pavel-kolobaev)
* 
 3.1.3. Zabbix представляет собой бесплатную систему мониторинга с открытым исходным кодом, разработанную для контроля состояния ИТ-инфраструктуры, включая серверы, сети, виртуальные машины, приложения и облачные сервисы. Она позволяет собирать данные, выявлять возникающие проблемы, отправлять уведомления пользователям и предоставлять средства для анализа и визуализации информации. Кроме того, Zabbix поддерживает разнообразные методы сбора данных, такие как использование агентов, проведение простых проверок и применение протокола SNMP.
* [Универсальная система мониторинга Zabbix — введение](https://habr.com/ru/articles/73338/comments/)
* [Zabbix: мониторим всё подряд (на примере Redis'а)](https://habr.com/ru/articles/485538/)
* [ТОП 6 фишек Zabbix: применение и настройка](https://habr.com/ru/companies/banki/articles/886306/)
* [Мониторинг пользовательских устройств с помощью Zabbix](https://habr.com/ru/companies/tbank/articles/736704/)
* [Установка и настройка Zabbix 5](https://selectel.ru/blog/zabbix-5-guide/)
* [Zabbix: Укрощение шторма алертов. От гистерезиса до Telegram и авто-ремедиации](https://habr.com/ru/articles/947884/)
* [Zabbix — автоматизация управления пользователями (JIT)](https://habr.com/ru/articles/970512/)
* [ТОП 6 фишек Zabbix: применение и настройка](https://habr.com/ru/companies/banki/articles/886306/comments/)
* [Использование мониторинга Zabbix в малом офисе с инфраструктурой на ОС Windows](https://habr.com/ru/articles/657105/)
* [Правильное обнаружение проблем с помощью Zabbix](https://habr.com/ru/companies/oleg-bunin/articles/320678/) 
* [Zabbix для DevOps: как мы внедряли систему мониторинга в процессы разработки и тестирования](https://habr.com/ru/companies/pt/articles/325276/)
* [Мониторинг PostgreSQL с использованием Zabbix](https://habr.com/ru/companies/zabbix/articles/515816/)
* 
 3.2. Визуализация и Оповещения (Dashboards & Alerting):
 3.2.1. Grafana представляет собой бесплатную платформу с открытым исходным кодом, предназначенную для визуализации данных. Она предоставляет пользователям возможность создавать интерактивные дашборды с графиками, диаграммами и уведомлениями, собирая информацию из различных источников, включая базы данных и системы мониторинга. Это веб-приложение широко используется для мониторинга ИТ-инфраструктуры, анализа данных, а также отображения метрик производительности и использования ресурсов в режиме реального времени.
* [Мониторинг с Grafana. Best practices](https://habr.com/ru/companies/karuna/articles/771134/)
* [Grafana — прошлое, настоящее, будущее и альтернативы](https://habr.com/ru/companies/mws/articles/812883/)
* [Основы мониторинга (обзор Prometheus и Grafana)](https://habr.com/ru/articles/709204/)
* [Enterprise мониторинг с нуля: Prometheus + Grafana для FastAPI приложения](https://habr.com/ru/articles/959430/)
* [Гайд по бизнес-метрикам в Grafana для аналитиков: бороться и искать, найти и не сдаваться](https://habr.com/ru/articles/904526/)
* [Grafana как еще один инструмент для технического мониторинга создаваемых нами программных продуктов](https://habr.com/ru/companies/slurm/articles/431122/)
* [Как мы выстроили систему визуализации ошибок с помощью Grafana и снизили время на их отработку с 2 часов до 15 секунд](https://habr.com/ru/articles/803527/)
* 
 3.2.2. Prometheus Alertmanager — превращает сухие цифры мониторинга в уведомления (Telegram, Slack, Email) при сбоях.
 3.2.3. Проверка доступности (Uptime Monitoring):
 3.2.4 Uptime Kuma — простой и эффективный инструмент для внешней проверки работы сайтов и API.


## Логирование / Logging (Events & Audit)
Система сбора, фильтрации и анализа текстовых событий. «Черный ящик» инфраструктуры для расследования инцидентов и аудита безопасности.
Готовые архитектурные решения (Stacks)
  * ELK Stack — Классический промышленный стандарт. [инфо](https://habr.com/ru/articles/538840/),[инфо](https://blog.skillfactory.ru/stek-elk-kak-rabotat-s-dannymi-prilozhenii/), [инфо](https://serveradmin.ru/ustanovka-i-nastroyka-elasticsearch-logstash-kibana-elk-stack/),[инфо](https://github.com/mekhanme/elk-mikrot), [инфо](https://habr.com/ru/companies/otus/articles/721004/))
  * EFK Stack — Стандарт для Kubernetes и Cloud Native сред. ([гайд ](https://arenda-server.cloud/blog/nastrojka-steka-logirovanija-elasticsearch-fluentd-i-kibana-efk-v-kubernetes/), [инфо](https://slurm.io/blog/tpost/0d06xiobme-logirovanie-v-kubernetes-kak-sobirat-hra), [инфо](https://habr.com/ru/companies/otus/articles/721004/), [инфо](https://ealebed.github.io/posts/2020/%D1%81%D0%B1%D0%BE%D1%80-%D0%B8-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D0%BB%D0%BE%D0%B3%D0%BE%D0%B2-kubernetes-%D0%BA%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80%D0%B0-%D1%81-%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E-efk/)   )
  * PLG Stack — Легковесный современный стек от Grafana Labs. [обзор](https://habr.com/ru/articles/800781/), [настройка](https://www.youtube.com/watch?v=2JIyHNskK-c), [инфо](https://habr.com/ru/articles/772702/), [инфо](https://habr.com/ru/companies/kts/articles/723980/), [инфо](https://habr.com/ru/articles/766102/)
  * Graylog — Полнофункциональная платформа управления логами «всё в одном». [инфо](https://winitpro.ru/index.php/2024/04/11/graylog-sbor-analiz-logov/), [инфо](https://habr.com/ru/companies/otus/articles/703882/)


Компоненты и инструменты (Pipeline)
1. Агенты сбора (Shippers / Agents)
   * Fluent Bit — Сверхлегкий сборщик для K8s и Edge. ([инфо](https://habr.com/ru/articles/548998/), [инфо](https://www.youtube.com/watch?v=WlGC0OUcxlQ)[гайд](https://hostingsrating.ru/articles/nastroika-fluent-bit-dlia-legkovesnoi-agregacii-logov))
   * Filebeat — Надежная доставка логов из файлов. ([инфо](https://habr.com/ru/articles/550352/), [инфо](https://www.reddit.com/r/elasticsearch/comments/xcqrq8/filebeat_v_logstash/?tl=ru))
   * Promtail — Агент для отправки логов в Loki. [инфо](https://itzm.tech/p/loki-in-docker/) [инфо](https://notes.kiriha.ru/soft/promtail/)
2. Агрегация и маршрутизация (Aggregators)
   * Vector — Высокопроизводительный Rust-инструмент. [инфо](https://beget.com/ru/kb/how-to/vps/vector-servis-sbora-logov), [инфо](https://clickhouse.com:2053/docs/ru/use-cases/observability/clickstack/ingesting-data/vector), (инфо)[https://docs.selectel.ru/logs/tools/vector]
   * Fluentd — Гибкий стандарт с огромным выбором плагинов. ([гайд](https://cloud.vk.com/docs/cases/cases-logs/case-fluentd))
   * Logstash — Мощный инструмент трансформации данных. [инфо](https://habr.com/ru/companies/m2tech/articles/660909/), [инфо](https://habr.com/ru/articles/451264/), [инфо](https://habr.com/ru/articles/451264/), [инфо](https://habr.com/ru/articles/165059/)
3. Хранение и Поиск (Storage & Search Engines)
   * Elasticsearch — Полнотекстовый поиск по Big Data. [инфо](https://habr.com/ru/articles/489924/), [инфо]https://habr.com/ru/articles/165059/()
   * Grafana Loki — Экономное хранилище, оптимизированное под Grafana. [инфо](https://habr.com/ru/companies/kts/articles/723980/), [инфо](https://habr.com/ru/articles/800781/)
   * 
4. Визуализация и интерфейс (UI / Dashboards)
   * Kibana — Глубокий анализ данных Elasticsearch. [инфо](https://www.simbirsoft.com/blog/kibana-chto-eto-osnovnye-vozmozhnosti-i-preimushchestva-primeneniya/), [инфо](https://habr.com/ru/companies/citymobil/articles/521802/)
   * Grafana — Единая панель для логов и метрик. [инфо](https://habr.com/ru/companies/karuna/articles/771134/), [инфо](https://habr.com/ru/companies/karuna/articles/771134/)




## Система управления конфигурациями
5. Система управления конфигурациями – это набор инструментов и практик для автоматизации и централизованного управления состоянием инфраструктуры, приложений и данных с помощью «инфраструктуры как кода».

5.1 Chef в контексте DevOps — это мощный инструмент управления конфигурацией, который позволяет командам автоматизировать процессы развертывания, настройки и управления инфраструктурой как кодом. Chef использует Ruby в качестве языка для написания "рецептов", которые описывают желаемое состояние серверов и других ресурсов.
* [Chef для новичков](https://habr.com/ru/companies/slurm/articles/208858/)
* [Управление конфигурациями: Puppet vs. Chef vs. Ansible](https://habr.com/ru/companies/otus/articles/774150/)
* [Chef для решения повседневных задач](https://habr.com/ru/articles/263341/)
* [Chef за 21 день. Часть первая. Введение](https://habr.com/ru/companies/epam_systems/articles/208542/)
* [Настраиваем сервер с Chef (Быстро и просто)](https://habr.com/ru/companies/staply/articles/244111/)
* [Chef или как управлять тысячей серверов](https://habr.com/ru/articles/87302/)



5.2 Puppet — это инструмент и платформа автоматизации, используемый в практике DevOps для управления конфигурацией и оркестровки серверов. В рамках DevOps, Puppet помогает командам разработчиков и системных администраторов автоматически настраивать, развертывать и управлять инфраструктурой, обеспечивая ее стабильное состояние и соответствие заданным параметрам.
* [Введение в Puppet](https://habr.com/ru/companies/avito/articles/507346/)
* [CI/CD-инфраструктура на базе Puppet и GitLab для управления флотом из 9000 хостов](https://habr.com/ru/companies/sportmaster_lab/articles/965238/)
* [Как стать кукловодом или Puppet для начинающих](https://habr.com/ru/articles/163811/)
* [Puppet в Avito: 15 000 серверов, CI/CD и уроки из продакшна](https://habr.com/ru/companies/avito/articles/939080/)
* [Puppet+Hiera. Выжимаем максимум](https://habr.com/ru/companies/semrush/articles/412587/)
* [С Puppet на Ansible за 4 года: 5 инсайтов и письмо себе в прошлое](https://habr.com/ru/companies/banki/articles/951808/)
* [Puppet, система управления конфигурациями. Часть I](https://habr.com/ru/articles/67471/)
* [Puppet, система управления конфигурациями. Часть II](https://habr.com/ru/articles/68532/)
* [2.9.14.4 Puppet - централизованное управление конфигурацией ОС и ПО](https://redos.red-soft.ru/base/redos-7_3/7_3-administation/7_3-remote-admin/7_3-puppet/)



5.3 Ansible — это система с открытым исходным кодом для автоматизации ИТ-процессов, которая позволяет управлять конфигурациями серверов, развертывать приложения и оркестровать сложные рабочие процессы. Вместо ручного выполнения команд на каждом сервере, Ansible позволяет описывать желаемое состояние инфраструктуры в виде кода и автоматически применять его на множестве машин.
* [2.9.14.3 Ansible - система автоматизации настройки и развертывания ПО](https://redos.red-soft.ru/base/redos-7_3/7_3-administation/7_3-remote-admin/7_3-ansible/)
* [Ansible для людей: автоматизировал и выдохнул](https://habr.com/ru/articles/920742/)
* [Ansible для начинающих](https://habr.com/ru/companies/slurm/articles/714000/)
* [Автоматизируйте всё с помощью Ansible](https://habr.com/ru/companies/slurm/articles/738594/)
* [Ansible для начинающих: инструкции и команды](https://practicum.yandex.ru/blog/ansible-sistema-upravleniya-serverami/)
* [Прокачаться в работе с Ansible — подборка ресурсов](https://habr.com/ru/companies/vasexperts/articles/920670/)
* [Архитектура приложения. Разбираем приложение Ansible на модули (A-services)](https://habr.com/ru/companies/pt/articles/954104/)
* [44 совета по Ansible: рекомендации и Best Practices](https://habr.com/ru/companies/slurm/articles/725788/)



5.4 Ansible Molecule — это фреймворк для разработки и тестирования ролей и других компонентов Ansible, который помогает создавать надежный и качественный код для автоматизации инфраструктуры. Он позволяет создавать изолированные тестовые среды в различных операционных системах, контейнерах или облачных платформах, чтобы проверить работоспособность ролей Ansible в разных сценариях и убедиться в их правильной работе и идемпотентности.
* [Тестирование автоматизации Ansible с помощью Molecule Часть 1](https://habr.com/ru/companies/slurm/articles/711432/)
* [Тестирование автоматизации Ansible с помощью Molecule Часть 2](https://habr.com/ru/companies/slurm/articles/713060/) 
* [Molecule — тестируем роли Ansible](https://habr.com/ru/articles/437216/)
* [Тестирование Ansible с использованием Molecule с Ansible в качестве верификатора](https://habr.com/ru/articles/527454/)



5.5 HashiCorp Vagrant — это инструмент с открытым исходным кодом от HashiCorp, предназначенный для создания и управления виртуальными средами разработки. Vagrant позволяет разработчикам быстро создавать и настраивать одинаковые рабочие окружения, что решает проблему «у меня на машине работает», и делает рабочую среду более предсказуемой и соответствующей производственной.
* [Что такое Vagrant: установка, запуск, использование}(https://ru.hexlet.io/blog/posts/vagrant)
* [Знакомимся с Otto, наследником Vagrant](https://habr.com/ru/articles/268497/)
* [Does anyone use HashiCorp Vagrant anymore?](https://www.reddit.com/r/devops/comments/p0icih/does_anyone_use_hashicorp_vagrant_anymore/)


5.6 Terraform — это инструмент с открытым исходным кодом для автоматизации управления инфраструктурой в виде кода (IaC), позволяющий описывать и развертывать облачные и локальные ресурсы с помощью конфигурационных файлов на декларативном языке HCL (HashiCorp Configuration Language).
* [Основы Terraform](https://habr.com/ru/companies/otus/articles/696694/)
* [Terraform: от незнания к best practices](https://habr.com/ru/companies/nixys/articles/721404/)
* [Terraform: поиск оптимального написания кода](https://habr.com/ru/articles/817839/)
* [Три юзкейса Terraform, к реализации которых вам пора приступать](https://habr.com/ru/companies/timeweb/articles/825454/)
* [DevOps Tutorials — Terraform: создаем виртуальный сервер в облаке](https://habr.com/ru/articles/937376/)
* [Теория: Обзор Terraform](https://ru.hexlet.io/courses/terraform-basics/lessons/overview/theory_unit)
* [Начало работы с Terraform](https://yandex.cloud/ru/docs/tutorials/infrastructure-management/terraform-quickstart)
* [Terraform: как установить, настроить и использовать инструмент](https://practicum.yandex.ru/blog/nastroyka-i-ispolzovanie-terraform/)



5.7  CDK8s — это фреймворк с открытым исходным кодом для генерации ресурсов Kubernetes. Основная идея cdk8s заключается в том, что с ним вместо Helm-шаблонов для управления ресурсами и приложениями в Kubernetes можно использовать привычные языки разработки: TypeScript, JavaScript, Python и Java.
* [Обзор фреймворка cdk8s для «программирования» Kubernetes-манифестов](https://habr.com/ru/companies/flant/articles/577624/)
* [Напишите свою инфраструктуру Kubernetes — как код Go](https://habr.com/ru/companies/ruvds/articles/680664/)


5.8 Crossplane — это фреймворк с открытым исходным кодом для платформенной разработки на базе Kubernetes, который позволяет управлять облачной инфраструктурой (например, базами данных, кластерами и другими ресурсами) через стандартный Kubernetes API. Он работает по принципу «Infrastructure as Code» (инфраструктура как код), постоянно синхронизируя состояние облачных ресурсов с запрошенными конфигурациями, что обеспечивает высокую доступность и упрощает развертывание и управление инфраструктурой в мультиоблачных средах.
* [Crossplane. Где встречаются Kubernetes и облака](https://habr.com/ru/companies/otus/articles/676082/)
* [Преимущества Crossplane в 2025 году?](https://www.reddit.com/r/devops/comments/1ilmkrt/crossplane_selling_points_in_2025/?tl=ru)
* [Установка Crossplane с поддержкой Yandex Cloud](https://yandex.cloud/ru/docs/managed-kubernetes/operations/applications/crossplane)
* {Как управлять инфраструктурой в GitOps с помощью Crossplane](https://habr.com/ru/companies/kts/articles/726026/)
* [Как зарабатывать больше, если знаешь Crossplane?](https://slurm.io/blog/tpost/yrki000z41-kak-zarabativat-bolshe-esli-znaesh-cross)




5.9 Pulumi — это платформа "инфраструктура как код" (IaC) с открытым исходным кодом, которая позволяет управлять облачной инфраструктурой с помощью привычных языков программирования, таких как Python, TypeScript, Go и C#.
* [Универсальное описание инфраструктуры на Pulumi. Раскатываемся в Kubernetes, AWS, GCP с одной конфигурацией](https://habr.com/ru/companies/otus/articles/674818/)
* [Terraform уже не тот? Как Pulumi меняет правила игры в Infrastructure as Code](https://habr.com/ru/companies/okko/articles/908960/)
* [Как зарабатывать больше, если знаешь Pulumi?](https://slurm.io/blog/tpost/nre0cpbxe1-kak-zarabativat-bolshe-esli-znaesh-pulum)
* [Pulumi. Описание инфраструктуры языком программирования // занятие курса «Infrastructure as a code»](https://www.youtube.com/watch?v=6MXauTFoUhQ)

## Хранение секретов и ключей / Secret Management
Часть концепции Total Control: исключение человеческого фактора и «открытых» данных. Инструменты для автоматизированной передачи учетных данных внутри инфраструктуры, исключающие утечки в коде и конфигурациях.
* HashiCorp Vault — промышленный стандарт для динамических секретов и шифрования.
* sops (Secrets Operations) — шифрование файлов (YAML, JSON, ENV) для безопасного хранения в Git.
* Sealed Secrets — специфическое решение для Kubernetes.
* Cloud Secret Managers (AWS, Azure, Google) — нативные облачные хранилища.

## Управление привилегированным доступом / Privileged Access Management (PAM)
Часть концепции Total Control: полный аудит и иерархия доступа. Инструменты для контроля действий администраторов, записи сессий и реализации принципа «нулевого доверия» (Zero Trust) при доступе к серверам и базам данных.
* Teleport — современная замена SSH/RDP с записью сессий и доступом через SSO.
* Apache Guacamole — клиентский доступ к рабочим столам через браузер (без прямого SSH-соединения).
* HashiCorp Boundary — гранулярный доступ к ресурсам на основе личности, а не сетевых адресов.
* FreeIPA / Keycloak — централизованное управление цифровыми личностями и правами.


 ## Управление идентификацией и доступом / Identity and Access Management (IAM)
Часть концепции Total Control: управление цифровыми личностями и правами доступа. Единая точка входа (SSO) и централизованная база пользователей для всех сервисов инфраструктуры.

* Keycloak — «золотой стандарт» для энтерпрайза. Позволяет настроить SSO (Single Sign-On), поддерживает протоколы OpenID Connect, SAML и OAuth 2.0. Идеален для глубокой интеграции с корпоративными системами.
 
* Authentik — современная и более легкая альтернатива Keycloak. Очень популярен в DevOps-среде за счет простоты деплоя через Docker и встроенного функционала управления доступом к приложениям (Outpost).
 
* Zitadel — облачно-ориентированное решение на Go. Отличается отличной поддержкой мультитенантности (когда нужно изолировать разные группы пользователей или клиентов внутри одной системы).
 
* FreeIPA — «Active Directory для Linux». Если тебе нужно управлять не просто входом в веб-приложения, а правами пользователей на тысячах Linux-серверов, SSH-ключами и политиками sudo — это твой выбор.
 
* LLDAP (Lightweight LDAP) — если FreeIPA кажется слишком громоздким. Это максимально упрощенный и быстрый LDAP-сервер для маленьких команд, где нужно просто хранить список пользователей и их пароли.
 
* Authelia — минималистичный «шлюз» аутентификации. Идеально подходит, если нужно быстро добавить 2FA (двухфакторную проверку) перед простыми веб-сервисами, которые сами этого не умеют. 



## Базы данных 
6. База данных (БД) — это упорядоченное электронное хранилище информации, позволяющее быстро и безопасно собирать, хранить, управлять и анализировать большие объемы данных. Системы управления базами данных (СУБД) — это программы, которые используются для работы с базами данных, а для извлечения информации применяются языки запросов, например, SQL.

6.1. ClickHouse — это высокопроизводительная столбцовая система управления базами данных (СУБД) с открытым исходным кодом, предназначенная для онлайн-аналитической обработки (OLAP) больших данных в режиме реального времени. Изначально разработанная компанией Яндекс для анализа данных Яндекс.Метрики, она стала популярным инструментом для веб-аналитики, маркетинговых отчетов, обработки логов и других задач, требующих быстрого анализа больших объемов информации
* [ClickHouse: Передовой инструмент для оперативной обработки данных](https://habr.com/ru/companies/otus/articles/773174/)
* [Погружение в ClickHouse: делаем первые и успешные шаги](https://habr.com/ru/articles/901018/)
* [Как я вкатывался в Clickhouse](https://habr.com/ru/articles/982130/)
* [Дом, милый дом: нюансы работы с ClickHouse. Часть 1](https://habr.com/ru/companies/nixys/articles/801029/)
* [Дом, милый дом: нюансы работы с ClickHouse. Часть 2, репликация](https://habr.com/ru/companies/nixys/articles/826850/)
* [Инфраструктура для Data-Engineer ClickHouse](https://habr.com/ru/articles/842818/)
* [ClickHouse как DWH: Производительность без боли и ловушки merge-таблиц](https://habr.com/ru/articles/912454/)



   
6.2 PostgreSQL — это бесплатная объектно-реляционная система управления базами данных (РСУБД) с открытым исходным кодом, известная своей надежностью, гибкостью и производительностью. Она поддерживает стандарт SQL, позволяя создавать и управлять данными в виде таблиц, но также включает объектно-ориентированные возможности, такие как пользовательские типы данных и наследование.
* [PostgreSQL: лучшие статьи на Хабр](https://otus.ru/journal/postgresql-luchshie-stati-na-habr/)
* [Как мы сократили объем данных в 10 раз, не повредив пользовательскому опыту, или переезд Postgres → ClickHouse](https://habr.com/ru/companies/kts/articles/988510/)   


6.3 MongoDB — это нереляционная (NoSQL) документоориентированная база данных с открытым исходным кодом, которая хранит данные в виде гибких JSON-подобных документов вместо таблиц и строк, как в реляционных базах данных. Это обеспечивает гибкость схемы данных, высокую производительность, масштабируемость и простоту работы с разнородной информацией, что делает ее популярной для веб-приложений, аналитики больших данных и мобильных приложений. 
* [Готовимся к собеседованию: 82 вопроса по MongoDB](https://habr.com/ru/companies/otus/articles/768342/)
* [Подумываете об использовании MongoDB?](https://habr.com/ru/companies/otus/articles/565700/)
* [Топ-5 инструментов для MongoDB в 2022 году](https://habr.com/ru/companies/otus/articles/666188/)
* [MongoDB vs PostgreSQL. Сравнение документо-ориентированной и реляционной базы данных](https://habr.com/ru/companies/amvera/articles/757534/)
* [Работа с MongoDB: читаем на Хабр](https://otus.ru/journal/rabota-s-mongodb-chitaem-na-habr/)



## Брокер сообщений
7. Брокер сообщений — это программный посредник, который принимает сообщения от приложений-отправителей, сохраняет их и затем передаёт приложениям-получателям, обеспечивая асинхронное и надёжное взаимодействие между ними. Он разгружает сервисы от необходимости знать о местонахождении друг друга, позволяет обрабатывать сообщения в удобное время и поддерживает отказоустойчивость системы за счёт буферизации и гарантированной доставки.
* [Брокеры сообщений, или Как происходит взаимодействие в рамках распределённой инфраструктуры](https://habr.com/ru/companies/sberbank/articles/669456/)
* [Брокеры сообщений и их использование в микросервисной архитектуре](https://habr.com/ru/sandbox/251358/)
* [Практическое руководство по выбору брокера сообщений](https://habr.com/ru/companies/otus/articles/901708/)
* [Брокер сообщений своими руками](https://habr.com/ru/articles/903302/)

 
7.1 RabbitMQ — это посредник для обмена данными между приложениями. Этот протокол включает издателей, получателей, очереди, обменники и ключи маршрутизации. RabbitMQ важен для создания распределенных систем, таких как микросервисы.
* [RabbitMQ: что это такое и как работает](https://blog.skillfactory.ru/rabbitmq-chto-eto-takoe-i-kak-rabotaet/)
* [Лучшие практики для надёжной работы с RabbitMQ](https://habr.com/ru/companies/tochka/articles/799949/)
* [Что такое RabbitMQ? Топология, объекты и атрибуты](https://systems.education/what-is-rabbitmq)
* [Когда и зачем нужен RabbitMQ](https://habr.com/ru/companies/slurm/articles/684412/)
* [RabbitMQ: терминология и базовые сущности](https://habr.com/ru/companies/slurm/articles/703060/)



7.2 Apache Kafka — это брокер сообщений, с открытым исходным кодом, предназначенная для работы с большими объемами данных в режиме реального времени. Она позволяет приложениям надежно и эффективно обмениваться данными, обрабатывая их по мере генерации, и имеет высокую производительность, масштабируемость и отказоустойчивость.
* [Kafka для начинающих: откуда такой спрос и зачем нужна эта технология](https://habr.com/ru/articles/957824/)
* [Изучаем Kafka — Уровень 1](https://habr.com/ru/articles/916726/)
* [Kafka за 20 минут. Ментальная модель и как с ней работать](https://habr.com/ru/companies/kuper/articles/738634/)
* [Apache Kafka: основы технологии](https://habr.com/ru/companies/slurm/articles/550934/)
* [Kafka для начинающих: работа с оффсетами на практике](https://habr.com/ru/articles/965218/)
* [Лучший Гайд по Kafka для Начинающих За 1 Час](https://www.youtube.com/watch?v=hbseyn-CfXY)





## Облачные вычисления
8. Облачные вычисления — это модель предоставления вычислительных ресурсов (серверов, хранилищ, программного обеспечения, сетей, аналитики и др.) по требованию через Интернет («облако»), позволяющая компаниям и частным пользователям использовать эти сервисы по подписке вместо владения и обслуживания собственной физической ИТ-инфраструктуры.

8.1 Amazon Web Services (AWS)
* [Базовая инфраструктура в облаках на примере AWS // Курс «Cloud Solution Architecture»](https://www.youtube.com/watch?v=hNKskKNWNKQ)



8.2 Microsoft Azure
* [Azure понятным языком [Шпаргалка]](https://habr.com/ru/companies/microsoft/articles/320544/)


8.3 Google Cloud Platform (GCP)
* [GCP: Разбор вычислительного стека Google Cloud Platform](https://habr.com/ru/companies/otus/articles/467749/)



## Система управления версиями
9. Система управления версиями (СУВ или VCS) — это программное обеспечение, которое отслеживает и управляет изменениями в файлах проекта с течением времени, позволяя сохранять разные версии документов, откатываться к предыдущим состояниям, а также работать совместно над проектом.

9.1 Git — это распределённая система управления версиями, инструмент для отслеживания изменений в файлах и совместной работы над проектами, особенно в разработке программного обеспечения. Он позволяет разработчикам сохранять историю всех версий проекта, возвращаться к предыдущим состояниям, а также координировать свои усилия, избегая конфликтов и обеспечивая эффективное управление рабочим процессом
* [Git для новичков (часть 1)](https://habr.com/ru/articles/541258/) 
* [Git для новичков (часть 2)](https://habr.com/ru/articles/542616/)
* [Гид по Git — глазами бывшего джуна](https://habr.com/ru/companies/surfstudio/articles/973304/)
* [15 команд Git, которые покрывают 90% повседневной работы разработчика](https://habr.com/ru/articles/905658/)
* [Что такое Git и почему он стал стандартом разработки](https://habr.com/ru/articles/959760/)
* [Git. Коротко о главном](https://habr.com/ru/articles/588801/)


   
9.2 Bitbucket — это облачный сервис хостинга кода, разработанный компанией Atlassian, который позволяет командам разработчиков хранить, управлять и совместно работать над проектами, используя систему контроля версий Git. Он предлагает централизованное пространство для размещения репозиториев, отслеживания изменений в коде и интеграции с другими инструментами, такими как Jira и Trello, что делает его популярным решением для профессиональных команд.
* [Bitbucket: что это, особенности, сравнение с GitLab](https://itglobal.com/ru-ru/company/glossary/bitbucket/)
* [Bitbucket: Создание приватного репозитория](https://habr.com/ru/sandbox/37865/)
* [6 секретов Bitbucket](https://habr.com/ru/articles/278547/)
* [Bitbucket](https://blog.skillfactory.ru/glossary/bitbucket/)


## Резервное копированиие
10. Резервное копирование, или бэкап, — это создание копий важных данных (файлов, папок, систем, приложений) и хранение их отдельно от оригинала, на других носителях (локальных дисках, внешних накопителях, в облаке).
1. UrBackup
* [Резервное копирование, часть по просьбам читателей: Обзор UrBackup, BackupPC, AMANDA](https://habr.com/ru/companies/slurm/articles/468963/)
* [Быстрая настройка резервного копирования под Linux и не только (UrBackup)](https://habr.com/ru/articles/262499/)
* [UrBackup: Надежное решение для резервного копирования и восстановления данных](https://mivocloud.com/ru/blog/UrBackup-Nadezhnoe-reshenie-dlya-rezervnogo-kopirovaniya-i-vosstanovleniya-dannykh)
* 
2. Amanda 
* [Advanced Maryland Automatic Network Disk Archiver](https://ru.wikipedia.org/wiki/Advanced_Maryland_Automatic_Network_Disk_Archiver)
* [Какова в действии система резервирования AMANDA](https://samag.ru/archive/article/1704)


3. Duplicati
4. Bacula 
5. Borg 
6. kopia
7. Restic

## Языки программирования 
11. Язык программирования — это формальная знаковая система, предназначенная для написания инструкций (компьютерных программ), которые выполняет ЭВМ. Он служит мостом между человеком и машиной, определяя строгий синтаксис (правила написания) и семантику (смысл команд) для создания алгоритмов. 



11.1 Язык Си (C) — это процедурный язык программирования общего назначения, разработанный Деннисом Ритчи в начале 1970-х годов. Он компилируемый, статически типизированный, отличается эффективностью, гибкостью и низкоуровневым доступом к памяти. Си широко используется для системного программирования, драйверов и встроенных систем.   
* [Язык программирования C. Твой путь начинается здесь, самурай](https://habr.com/ru/articles/928410/)
* [Справочник по языку C](https://learn.microsoft.com/ru-ru/cpp/c-language/c-language-reference?view=msvc-170)
* [Руководство по языку программирования Си](https://metanit.com/c/tutorial/)



11.2 C++ — это компилируемый, статически типизированный язык программирования общего назначения, разработанный как расширение языка Си (C) с поддержкой объектно-ориентированного программирования (ООП), обобщенного программирования и управления памятью. Он сочетает высокоуровневые абстракции с низкоуровневым доступом к ресурсам, обеспечивая высокую производительность. 
* [Справочник по языку C++](https://learn.microsoft.com/ru-ru/cpp/cpp/cpp-language-reference?view=msvc-170)
* [Руководство по языку программирования C++](https://metanit.com/cpp/tutorial/)
* [C++: описание языка и его основы](https://otus.ru/journal/c-opisanie-yazyka-i-ego-osnovy/)
* [Уроки С++](https://ravesli.com/uroki-cpp/)



11.3 Java — это широко распространенный, объектно-ориентированный язык программирования высокого уровня, созданный Sun Microsystems в 1995 году (сейчас принадлежит Oracle). Его ключевая особенность — платформанезависимость: код компилируется в байт-код и запускается на любой ОС через виртуальную машину Java (JVM) по принципу «Напиши один раз, запускай везде» (Write Once, Run Anywhere). 
* [Руководство по языку программирования Java](https://metanit.com/java/tutorial/)
* [Всё, что нужно знать новичку о Java](https://practicum.yandex.ru/blog/chto-takoe-java-dlya-nachinayuschih/)
* [Java: описание, особенности и области использования](https://otus.ru/journal/java-opisanie-osobennosti-i-oblasti-ispolzovaniya/) 
* [Язык программирования Java: что нужно знать новичку](https://ru.hexlet.io/blog/posts/yazyk-programmirovaniya-java-osobennosti-populyarnost-situatsiya-na-rynke-truda)
* [10 главных конструкций языка Java](https://thecode.media/10-java/)
* [10 лучших Java-фреймворков](https://scand.com/ru/company/blog/top-java-frameworks/)



11.4 JavaScript (JS) — это высокоуровневый, интерпретируемый язык программирования, являющийся одной из трех базовых технологий веб-разработки (наряду с HTML и CSS). Он используется для создания интерактивных, динамических веб-страниц, обработки действий пользователя (клики, анимации) и работы на стороне сервера (Node.js). 
* [JavaScript для начинающих. Урок 1](https://habr.com/ru/sandbox/170986/)
* [JavaScript Frameworks: описание и особенности](https://otus.ru/journal/javascript-frameworks-opisanie-i-osobennosti/)
* [JavaScript-фреймворки и библиотеки, на которые стоит обратить внимание в 2025 году](https://habr.com/ru/companies/ru_mts/articles/864500/)
* [Лонгрид о JavaScript](https://habr.com/ru/articles/803137/)
* [JavaScript повсюду или почему веб-технологии захватили мир](https://habr.com/ru/articles/756064/)
* [Современный учебник JavaScript](https://learn.javascript.ru/)

11.5 TypeScript
* [Чистый код на TypeScript: практические советы](https://habr.com/ru/articles/948488/)
* [Изучение TypeScript — Полное руководство для начинающих. Часть 1 — Введение и примитивные типы данных](https://habr.com/ru/articles/663964/))

11.6 Python — высокоуровневый язык программирования общего назначения, созданный Гвидо ван Россумом в 1991 году. Он отличается простым, читаемым синтаксисом, использованием отступов для структуры кода и универсальностью. Python активно используется в веб-разработке (Django), анализе данных, машинном обучении, автоматизации (скриптах) и ИИ. 
* [Что же такое Django?](https://habr.com/ru/articles/747234/)
* [Что бы я хотел знать когда начинал изучать Django? — очень общий взгляд](https://habr.com/ru/articles/508100/)
* [Быстрый Django: всё, что нужно знать о производительности](https://habr.com/ru/articles/942296/)
* [Почему я рекомендую Ruby on Rails новичкам в 2024 году?](https://habr.com/ru/articles/794476/)
* [Ruby on Rails шаг за шагом. #1 Теория](https://habr.com/ru/articles/49700/)
* [Курс по Ruby+Rails. Часть 1. Императивное программирование](https://habr.com/ru/companies/evrone/articles/689076/)
* [Знакомство с FastAPI](https://habr.com/ru/articles/488468/)
* [FastAPI: Хватит писать всё в main.py. Гайд по нормальной структуре для новичков](https://habr.com/ru/articles/970798/)
* [FastAPI: 5 практичных архитектурных решений, о которых я пожалел, что не узнал раньше](https://habr-articles.rssing.com/chan-76549191/article37998.html)
* [Плюсы и минусы FastAPI в 2023](https://habr.com/ru/articles/748552/)
* [Разработка на Python: ТОП-9 статей на Хабр](https://otus.ru/journal/razrabotka-na-python-top-9-statej-na-habr/)
* [Как я в 35 пытался стать Python-разработчиком, и почему у меня [пока] ничего не вышло](https://habr.com/ru/articles/832186/)
* [Сказ о Python или почему его лучше не выбирать новичкам](https://habr.com/ru/articles/808195/)
* [Основы языка программирования Python за 10 минут](https://habr.com/ru/articles/709102/)


1.6. IP-телефония (VoIP) — это современная технология передачи голосовых и видеосообщений через интернет-протокол (IP), заменяющая традиционные аналоговые линии.
    * [IP-телефония. Виды VoIP устройств, обзор плюсов-минусов. Что выбрать?](https://habr.com/ru/articles/493528/)
    * [Основы IP-телефонии, базовые принципы, термины и протоколы](https://habr.com/ru/articles/183152/)
    * [Основы IP-телефонии, базовые принципы, термины и протоколы](https://habr.com/ru/articles/183152/)
    * [Что такое IP-телефония и как она работает](https://thecode.media/ip-telephony/)
    * [IP-телефония: что это и как работает](https://selectel.ru/blog/ip-telephony/)
    * [Базовые принципы IP - телефония](https://wiki.merionet.ru/articles/ip-telephony)
    * [Как устроена IP-телефония: объясняем на пальцах](https://www.youtube.com/watch?v=nMeSkBlH3Ek)
    * [Что такое IP Телефония // Проводные телефоны возвращаются?](https://www.youtube.com/watch?v=hYKynt1i_eE)
    * [Сравнение программ для IP-телефонии](https://ru.wikipedia.org/wiki/Сравнение_программ_для_IP-телефонии)


     -  1.6.1. Asterisk (Астериск) — это популярная программная АТС с открытым исходным кодом, предназначенная для создания систем IP-телефонии (VoIP) на базе ОС Linux, BSD и других. Она превращает обычный компьютер в мощную телефонную станцию с поддержкой IVR, голосовой почты, конференций и записи звонков.
    - [Asterisk](https://ru.wikipedia.org/wiki/Asterisk)
    - [База знаний](http://www.asterisk.ru/knowledgebase/books)
    - [«Астериск - будущее телефонии».](http://www.asterisk.ru/store/files/Asterisk_-_Definitive_guide_4th.pdf)
    - [Asterisk: Полное руководство, 5 издание](https://denis.elib.ru/wp-content/uploads/2021/01/Asterisk-The-Definitive-Guide.pdf)
    - [Asterisk - настройка с нуля](https://wiki.merionet.ru/articles/asterisk-nastrojka-s-nulya)
    - [Asterisk Managment Interface (AMI), Часть 1](https://habr.com/ru/articles/64105/)
    1.6.2. FreePBX — это популярный веб-интерфейс (GUI) с открытым исходным кодом для управления IP-АТС Asterisk. Он позволяет настраивать телефонные системы, маршрутизацию звонков, IVR (голосовое меню) и SIP-аккаунты через браузер, исключая необходимость правки конфигурационных файлов вручную. Часто поставляется в составе FreePBX Distro (ОС+Asterisk+GUI). 
    - [r/freepbx](https://www.reddit.com/r/freepbx/)
    - [Руководство администратора FreePBX на русском языке](https://wiki.merionet.ru/articles/rukovodstvo-administratora-freepbx-na-russkom-yazyke)
    - [FreePBX: первые шаги по граблям](https://habr.com/ru/companies/slurm/articles/313078/)
    - [Простая установка Asterisk + FreePBX для начинающих](https://habr.com/ru/articles/171163/)
    - [Raspberry Pi + FreePBX(asterisk) + Mikrotik = АТС мини](https://habr.com/ru/articles/550734/)
    - [Сложности установки сервера IP-телефонии FreePBX на неттоп с процессором AMD](https://habr.com/ru/articles/593519/)
    - [Разбираемся с FreePBX и интегрируем его с Битрикс24 и не только](https://habr.com/ru/articles/518450/)     
    - [Аналоги FreePBX: 11 похожих сервисов для замены](https://exolve.ru/blog/analogues-freepbx-11-services-to-replace/)
    
    1.6.3 Issabel PBX — это бесплатная коммуникационная платформа с открытым исходным кодом на базе Asterisk, предназначенная для создания IP-АТС, VoIP-серверов и контакт-центров. Она объединяет телефонию, факс, чат и CRM-интеграцию в одном веб-интерфейсе, предоставляя функции IVR, очередей, записи звонков и видеоконференций. 
    - [Issabel PBX - установка платформы](https://wiki.merionet.ru/articles/issabel-pbx-ustanovka-platformy)
    - [Возможности сетевых настроек в дистрибутиве IssabelPBX.](https://voxlink.ru/kb/legacy-pbx-integration/vozmozhnosti-setevyh-nastroek-v-distributive-issabelpbx/)
    - [Внедрение IP телефонии на базе Issabel. Часть 1](https://www.youtube.com/watch?v=8mqrVAe27eM)
    - [Использование встроенной безопасности IssabelPBX](https://voxlink.ru/kb/integraciya-s-crm/ispolzovanie-vstroennoj-bezopasnosti-issabelpbx/)

    1.6.4 VitalPBX — это современная, функциональная IP-АТС на базе Asterisk, предназначенная для создания корпоративных систем связи. Она сочетает возможности Open Source-решений с удобным графическим интерфейсом, обеспечивая работу IVR, запись разговоров, видеозвонки и другие функции, что делает её гибкой платформой для бизнеса. 
    - [Базовый обзор VitalPbx](https://voxlink.ru/kb/asterisk-installation/bazovyi-obzor-vitalpbx)
    - [VitalPBX tips & tricks](https://voxlink.ru/kb/asterisk-installation/vitalpbx-tips-tricks/)

    1.6.5 Incredible PBX — это мощная, безопасная и бесплатная IP-АТС на базе открытого исходного кода Asterisk и FreePBX, предназначенная для создания корпоративных телефонных сетей. Она объединяет функции VoIP, включая облачную интеграцию (Google Voice), повышенную защиту и удобный веб-интерфейс. 
    - [«Невероятная АТС» для RasPBX](https://www.rlocman.ru/news/new.html?di=150832&srsltid=AfmBOor1l9gyi8SiAHi32X5dJC7vKvm0-judCmxE-VU1jnjeGPMXFEuR) 
    - [Incredible PBX Wiki | HomePage](https://wiki.incrediblepbx.com/HomePage) 




