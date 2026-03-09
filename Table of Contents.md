# 📚 База знаний Архитектора / Knowledge Base
> *"В мире энтропии Сознание — единственный источник Структуры. Предать свой Порядок — значит добровольно выбрать распад."*

---

## 📑 Содержание / Table of Contents

1. [🏗️ Фундамент (The Base)](#1-фундамент-the-base)
2. [🧊 Слой Изоляции (Compute Layer)](#2-слой-изоляции-compute-layer)
3. [🛡️ Безопасность и Доступ (Security Stack)](#3-безопасность-и-доступ-security-stack)
4. [💾 Данные и Хранение (Storage & Data)](#4-данные-и-хранение-storage--data)
5. [🔭 Наблюдаемость (Observability)](#5-наблюдаемость-observability)
6. [🛠️ Инструментарий и Автоматизация (DevOps/Dev)](#6-инструментарий-и-автоматизация-devopsdev)
7. [🌍 Сервисы и Выживание (Business Continuity)](#7-сервисы-и-выживание-business-continuity)

---

## 1. 🏗️ Фундамент (The Base)
*Базовые правила и системные ресурсы, на которых строится всё остальное.*

### 1.1 Лицензирование и Свобода (LFS)
*   **[GNU GPL](https://www.gnu.org)** — «Вирусная» свобода. Гарантирует, что производные работы останутся открытыми.
*   **[MIT License](https://opensource.org)** — Максимальный прагматизм. Разрешает любое использование при сохранении авторства.
*   **[Apache 2.0](https://www.apache.org)** — Профессиональный стандарт с явным предоставлением патентных прав.
*   **[Copyleft vs Copyright](https://www.gnu.org)** — Концепция «авторского права наоборот». Основа суверенитета Open Source.

### 1.2 Операционные системы (OS)
*   **[Debian](https://www.debian.org)** — Индустриальный стандарт стабильности и предсказуемости.
*   **[Arch Linux](https://archlinux.org)** — Система для глубокого контроля и понимания внутренних механизмов ОС.
*   **[FreeBSD](https://www.freebsd.org)** — Архитектурная чистота. Нативная интеграция ZFS и Jails.
*   **[OpenBSD](https://www.openbsd.org)** — Бастион безопасности. Бескомпромиссный подход к аудиту кода.
*   **[Alpine Linux](https://alpinelinux.org)** — Дистиллированная ОС (5МБ). Идеальна для безопасных контейнеров.
*   **[illumos](https://illumos.org)** — Наследник OpenSolaris для ценителей эталонных ZFS и DTrace.

### 1.3 Сетевая связность и анализ (NAC)
*   **[Wireshark](https://www.wireshark.org)** / **[Tcpdump](https://www.tcpdump.org)** — Глубокий анализ и перехват трафика.
*   **[MTR](https://github.com)** — Диагностика маршрутов и выявление потерь на узлах.
*   **[WireGuard](https://www.wireguard.com)** — Современный VPN на базе эллиптических кривых. Скорость и простота.
*   **[HAProxy](http://www.haproxy.org)** — Бескомпромиссный балансировщик нагрузки TCP/HTTP.

---

## 2. 🧊 Слой Изоляции (Compute Layer)
*Управление ресурсами через возведение границ. Изоляция как закон.*

### 2.1 Контейнеризация и механизмы изоляции (CI)
*   **[Cgroups v2](https://www.kernel.org)** / **[Namespaces](https://man7.org)** — Фундамент изоляции в ядре Linux.
*   **[Jails](https://docs.freebsd.org)** / **[BastilleBSD](https://bastillebsd.org)** — Нативная изоляция FreeBSD и фреймворк для её автоматизации.
*   **[Docker](https://www.docker.com)** / **[Podman](https://podman.io)** — Стандарты управления контейнерами (традиционный и daemonless).
*   **[bhyve](https://bhyve.org)** — Лаконичный гипервизор FreeBSD с аппаратным ускорением.

### 2.2 Оркестрация и управление кластерами (OCM)
*   **[Kubernetes (K8s)](https://kubernetes.io)** — Промышленный стандарт управления распределенными системами.
*   **[HashiCorp Nomad](https://www.nomadproject.io)** — Универсальный оркестратор для контейнеров и бинарных файлов.
*   **[Argo CD](https://argoproj.github.io)** / **[Flux CD](https://fluxcd.io)** — Реализация паттерна GitOps: Git как единственный источник истины.

---

## 3. 🛡️ Безопасность и Доступ (Security Stack)
*Создание неприступного периметра и тотальный аудит доступа.*

### 3.1 Hardening и Аудит (SH)
*   **[PF (Packet Filter)](https://www.freebsd.orgdoc/handbook/firewalls-pf.html)** / **[NFTables](https://netfilter.org)** — Сетевые экраны высшего уровня.
*   **[SELinux](https://github.com)** / **[AppArmor](https://apparmor.net)** — Мандатное управление доступом и профили безопасности.
*   **[Wazuh](https://wazuh.com)** — Платформа обнаружения вторжений (HIDS) и мониторинга целостности.
*   **[CrowdSec](https://www.crowdsec.net)** — Поведенческий анализ угроз на основе системных логов.

### 3.2 Управление секретами и Идентификация (IAM/PAM)
*   **[HashiCorp Vault](https://www.vaultproject.io)** — Динамическое управление секретами и шифрование.
*   **[Teleport](https://goteleport.com)** — Современный PAM. Замена SSH с поддержкой SSO и записью сессий.
*   **[Keycloak](https://www.keycloak.org)** — Корпоративная система управления доступом и SSO.
*   **[FreeIPA](https://www.freeipa.org)** — Комплексное управление Identity в Linux-средах (LDAP/Kerberos).

---

## 4. 💾 Данные и Хранение (Storage & Data)
*Управление данными через избыточность и целостность.*

### 4.1 Системы хранения (SS)
*   **[ZFS](https://openzfs.github.io)** — Религия целостности данных. Хранилище с самоисцелением.
*   **[Ceph](https://ceph.io)** — Промышленный стандарт распределенного хранения (Object, Block, File).
*   **[MinIO](https://min.io)** — Высокопроизводительное S3-совместимое объектное хранилище.

### 4.2 Базы данных и Брокеры (DB/MB)
*   **[PostgreSQL](https://www.postgresql.org)** — Эталонная реляционная СУБД.
*   **[ClickHouse](https://clickhouse.com)** — Молниеносная аналитика на больших данных (OLAP).
*   **[Redis](https://redis.io)** — Сверхбыстрое In-memory хранилище.
*   **[Apache Kafka](https://kafka.apache.org)** / **[RabbitMQ](https://www.rabbitmq.com)** — Нервная система архитектуры: очереди и потоки событий.

---

## 5. 🔭 Наблюдаемость (Observability)
*Перевод системы из невидимого хаоса в измеримый Порядок.*

### 5.1 Мониторинг и Логирование (MO/CL)
*   **[Prometheus](https://prometheus.io)** / **[VictoriaMetrics](https://victoriametrics.com)** — Сбор и долгосрочное хранение метрик.
*   **[Vector](https://vector.dev)** — Высокопроизводительный пайплайн данных на Rust.
*   **[Grafana Loki](https://grafana.com)** — Экономичное хранилище логов, оптимизированное для метаданных.
*   **[Elasticsearch](https://www.elastic.co)** — Мощный движок полнотекстового поиска по логам.

### 5.2 Визуализация (VA)
*   **[Grafana](https://grafana.com)** — Универсальный интерфейс визуализации всего стека.
*   **[Jaeger](https://www.jaegertracing.io)** — Распределенная трассировка запросов в микросервисах.

---

## 6. 🛠️ Инструментарий и Автоматизация (DevOps/Dev)
*Инструментарий как продолжение воли. Автоматизация созидания.*

### 6.1 IaC и Управление версиями (CM/VCS)
*   **[Git](https://git-scm.com)** / **[GitHub](https://github.com)** — Фундамент версионности и совместной работы.
*   **[Ansible](https://www.ansible.com)** — Agentless управление конфигурациями (YAML).
*   **[Terraform](https://www.terraform.io)** — Декларативное создание инфраструктуры через код.

### 6.2 Инструменты разработки и Языки (DevTools/PL)
*   **[Neovim](https://neovim.io)** / **[Vim](https://www.vim.org)** — Модальные редакторы: чистота мысли и скорость кода.
*   **[C++](https://isocpp.org)** / **[Rust](https://www.rust-lang.org)** — Системные языки: производительность и гарантии безопасности.
*   **[Go](https://go.dev)** / **[Python](https://www.python.org)** — Языки инфраструктуры и автоматизации.
*   **[Strace](https://strace.io)** / **[GDB](https://www.sourceware.org)** — Тотальная отладка и контроль исполнения.

---

## 7. 🌍 Сервисы и Выживание (Business Continuity)
*Прикладные службы и гарантия восстановления системы.*

### 7.1 Web, Почта и Связь (WS/ES/IPT)
*   **[Nginx](https://nginx.org)** / **[Caddy](https://caddyserver.com)** — Точки входа и доставка контента.
*   **[Postfix](https://www.postfix.org)** / **[Dovecot](https://www.dovecot.org)** — Автономный почтовый стек.
*   **[Asterisk](https://www.asterisk.org)** — Гибкая программная АТС.

### 7.2 Резервное копирование — Финальный щит (BR)
*   **[BorgBackup](https://borgbackup.readthedocs.io)** / **[Restic](https://restic.net)** — Дедуплицированные и зашифрованные бэкапы.
*   **[ZFS Snapshots](https://openzfs.github.ioman/8/zfs-snapshot.8.html)** — Мгновенные снимки реальности.
*   **[Velero](https://velero.io)** — Восстановление кластеров Kubernetes.
