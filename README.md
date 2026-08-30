# Привет, меня зовут Кирилл 👋
### C++ разработчик · Системное программирование · Backend

C++ разработчик с опытом сквозной разработки высоконагруженных сетевых сервисов — от архитектуры и реализации до развёртывания и поддержки в production. Специализируюсь на асинхронном сетевом взаимодействии (Boost.Asio, gRPC, WebSocket), отказоустойчивых интеграциях с внешними системами (connection pooling, health-check, circuit breaker) и многопоточной обработке данных. Участвую в код-ревью, следую принципам SOLID, DRY, KISS. Профессиональный интерес — низкоуровневая оптимизация производительности и построение надёжных распределённых систем.
## О себе

**Что умею:**
- Сетевое взаимодействие: асинхронный IO (Boost.Asio), gRPC/Protobuf, WebSocket, connection pooling, отказоустойчивые интеграции с внешними API
- Управление памятью: умные указатели, RAII, диагностика утечек (Valgrind, AddressSanitizer)
- Многопоточность: синхронизация, lock-free структуры данных, work-stealing паттерны
- Проектирование: декомпозиция сервисов, выбор структур данных под задачу, профилирование узких мест
- Инфраструктура: контейнеризация (Docker), CI/CD, написание и поддержка сборочных систем на CMake

Интересуюсь промышленной разработкой, углубляюсь в архитектуру, тестирование и оптимизацию. В фокусе интересов — системное программирование, алгоритмы и производительность.

## Проекты
- [Slab-allocator](https://github.com/cpprismic/slab-allocator) - быстрый пул-аллокатор блоков фиксированного размера для C++, плюс SlabMemoryResource — std::pmr::memory_resource поверх него
- [Document Signing Service](https://github.com/cpprismic/document-signing-service) - сервис автоматизации подписания документов: генерация PDF-соглашений с динамическими шаблонами, SMS-аутентификация, хэш метаданных подписания, наложение цифрового штампа
- [Cve-monitor](https://github.com/cpprismic/cve-parser) - асинхронный сервис мониторинга и парсинга новых уязвимостей из разных источников, спроектированный на [userver](https://userver.tech/) framework
- [Async-sink](https://github.com/cpprismic/async-sink) - логгер с производительностью 5+ млн сообщений/сек и неблокирующей записью, header-only библиотека с zero-allocation архитектурой и гибкой системой sink'ов
- [Html to pdf converter](https://github.com/cpprismic/html-to-pdf-converter) - многопоточный асинхронный конвертер HTML в PDF
- [Load Tester](https://github.com/cpprismic/load_tester) - утилита нагрузочного тестирования HTTP API микросервисов
- [Test runner](https://github.com/cpprismic/mini-projects/tree/main/test%20runner) - мини-фреймворк для юнит-тестирования
- [Search system](https://github.com/cpprismic/mini-projects/tree/main/search%20server), 
  [Search system Lite](https://github.com/cpprismic/mini-projects/tree/main/search%20server%20lite) - модели индексирования и поиска с ранжированием TF-IDF в текстах с фильтрацией по предикатам, поддержкой минус-словами, статусами и кастомными рейтингами
- [Image converter](https://github.com/cpprismic/mini-projects/tree/main/image%20converter) - библиотека для загрузки, сохранения и конвертации растровых изображений с поддержкой форматов JPEG, PPM и BMP
- [JSON/XML-file reader](https://github.com/cpprismic/mini-projects/tree/main/simple%20JSON%2C%20XML-file%20reader), 
[INI-file reader](https://github.com/cpprismic/mini-projects/tree/main/simple%20INI-file%20reader) - парсеры конфигурационных файлов, реализованный без сторонних библиотек
- [Stack_vector](https://github.com/cpprismic/mini-projects/blob/main/stack%20vector/stack_vector.h "реализация ограниченного вектора без динамического выделения памяти"), 
[Vector with smart pointers](https://github.com/cpprismic/mini-projects/blob/main/simple%20vector%20more%20complicated%20version/raw_memory.h), 
[Single linked list](https://github.com/cpprismic/mini-projects/blob/main/single%20linked%20list/single-linked-list.h), 
[Hash map](https://github.com/cpprismic/mini-projects/blob/main/hash%20table%20class/main.cpp) - упрощенные реализации классических структур данных
- [остальные проекты с описанием](https://github.com/cpprismic/mini-projects)

## Технологии и инструменты

- **Язык:** C++17/20 (STL, RAII, Multithreading, Templates, Move semantics), Python 3
- **Сети и протоколы:** TCP/IP, UDP, Boost.Asio, Boost.Beast, WebSocket, gRPC, Protobuf, TLS/mTLS (OpenSSL)
- **Инфраструктура и очереди:** Redis (Boost.Redis), Kafka (librdkafka), PostgreSQL, SQLite, REST API, микросервисная архитектура
- **Сборка и компиляторы:** CMake, g++, clang, MSVC
- **Инфраструктура:** Git (GitHub/GitLab), CI/CD (GitHub Actions/GitLab CI), Docker
- **Тестирование и отладка:** GoogleTest/gmock, GDB, Valgrind, Sanitizers, Perf
- **Подходы:** ООП, SOLID, RAII, Templates, constexpr-if, multithreading, move-семантика, perfect forwarding, exception handling

![C++](https://img.shields.io/badge/C++-20-00599C?style=flat&logo=cplusplus&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=google&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/Python-3-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
