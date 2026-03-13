# 🗺️ Оглавление / Table of Contents

### 🏗️ Фундамент и Инфраструктура
- [1. Лицензирование и Свобода (LFS)](#1-типы-лицензий-и-правовой-статус-по--license-types-and-legal-status-lfs)
- [2. Операционные системы (OS)](#2-операционные-системы--operating-systems-os)
- [3. Изоляция и виртуализация (Compute)](#3-изоляция-и-виртуализация--virtualization-and-core-isolation-compute)
- [4. Контейнеризация и среды исполнения (Containers)](#4-контейнеризация-и-среды-исполнения--containerization-and-runtimes-containers)
- [5. Оркестрация кластеров и GitOps (OCM)](#5-оркестрация-кластеров-и-gitops--cluster-orchestration-and-gitops-ocm)
- [6. Сетевая инфраструктура и безопасность (Network Security)](#6-сетевая-инфраструктура-и-безопасность--networking-and-security-stack-network-security)

### 🛡️ Стек Безопасности (Security Stack)
- [7. Защита приложений и WAF](#7-защита-приложений-и-фильтрация-трафика--web-application-firewall-and-security-waf)
- [8. Управление идентификацией и SSO (IAM)](#8-управление-идентификацией-и-единый-вход--identity-and-access-management-iam--sso)
- [9. Службы каталогов и Identity](#9-службы-каталогов-и-идентификация--directory-services-identity)
- [10. Изоляция процессов и Hardening](#10-изоляция-процессов-и-усиление-защиты--system-hardening-and-mac-security)
- [11. Сканирование и обнаружение угроз (IDS)](#11-сканирование-и-обнаружение-угроз--scanning-and-intrusion-detection-ids)
- [12. Шифрование данных и криптография](#12-шифрование-данных-и-криптография--data-encryption-and-cryptography-cryptography)

### 💾 Данные и Хранение (Storage & Data)
- [13. Системы управления базами данных (DBMS)](#13-системы-управления-базами-данных--database-management-systems-dbms)
- [14. Распределенные и объектные хранилища](#14-распределенные-и-объектные-хранилища--distributed-and-object-storage-distributed-storage)
- [15. Программные хранилища и NAS (SDS)](#15-программные-хранилища-и-сетевые-диски--software-defined-storage-and-nas-sds)
- [16. Брокеры сообщений и шины данных (MB)](#16-брокеры-сообщений-и-шины-данных--message-brokers-and-data-buses-mb)
- [17. Резервное копирование и восстановление (BR)](#17-резервное-копирование-и-восстановление--backup-and-disaster-recovery-br)

### 🔭 Наблюдаемость и Автоматизация (DevOps)
- [18. Системы мониторинга и метрик (MO)](#18-системы-мониторинга-и-метрик--monitoring-and-metrics-systems-mo)
- [19. Централизованное логирование (CL)](#19-централизованное-логирование--centralized-logging-cl)
- [20. Визуализация и оповещение (VA)](#20-визуализация-и-оповещение--visualization-and-alerting-va)
- [21. Инфраструктура как код (IaC)](#21-инфраструктура-как-код--infrastructure-as-code-iac)
- [22. Управление конфигурациями (CM)](#22-управление-конфигурациями--configuration-management-cm)

### 💻 Стек Разработки (Development)
- [23. Системы управления версиями (VCS)](#23-системы-управления-версиями--version-control-systems-vcs)
- [24. Сборка и компиляция (Build Systems)](#24-сборка-и-компиляция--build-systems-and-toolchains-build-systems)
- [25. Системная отладка и анализ (Debugging)](#25-системная-отладка-и-анализ--system-debugging-and-profiling-debugging)
- [26. Среда разработки и редакторы (Workspace)](#26-среда-разработки-и-редакторы--development-workspace-and-editors-workspace)
- [27. Языки программирования (PL)](#27-языки-программирования--programming-languages-pl)

### 🌍 Прикладные сервисы и Связь (Communications)
- [28. Веб-серверы и прокси-системы (Web)](#28-веб-серверы-и-прокси-системы--web-servers-and-reverse-proxies-web)
- [29. IP-телефония и голосовая связь (VoIP)](#29-ip-телефония-и-голосовая-связь--ip-telephony-and-voice-over-ip-voip)
- [30. Почтовая инфраструктура и клиенты (Email)](#30-почтовая-инфраструктура-и-клиенты--mail-infrastructure-and-clients-email)
- [31. Децентрализованные мессенджеры (IM / P2P)](#31-децентрализованные-мессенджеры-и-протоколы--decentralized-messaging-im--p2p)
- [32. Федеративные социальные сети (Fediverse)](#32-федеративные-социальные-сети--federated-social-networks-fediverse)
- [33. Суверенные хабы (Self-hosted Hubs)](#33-суверенные-платформы-управления--self-hosted-management-hubs-hubs)

### ⚙️ Инженерные и Бизнес-системы (Engineering & Business)
- [34. Инженерное проектирование (CAD / EDA)](#34-инженерное-проектирование-и-автоматизация--engineering-design-and-automation-cad--eda)
- [35. Управление ресурсами (ERP / CRM)](#35-управление-ресурсами-и-предприятием--enterprise-resource-planning-erp--crm)
- [36. Логистика, склад и торговля (SCM / POS)](#36-логистика-склад-и-торговля--supply-chain-and-commerce-scm--pos)
- [37. Работа с графикой и анимацией (2D / 3D)](#37-работа-с-графикой-и-анимацией--graphics-and-animation-2d--3d)
- [38. Мониторинг ресурсов и активов (SAM)](#38-мониторинг-ресурсов-и-активов--asset-and-resource-monitoring-sam)
- [39. Аналитика и ГИС (BI / GIS)](#39-аналитические-и-географические-системы--business-intelligence-and-gis-bi--gis)
- [40. Инженерный анализ и производство (CAE / CAM)](#40-инженерный-анализ-и-производство--engineering-analysis-and-manufacturing-cae--cam)
- [41. Специализированное управление (CBS / NIS / EAM)](#41-специализированное-управление-активами--specialized-asset-management-cbs--nis--eam)
- [42. Управление контентом (ECM / EDMS)](#42-управление-контентом-и-документами--content-and-document-management-ecm--edms)
- [43. Управление проектами и задачами (PMS)](#43-управление-проектами-и-разработка--project-management-and-bug-tracking-pms)
- [44. Совместная работа и снабжение (SRM)](#44-совместная-работа-и-снабжение--collaboration-and-supply-management-srm)


## 1. Типы лицензий и правовой статус ПО / License Types and Legal Status (LFS)
*Выбор лицензии определяет условия владения кодом. Инструмент должен быть под полным контролем.*

*   **Permissive (BSD/MIT/Apache 2.0)** — Максимальная свобода интеграции без обязательного открытия производного кода. [[Сравнение]](https://choosealicense.com)
*   **Strong Copyleft (GPL v2/v3, AGPL)** — Обязательное сохранение открытости всех производных работ. [[О лицензии]](https://www.gnu.org)
*   **Weak Copyleft (LGPL, MPL)** — Допускает связывание с закрытым кодом, сохраняя открытость самой библиотеки. [[Различия]](https://www.mozilla.org)

## 2. Операционные системы / Operating Systems (OS)
*Фундаментальный слой системы: ядра и дистрибутивы.*

*   **GNU/Linux** — Семейство открытых операционных систем на базе ядра Linux. [[Kernel]](https://www.kernel.org) | [[Repo]](https://github.com) | [[Install]](https://www.youtube.com)
*   **FreeBSD** — Высокопроизводительная ОС, происходящая от Berkeley Software Distribution. [[Docs]](https://docs.freebsd.org) | [[Repo]](https://github.com) | [[Install]](https://www.youtube.com)
*   **illumos** — Свободная ОС на базе OpenSolaris (ядро, ZFS, зоны). [[Docs]](https://illumos.org) | [[Repo]](https://github.com)
*   **GNU/Hurd** — Микроядерная операционная система, разрабатываемая в рамках проекта GNU. [[Docs]](https://www.gnu.org) | [[Wiki]](https://darnassus.sceen.net)

## 3. Изоляция и виртуализация / Virtualization and Core Isolation (Compute)
*Низкоуровневые механизмы ядра и аппаратная виртуализация.*

*   **Linux Namespaces** — Изоляция системных ресурсов (Network, PID, Mount). [[Manual]](https://man7.org) | [[Video]](https://www.youtube.com)
*   **Cgroups v2** — Иерархическое ограничение ресурсов (CPU, RAM, I/O) в Linux. [[Docs]](https://www.kernel.orgdoc/html/latest/admin-guide/cgroup-v2.html)
*   **FreeBSD Jails** — Нативная технология изоляции на уровне ядра FreeBSD. [[Handbook]](https://docs.freebsd.orgjails/) | [[Install]](https://www.youtube.com)
*   **KVM** — Инфраструктура аппаратной виртуализации в ядре Linux. [[Docs]](https://www.linux-kvm.org) | [[Install]](https://www.youtube.com)
*   **QEMU** — Универсальный эмулятор и виртуализатор машин. [[Docs]](https://www.qemu.org) | [[Repo]](https://github.com)
*   **bhyve** — Современный лаконичный гипервизор FreeBSD. [[Wiki]](https://wiki.freebsd.org) | [[Install]](https://www.youtube.com)

## 4. Контейнеризация и среды исполнения / Containerization and Runtimes (Containers)
*Инструменты создания, сборки и запуска изолированных приложений.*

*   **Docker** — Стандарт автоматизации развертывания приложений в контейнерах. [[Docs]](https://docs.docker.com) | [[Install]](https://www.youtube.com)
*   **Podman** — Daemonless-альтернатива Docker для работы без root-привилегий. [[Docs]](https://podman.io) | [[Repo]](https://github.com) | [[Install]](https://www.youtube.com)
*   **Containerd** — Легковесный промышленный стандарт среды выполнения. [[Docs]](https://containerd.io) | [[Repo]](https://github.com)
*   **LXC (Linux Containers)** — Система контейнеризации уровня ОС (база для Proxmox). [[Docs]](https://linuxcontainers.org) | [[Install]](https://www.youtube.com)
*   **Buildah** — Утилита для сборки OCI-образов без использования демонов. [[Docs]](https://buildah.io) | [[Repo]](https://github.com)

## 5. Оркестрация кластеров и GitOps / Cluster Orchestration and GitOps (OCM)
*Управление распределенными ресурсами и автоматизация доставки.*

*   **Kubernetes (K8s)** — Промышленный стандарт управления контейнерами. [[Docs]](https://kubernetes.io) | [[Course]](https://www.youtube.com)
*   **K3s** — Облегченная версия K8s для Edge и малых серверов. [[Docs]](https://docs.k3s.io) | [[Install]](https://www.youtube.com)
*   **HashiCorp Nomad** — Гибкий оркестратор для контейнеров, бинарников и ВМ. [[Docs]](https://developer.hashicorp.com) | [[Install]](https://www.youtube.com)
*   **Docker Swarm** — Встроенное решение для простых контейнерных кластеров. [[Docs]](https://docs.docker.com)
*   **Argo CD** — Инструмент непрерывной доставки (GitOps) для Kubernetes. [[Docs]](https://argoproj.github.io) | [[Install]](https://www.youtube.com)
*   **Flux CD** — Набор инструментов синхронизации кластера с Git. [[Docs]](https://fluxcd.io) | [[Install]](https://www.youtube.com)

## 6. Сетевая инфраструктура и безопасность / Networking and Security Stack (Network Security)
*Анализ, туннелирование и фильтрация трафика.*

*   **Wireshark** — Графический анализатор протоколов для детального разбора трафика. [[Docs]](https://www.wireshark.org) | [[Video]](https://www.youtube.com)
*   **Tcpdump** — Консольная утилита для захвата и анализа пакетов. [[Docs]](https://www.tcpdump.org) | [[Guide]](https://www.youtube.com)
*   **MTR (My Traceroute)** — Диагностика сети (ping + traceroute). [[Repo]](https://github.com) | [[Guide]](https://www.linode.com)
*   **Netcat (nc)** — Универсальная утилита («швейцарский нож») для TCP/UDP. [[Manual]](https://linux.die.net)
*   **WireGuard** — Современный высокоскоростной протокол VPN с криптографией. [[Docs]](https://www.wireguard.com) | [[Install]](https://www.youtube.com)
*   **OpenVPN** — Классическое решение для зашифрованных каналов. [[Docs]](https://openvpn.net) | [[Install]](https://www.youtube.com)
*   **Tailscale** — Решение для Mesh-сетей (SDN) на базе WireGuard. [[Docs]](https://tailscale.com) | [[Install]](https://www.youtube.com)
*   **ZeroTier** — Платформа для виртуализации глобальных сетей (P2P SDN). [[Docs]](https://docs.zerotier.com) | [[Install]](https://www.youtube.com)
*   **NFTables** — Современная подсистема фильтрации пакетов в ядре Linux. [[Wiki]](https://wiki.nftables.org) | [[Guide]](https://www.youtube.com)
*   **IPTables** — Классический интерфейс управления фильтрацией в Linux. [[Manual]](https://linux.die.net)
*   **PF (Packet Filter)** — Эталонный сетевой экран во FreeBSD/OpenBSD. [[Handbook]](https://docs.freebsd.orgfirewalls/#firewalls-pf)
*   **Fail2ban** — Автоматическая блокировка IP-адресов при признаках атак. [[Docs]](https://www.fail2ban.org) | [[Install]](https://www.youtube.com)
*   **CrowdSec** — Поведенческий анализ угроз (IPS) на основе логов. [[Docs]](https://docs.crowdsec.net) | [[Install]](https://www.youtube.com)
*   **PacketFence** — Полнофункциональное решение для контроля доступа (NAC). [[Docs]](https://www.packetfence.org) | [[Install]](https://www.youtube.com)
*   **FreeRADIUS** — Сервер для централизованной авторизации и учета. [[Docs]](https://freeradius.org) | [[Install]](https://www.youtube.com)

## 7. Защита приложений и фильтрация трафика / Web Application Firewall and Security (WAF)
*Защита веб-сервисов, API и микросервисов.*

*   **ModSecurity** — Классический WAF-модуль для защиты от SQLi и XSS. [[Repo]](https://github.com)
*   **Wallarm** — Современное решение для защиты API и микросервисов. [[Site]](https://wallarm.com)
*   **Authelia** — Портал двухфакторной аутентификации (2FA) перед обратным прокси. [[Docs]](https://www.authelia.com) | [[Install]](https://www.youtube.com)

## 8. Управление идентификацией и единый вход / Identity and Access Management (IAM / SSO)
*Централизованные платформы управления доступом.*

*   **Keycloak** — Система управления доступом и SSO (OIDC, SAML). [[Site]](https://www.keycloak.org) | [[Install]](https://www.youtube.com)
*   **Authentik** — Платформа аутентификации с защитой приложений. [[Docs]](https://goauthentik.io)
*   **Authelia (Identity)** — Минималистичный портал аутентификации с поддержкой 2FA. [[Docs]](https://www.authelia.com)

## 9. Службы каталогов и идентификация / Directory Services (Identity)
*Инфраструктурные решения для доменных сред.*

*   **FreeIPA** — Интегрированное решение для управления идентификацией в Linux. [[Docs]](https://www.freeipa.org)
*   **Samba 4** — Реализация протоколов Microsoft AD для Linux/Unix сред. [[Wiki]](https://wiki.samba.org)
*   **Univention Corporate Server (UCS)** — Платформа на базе Debian для AD-домена. [[Site]](https://www.univention.com)
*   **Zentyal Server** — Управление AD на базе Ubuntu. [[Site]](https://zentyal.com)
*   **LLDAP** — Упрощенная реализация LDAP для небольших команд. [[Repo]](https://github.com)

## 10. Изоляция процессов и усиление защиты / System Hardening and MAC (Security)
*Механизмы принудительного контроля доступа.*

*   **SELinux** — Система мандатного управления доступом (MAC) для RHEL-стека. [[Wiki]](https://selinuxproject.org)
*   **AppArmor** — Система безопасности на базе профилей для Debian/Ubuntu. [[Wiki]](https://gitlab.com)
*   **Sudo** — Программа делегирования привилегий суперпользователя. [[Site]](https://www.sudo.ws)
*   **Doas** — Минималистичная альтернатива sudo из OpenBSD. [[Repo]](https://github.com)
*   **Lynis** — Утилита для глубокого аудита безопасности Unix-систем. [[Site]](https://cisofy.com) | [[Install]](https://www.youtube.com)


## 11. Сканирование и обнаружение угроз / Scanning and Intrusion Detection (IDS)
*Средства поиска уязвимостей и сетевого сканирования.*

*   **Wazuh** — Платформа мониторинга безопасности и обнаружения вторжений (HIDS). [[Docs]](https://documentation.wazuh.com) | [[Install]](https://www.youtube.com)
*   **Trivy** — Сканер безопасности для контейнеров, файловых систем и IaC. [[Repo]](https://github.com)
*   **Nmap** — Мощный сканер сети для обнаружения хостов и открытых портов. [[Guide]](https://nmap.org) | [[Video]](https://www.youtube.com)
*   **GVM (OpenVAS)** — Профессиональный сканер известных сетевых уязвимостей. [[Site]](https://www.openvas.org) | [[Install]](https://www.youtube.com)

## 12. Шифрование данных и криптография / Data Encryption and Cryptography (Cryptography)
*Защита информации «в покое» и дисковых подсистем.*

*   **LUKS** — Стандарт шифрования дисковых разделов в Linux. [[GitLab]](https://gitlab.com)
*   **GnuPG (GPG)** — Реализация стандарта OpenPGP для шифрования и подписи данных. [[Site]](https://gnupg.org)
*   **Geli** — Система блочного шифрования дисков в операционной системе FreeBSD. [[Handbook]](https://docs.freebsd.org)

## 13. Системы управления базами данных / Database Management Systems (DBMS)
*Логическая организация и транзакционная обработка данных.*

*   **PostgreSQL** — Мощная объектно-реляционная система с поддержкой сложных типов данных. [[Docs]](https://www.postgresql.org)
*   **MariaDB** — Популярное ответвление MySQL, созданное для сохранения открытости кода. [[Repo]](https://github.com)
*   **MySQL** — Классическая реляционная база данных, стандарт для веб-разработки. [[Docs]](https://dev.mysql.com)
*   **SQLite** — Встраиваемая библиотека базы данных, работающая напрямую с файлом. [[Site]](https://www.sqlite.org)
*   **ClickHouse** — Столбцовая СУБД для сверхбыстрой аналитики больших данных (OLAP). [[Docs]](https://clickhouse.com) | [[Install]](https://www.youtube.com)
*   **MongoDB (Community Edition)** — Документоориентированная система с гибкой JSON-схемой. [[Docs]](https://www.mongodb.com)
*   **Redis** — Высокопроизводительное хранилище структур данных в памяти (In-memory). [[Docs]](https://redis.io)
*   **InfluxDB** — Специализированная БД для временных рядов (метрики и мониторинг). [[Docs]](https://docs.influxdata.com)

## 14. Распределенные и объектные хранилища / Distributed and Object Storage (Distributed Storage)
*Агрегация ресурсов в отказоустойчивые кластеры.*

*   **Ceph** — Промышленная платформа распределенного хранения (Block, File, Object). [[Docs]](https://docs.ceph.com) | [[Install]](https://www.youtube.com)
*   **MinIO** — Высокопроизводительное объектное хранилище, совместимое с API Amazon S3. [[Docs]](https://min.io) | [[Install]](https://www.youtube.com)
*   **Longhorn** — Облачное блочное хранилище с высокой доступностью для Kubernetes. [[Docs]](https://longhorn.io)
*   **GlusterFS** — Масштабируемая сетевая ФС для агрегации дисковых ресурсов. [[Docs]](https://docs.gluster.org)

## 15. Программные хранилища и сетевые диски / Software Defined Storage and NAS (SDS)
*Готовые платформы для управления дисковыми массивами.*

*   **TrueNAS SCALE** — Платформа на базе Debian с поддержкой ZFS и контейнеров. [[Site]](https://www.truenas.com) | [[Install]](https://www.youtube.com)
*   **OpenMediaVault (OMV)** — NAS-решение на базе стабильной ветки Debian. [[Docs]](https://docs.openmediavault.org)
*   **Unraid** — ОС для управления дисковыми массивами и виртуализацией. [[Site]](https://unraid.net)
*   **TrueNAS CORE** — Платформа хранения на базе FreeBSD и ZFS. [[Site]](https://www.truenas.com)
*   **XigmaNAS** — Дистрибутив на базе FreeBSD для создания файловых серверов. [[Site]](https://www.xigmanas.com)

## 16. Брокеры сообщений и шины данных / Message Brokers and Data Buses (MB)
*Инфраструктура для асинхронного обмена сообщениями.*

*   **Apache Kafka** — Платформа потоковой передачи данных для High Load систем. [[Site]](https://kafka.apache.org)
*   **RabbitMQ** — Универсальный брокер сообщений (AMQP) для гибкой маршрутизации. [[Docs]](https://www.rabbitmq.com)
*   **NATS** — Легковесная и производительная система обмена сообщениями. [[Docs]](https://docs.nats.io)

## 17. Резервное копирование и восстановление / Backup and Disaster Recovery (BR)
*Инструменты обеспечения живучести данных и создания точек восстановления.*

*   **17.1. Механизмы снимков и целостности (Snapshots):**
    *   **ZFS Snapshots** — Мгновенные атомарные снимки файловой системы. [[Handbook]](https://docs.freebsd.org)
    *   **Btrfs Snapshots** — Снимки ФС в Linux с поддержкой инкрементальной передачи. [[Wiki]](https://btrfs.readthedocs.io)
    *   **Timeshift** — Инструмент создания снимков состояния системы для отката Linux. [[Repo]](https://github.com)
    *   **Snapper** — Специализированная утилита для управления снимками ФС. [[Site]](http://snapper.io)
*   **17.2. Архивация и дедупликация данных (Deduplication):**
    *   **BorgBackup** — Бэкап с эффективной дедупликацией, сжатием и шифрованием. [[Docs]](https://borgbackup.readthedocs.io)
    *   **Restic** — Быстрый инструмент бэкапа с нативной поддержкой S3. [[Docs]](https://restic.net)
    *   **Duplicacy** — Кроссплатформенный инструмент с уникальной дедупликацией. [[Site]](https://duplicacy.com)
*   **17.3. Специализированные и корпоративные системы (Enterprise):**
    *   **Barman** — Решение для резервного копирования и восстановления PostgreSQL. [[Site]](https://www.pgbarman.org)
    *   **Velero** — Инструмент для бэкапа и миграции ресурсов Kubernetes. [[Docs]](https://velero.io)
    *   **Bacula / Bareos** — Масштабируемые сетевые системы бэкапа корпоративного уровня. [[Bareos Docs]](https://docs.bareos.org)
    *   **Proxmox Backup Server** — Бэкап виртуальных машин и контейнеров Proxmox. [[Docs]](https://pbs.proxmox.com) | [[Install]](https://www.youtube.com)
*   **17.4. Транспорт и хранение копий (Transport):**
    *   **Rclone** — Синхронизация файлов с десятками облачных хранилищ. [[Docs]](https://rclone.org)

## 18. Системы мониторинга и метрик / Monitoring and Metrics Systems (MO)
*Сбор, хранение и анализ количественных показателей.*

*   **Prometheus** — Индустриальный стандарт мониторинга (Pull-модель). [[Docs]](https://prometheus.io) | [[Install]](https://www.youtube.com)
*   **VictoriaMetrics** — Сверхбыстрая СУБД для долгосрочного хранения метрик. [[Docs]](https://docs.victoriametrics.com)
*   **Zabbix** — Универсальная система мониторинга корпоративного класса. [[Site]](https://www.zabbix.com) | [[Install]](https://www.youtube.com)
*   **Netdata** — Мониторинг производительности систем в реальном времени. [[Docs]](https://learn.netdata.cloud)
*   **Node Exporter** — Агент для выгрузки аппаратных метрик операционной системы. [[Repo]](https://github.com)
*   **Process Exporter** — Агент для получения детальной статистики по группам процессов. [[Repo]](https://github.com)

## 19. Централизованное логирование / Centralized Logging (CL)
*Сбор и агрегация текстовых событий (логов).*

*   **Классический стек ELK (Elasticsearch Stack):**
    *   **Elasticsearch** — Распределенная поисковая система, ядро стека ELK. [[Docs]](https://www.elastic.co)
    *   **Logstash** — Компонент для динамической обработки и трансформации данных. [[Docs]](https://www.elastic.co)
    *   **Filebeat** — Легковесный агент для передачи текстовых журналов в Elasticsearch. [[Docs]](https://www.elastic.co)
    *   **Metricbeat** — Специализированный агент для передачи метрик в Elasticsearch. [[Docs]](https://www.elastic.co)
*   **Облачно-ориентированный стек EFK (Fluentd Stack):**
    *   **Fluentd** — Универсальный агрегатор данных, де-факто стандарт для облачных сред. [[Docs]](https://docs.fluentd.org)
    *   **Fluent Bit** — Ультралегкий сборщик логов, оптимизированный для контейнеров. [[Docs]](https://docs.fluentbit.io)
*   **Экономичный стек PLG (Grafana Loki Stack):**
    *   **Grafana Loki** — Система хранения логов, индексирующая только метаданные. [[Docs]](https://grafana.com) | [[Install]](https://www.youtube.com)
    *   **Promtail** — Агент для извлечения логов и их передачи в систему Loki. [[Docs]](https://grafana.comclients/promtail/)
*   **Универсальные конвейеры данных (Data Pipelines):**
    *   **Vector** — Высокопроизводительный инструмент на Rust для построения пайплайнов. [[Docs]](https://vector.dev)

## 20. Визуализация и оповещение / Visualization and Alerting (VA)
*Графическое представление данных и системы уведомлений.*

*   **Grafana** — Платформа для визуализации метрик, логов и трассировок. [[Site]](https://grafana.com) | [[Install]](https://www.youtube.com)
*   **Kibana** — Визуальный интерфейс для анализа данных и навигации по Elasticsearch. [[Docs]](https://www.elastic.co)
*   **Alertmanager** — Компонент для группировки и маршрутизации уведомлений. [[Docs]](https://prometheus.ioalerting/latest/alertmanager/)
*   **Jaeger** — Система для мониторинга и распределенной трассировки запросов. [[Docs]](https://www.jaegertracing.io)

## 21. Инфраструктура как код / Infrastructure as Code (IaC)
*Инструменты декларативного развертывания ресурсов и управления облачными средами.*

*   **Terraform** — Промышленный стандарт для создания и изменения инфраструктуры через конфигурационные файлы. [[Docs]](https://developer.hashicorp.com) | [[Install]](https://www.youtube.com)
*   **OpenTofu** — Полностью открытый форк Terraform, созданный для сохранения лицензионной чистоты. [[Repo]](https://github.com)
*   **Pulumi** — Платформа IaC, позволяющая описывать инфраструктуру на стандартных языках программирования. [[Docs]](https://www.pulumi.com)
*   **Cloud-Init** — Отраслевой стандарт для автоматической первичной настройки облачных инстансов. [[Docs]](https://cloudinit.readthedocs.io)

## 22. Управление конфигурациями / Configuration Management (CM)
*Автоматизация настройки операционных систем, сервисов и приложений.*

*   **Ansible** — Мощная система автоматизации без агентов, работающая через протокол SSH. [[Docs]](https://docs.ansible.com) | [[Install]](https://www.youtube.com)
*   **SaltStack** — Высокопроизводительная платформа для удаленного исполнения команд и управления конфигурациями. [[Docs]](https://docs.saltproject.io)
*   **Puppet** — Классическая декларативная система управления инфраструктурой на основе агентов. [[Docs]](https://www.puppet.com)
*   **Chef** — Инструмент автоматизации, использующий программный подход (Ruby DSL) для описания систем. [[Docs]](https://docs.chef.io)

## 23. Системы управления версиями / Version Control Systems (VCS)
*Механизмы фиксации изменений и автономного хостинга кода.*

*   **Git** — Распределенная система контроля версий. Фундамент для работы с кодом. [[Docs]](https://git-scm.com)
*   **LazyGit** — Терминальный интерфейс (TUI) для быстрого визуального управления Git-репозиторием. [[Repo]](https://github.com)
*   **GitUI** — Высокопроизводительный консольный клиент для Git, написанный на Rust. [[Repo]](https://github.com)
*   **Gitea** — Легковесная self-hosted платформа для хостинга репозиториев. [[Docs]](https://docs.gitea.com) | [[Install]](https://www.youtube.com)
*   **Forgejo** — Независимый форк Gitea, ориентированный на полную свободу сообщества. [[Site]](https://forgejo.org)
*   **GitLab (Community Edition)** — Корпоративная платформа с полным циклом автоматизации (CI/CD). [[Docs]](https://docs.gitlab.com)

## 24. Сборка и компиляция / Build Systems and Toolchains (Build Systems)
*Инфраструктура для преобразования исходного кода в бинарные файлы.*

*   **LLVM** — Универсальная инфраструктура для построения современных компиляторов. [[Site]](https://llvm.org)
*   **GCC (GNU Compiler Collection)** — Классический набор компиляторов для C, C++ и других языков. [[Docs]](https://gcc.gnu.org)
*   **Clang** — Компилятор для C-подобных языков на базе инфраструктуры LLVM. [[Site]](https://clang.llvm.org)
*   **Make** — Традиционная утилита для автоматизации сборки через Makefile. [[Manual]](https://www.gnu.org)
*   **CMake** — Кроссплатформенная система автоматизации сборки и управления проектами. [[Docs]](https://cmake.org)
*   **Ninja** — Компактная и быстрая система сборки, ориентированная на скорость исполнения. [[Site]](https://ninja-build.org)

## 25. Системная отладка и анализ / System Debugging and Profiling (Debugging)
*Инструменты глубокого исследования работы программ и поиска ошибок.*

*   **GDB** — Универсальный системный отладчик для исследования работы программ. [[Docs]](https://www.sourceware.org) | [[Tutorial]](https://www.youtube.com)
*   **Strace** — Мониторинг системных вызовов процесса для анализа взаимодействия с ядром. [[Manual]](https://man7.org)
*   **Ltrace** — Инструмент для отслеживания вызовов функций в динамических библиотеках. [[Manual]](https://linux.die.net)
*   **Valgrind** — Фреймворк для обнаружения утечек памяти и профилирования производительности. [[Docs]](https://valgrind.org)

## 26. Среда разработки и редакторы / Development Workspace and Editors (Workspace)
*Инструменты взаимодействия между Сознанием Архитектора и кодом.*

*   **Neovim** — Расширяемый текстовый редактор на базе Vim с поддержкой Lua. [[Repo]](https://github.com) | [[Setup]](https://www.youtube.com)
*   **Emacs** — Мощная среда редактирования и организации деятельности (Lisp-based). [[Site]](https://www.gnu.org)
*   **Qt Creator** — IDE, оптимизированная для разработки кроссплатформенных приложений на C++. [[Docs]](https://doc.qt.io)
*   **VS Code (OSS)** — Открытая версия редактора (Code - OSS) без встроенной телеметрии. [[Repo]](https://github.com)

## 27. Языки программирования / Programming Languages (PL)
*Фундаментальные инструменты создания систем.*

*   **C / C++** — Стандарт системного программирования с прямым контролем ресурсов.
*   **Rust** — Современный язык с гарантиями безопасности памяти. [[Site]](https://www.rust-lang.org)
*   **Zig** — Лаконичная замена C с акцентом на простоту и ручное управление ресурсами. [[Site]](https://ziglang.org)
*   **Go (Golang)** — Язык для создания масштабируемых сетевых сервисов. [[Site]](https://go.dev)
*   **Lua / AngelScript** — Компактные встраиваемые языки для расширения программ.
*   **Python / Ruby** — Языки для быстрой автоматизации и создания сценариев.
*   **Shell (Bash, Zsh)** — Языки командной оболочки для управления процессами.

## 28. Веб-серверы и прокси-системы / Web Servers and Reverse Proxies (Web)
*Инструменты доставки контента и балансировки нагрузки.*

*   **Nginx** — Эффективный Reverse Proxy для терминации SSL и защиты бэкендов. [[Docs]](https://nginx.org)
*   **Apache HTTP Server** — Классический расширяемый веб-сервер с модульной архитектурой. [[Docs]](https://httpd.apache.org)
*   **Caddy** — Современный веб-сервер с автоматическим управлением HTTPS. [[Site]](https://caddyserver.com)
*   **HAProxy** — Высокопроизводительный балансировщик нагрузки TCP/HTTP. [[Docs]](http://www.haproxy.org)

## 29. IP-телефония и голосовая связь / IP Telephony and Voice over IP (VoIP)
*Программные АТС и SIP-прокси.*

*   **Asterisk** — Программная АТС с открытым кодом и гибкой логикой управления звонками. [[Docs]](https://wiki.asterisk.org) | [[Install]](https://www.youtube.com)
*   **FreePBX** — Графический веб-интерфейс для настройки и управления Asterisk. [[Site]](https://www.freepbx.org)
*   **Issabel** — Дистрибутив IP-АТС, объединяющий связь, почту и факс. [[Site]](https://www.issabel.org)
*   **VitalPBX** — Современная платформа телефонии на базе Asterisk. [[Docs]](https://vitalpbx.com)
*   **Incredible PBX** — Защищенная сборка телефонии с предустановленным фаерволом. [[Site]](https://incrediblepbx.com)
*   **Kamailio** — Высокопроизводительный SIP-прокси сервер для обработки критических нагрузок. [[Docs]](https://www.kamailio.org)
*   **FreeSWITCH** — Коммуникационная платформа для передачи голоса и видео. [[Docs]](https://freeswitch.org)

## 30. Почтовая инфраструктура и клиенты / Mail Infrastructure and Clients (Email)
*Автономные узлы связи и приложения для работы с почтой.*

*   **Postfix** — Надежный и производительный агент передачи почты (MTA). [[Docs]](https://www.postfix.org)
*   **Exim** — Гибкий почтовый сервер (MTA) с мощной маршрутизацией. [[Docs]](https://www.exim.org)
*   **Dovecot** — Высокопроизводительный сервер для доступа по протоколам IMAP и POP3. [[Docs]](https://doc.dovecot.org)
*   **Rspamd** — Быстрая система фильтрации спама на базе нейронных сетей. [[Docs]](https://rspamd.com)
*   **ClamAV** — Антивирусный движок для проверки почтовых шлюзов. [[Docs]](https://docs.clamav.net)
*   **Roundcube** — Популярный веб-интерфейс для доступа к почтовым ящикам. [[Site]](https://roundcube.net)
*   **RainLoop** — Современный и быстрый веб-клиент для электронной почты. [[Site]](https://www.rainloop.net)
*   **Thunderbird / Betterbird** — Полнофункциональные настольные почтовые клиенты.
*   **Claws Mail** — Минималистичный и быстрый клиент на базе GTK+. [[Site]](https://www.claws-mail.org)

## 31. Децентрализованные мессенджеры и протоколы / Decentralized Messaging (IM / P2P)
*Инфраструктура мгновенного обмена сообщениями, аудио и видеосвязи.*

*   **31.1. WebRTC и медиа-серверы (Backend):**
    *   **Jitsi Videobridge / Jicofo** — Узлы маршрутизации видеосигнала для Jitsi Meet. [[Docs]](https://jitsi.github.io)
    *   **Janus Gateway** — Универсальный WebRTC-шлюз для интеграции медиа-потоков. [[Repo]](https://github.com)
    *   **Galene** — Сверхлегкий SFU-сервер на Go для трансляций и лекций. [[Site]](https://galene.org)
    *   **Coturn** — TURN/STUN сервер для обхода NAT и работы видеосвязи. [[Repo]](https://github.com)
*   **31.2. Экосистема XMPP (Jabber):**
    *   **ejabberd** — Масштабируемый XMPP-сервер на Erlang. [[Docs]](https://docs.ejabberd.im)
    *   **Prosody IM** — Легковесный и гибкий XMPP-сервер на Lua. [[Site]](https://prosody.im)
    *   **Conversations** — Эталонный Android-клиент (Голос + Видео). [[Site]](https://conversations.im)
    *   **Dino** — Современный нативный клиент для Linux (GTK). [[Site]](https://dino.im)
*   **31.3. Экосистема Matrix:**
    *   **Synapse / Dendrite / Conduit** — Реализации серверной части Matrix. [[Matrix Docs]](https://matrix.org)
    *   **Element** — Официальный мультиплатформенный клиент. [[Site]](https://element.io)
    *   **nheko** — Быстрый нативный клиент на C++/Qt. [[Repo]](https://github.com)
*   **31.4. Распределенные и P2P решения (Privacy-First):**
    *   **Jami (GNU)** — Распределенная сеть (DHT) без серверов. [[Site]](https://jami.net)
    *   **SimpleX Chat** — Мессенджер без User ID через эфемерные реле. [[Site]](https://simplex.chat)
    *   **Tox / Session / Cwtch** — Инструменты прямой и луковой маршрутизации сообщений.
*   **31.5. Анализ рисков и форки:**
    *   **Signal** — Клиент с открытым кодом при централизованном бэкенде.
    *   **Molly / Molly-Socket** — Усиленный форк Signal с шифрованием БД. [[Repo]](https://github.com)

## 32. Федеративные социальные сети / Federated Social Networks (Fediverse)
*Децентрализованные альтернативы корпоративным медиа-платформам.*

*   **Mastodon / Pleroma / Misskey** — Платформы микроблогинга (аналоги **Twitter**).
*   **Friendica / Hubzilla / Diaspora** — Социальные сети (аналоги **Facebook / VK**).
*   **Pixelfed** — Обмен фотографиями (аналог **Instagram**). [[Site]](https://pixelfed.org)
*   **PeerTube** — Децентрализованный видеохостинг (аналог **YouTube**). [[Site]](https://joinpeertube.org)
*   **Lemmy / Kbin** — Агрегаторы ссылок и форумы (аналоги **Reddit**).
*   **Funkwhale** — Музыкальные платформы (аналог **Spotify**). [[Site]](https://funkwhale.audio)
*   **WriteFreely / Plume** — Федеративный блогинг (аналог **Medium**).

## 33. Суверенные платформы управления / Self-hosted Management Hubs (Hubs)
*Комплексные экосистемы для коллективной работы и офисных функций.*

*   **Nextcloud Hub** — Индустриальный стандарт с модулями Deck, Talk и Files. [[Docs]](https://docs.nextcloud.com) | [[Install]](https://www.youtube.com)
*   **ownCloud Infinite Scale (oCis)** — Высокопроизводительная платформа на Go. [[Docs]](https://doc.owncloud.com)
*   **Pydio Cells** — Платформа на Go с продвинутой системой прав доступа (RBAC). [[Docs]](https://pydio.com)
*   **OpenProject** — Мощная альтернатива MS Project для управления проектами. [[Site]](https://www.openproject.org)
*   **OnlyOffice / Collabora** — Движки совместного редактирования документов.

## 34. Инженерное проектирование и автоматизация / Engineering Design (CAD / EDA)
*   **34.1. CAD системы:** **FreeCAD**, **LibreCAD**, **QCAD**, **BRL-CAD**, **OpenSCAD**, **Salome**.
*   **34.2. EDA системы:** **KiCad**, **gEDA**, **Fritzing**, **Pcb-rnd**. [[KiCad Docs]](https://docs.kicad.org)

## 35. Управление ресурсами и предприятием / Enterprise Planning (ERP / CRM)
*   **Odoo / ERPNext** — Модульные платформы управления предприятием. [[ERPNext Docs]](https://docs.erpnext.com)
*   **Tryton / iDempiere** — Масштабируемые ERP на открытых стандартах.
*   **SuiteCRM / EspoCRM** — Системы управления отношениями с клиентами.

## 36. Логистика, склад и торговля / Supply Chain and Commerce (SCM / POS)
*   **OpenBoxes / myWMS** — Управление цепочками поставок и складом.
*   **PartKeepr / Snipe-IT** — Инвентаризация ИТ-активов и компонентов. [[Snipe-IT Repo]](https://github.com)
*   **UniCenta / SambaPOS** — Системы для точек продаж и ресторанов.

## 37. Работа с графикой и анимацией / Graphics and Animation (2D / 3D)
*   **2D:** **GIMP**, **Krita**, **Synfig Studio**, **OpenToonz**, **Pencil2D**.
*   **3D:** **Blender**, **Bforartists**, **Wings 3D**, **Dust3D**, **Dilay**. [[Blender Docs]](https://docs.blender.org)
*   **Render:** **LuxCoreRender**, **YafaRay**, **POV-Ray**, **Aqsis**.

## 38. Мониторинг ресурсов и активов / Asset and Resource Monitoring (SAM)
*   **OpenBoxes** — Учет активов. **eHour / Kimai** — Тайм-трекинг. [[Kimai Repo]](https://github.com)

## 39. Аналитические и географические системы / Business Intelligence and GIS (BI / GIS)
*   **BI:** **Metabase**, **Apache Superset**, **Pentaho**, **JasperReports**. [[Superset Docs]](https://superset.apache.org)
*   **GIS:** **QGIS**, **PostGIS**, **GRASS GIS**. [[QGIS Docs]](https://docs.qgis.org)

## 40. Инженерный анализ и производство / Engineering Analysis (CAE / CAM)
*   **CAE:** **OpenFOAM**, **Code_Aster**, **CalculiX**. [[OpenFOAM Docs]](https://www.openfoam.com)
*   **CAM:** **FreeCAD (Path)**, **PyCAM**.

## 41. Специализированное управление активами / Specialized Assets (CBS / NIS / EAM)
*   **CBS:** **Apache Fineract**, **Mifos X**. [[Fineract Docs]](https://fineract.apache.org)
*   **NIS:** **NetBox**, **Netdot**. [[NetBox Repo]](https://github.com)
*   **EAM:** **Snipe-IT**, **OpenMAINT**.

## 42. Управление контентом и документами / Content Management (ECM / EDMS)
*   **Alfresco**, **Mayan EDMS**. [[Mayan Docs]](https://docs.mayan-edms.com)

## 43. Управление проектами и разработка / Project Management (PMS)
*   **PMS:** **OpenProject**, **Taiga**, **Focalboard**.
*   **Bug Tracking:** **MantisBT**, **Redmine**, **Gitea Issues**. [[Redmine Site]](https://www.redmine.org)

## 44. Совместная работа и снабжение / Collaboration and SRM
*   **Collaboration:** **Mattermost**, **Zulip**, **Etherpad**, **CryptPad**.
*   **SRM:** **Apache OFBiz**, **Odoo (Purchase)**.
