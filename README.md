# 👋 Привет! Я Юра Струков  
**C++ Developer | Архитектор высоконагруженных систем**  

✅ **Специализация:** C++20, многопоточность (Boost.Asio), высокопроизводительные backend-системы.  
✅ **Ключевые достижения:**  
- Асинхронный сервер с обработкой **1000+ RPS** и нулевыми потерями данных.  
- Оптимизация поиска маршрутов на **40%** через алгоритм Дейкстры.  
- Сокращение IT-затрат на **25%** в роли руководителя.  

*«Оптимизация — это не улучшение кода. Это искусство убирать всё лишнее»*

---

## 🛠️ Технологии

**Языки и фреймворки:**  
[![C++20](https://img.shields.io/badge/C%2B%2B-20-00599C?logo=cplusplus)](https://isocpp.org/) 
[![Boost](https://img.shields.io/badge/Boost-1.83-00599C)](https://www.boost.org/) 
[![STL](https://img.shields.io/badge/STL-✓-blue)](https://en.cppreference.com/w/cpp/standard_library)  

**Базы данных:**  
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?logo=postgresql)](https://www.postgresql.org/)  

**Инфраструктура:**  
[![Docker](https://img.shields.io/badge/Docker-✓-2496ED?logo=docker)](https://www.docker.com/) 
[![CMake](https://img.shields.io/badge/CMake-✓-064F8C)](https://cmake.org/)  
[![Prometheus](https://img.shields.io/badge/Prometheus-✓-ED8B00)](https://prometheus.io/) 
[![Grafana](https://img.shields.io/badge/Grafana-✓-F46800)](https://grafana.com/)  

**Профилирование и мониторинг:**  
[![gprof](https://img.shields.io/badge/gprof-✓-4D4D4D)](https://sourceware.org/binutils/docs/gprof/) 
[![perf](https://img.shields.io/badge/perf-✓-4D4D4D)](https://perf.wiki.kernel.org/) 
[![FlameGraph](https://img.shields.io/badge/FlameGraph-✓-E53935)](https://github.com/brendangregg/FlameGraph)  

**Тестирование:**  
[![GoogleTest](https://img.shields.io/badge/Google_Test-✓-4D4D4D)](https://github.com/google/googletest) 
[![Catch2](https://img.shields.io/badge/Catch2-✓-4D4D4D)](https://github.com/catchorg/Catch2)  

---

## 🚀 Проекты

### 🎮 Асинхронный игровой сервер (C++20)  
**Проблема:** Нужен сервер, устойчивый к нагрузкам >1k RPS с гарантией сохранения данных.  
**Решение:**  
- Асинхронная обработка через **Boost.Asio**.  
- Сериализация состояния в PostgreSQL (интервал + аварийное сохранение).  
**Результат:**  
✅ Zero data loss при сбоях.  
✅ Задержка <50 мс на 95% запросов.  
[![Code](https://img.shields.io/badge/Код-на_гитхабе-blue)](https://github.com/realht/cpp-http_async_server)  

---

### 📊 Консольный Excel с формулами  
**Проблема:** Требовалась обработка сложных формул без циклов и лагов.  
**Решение:**  
- Парсинг формул → граф зависимостей (**ANTLR4**).  
- Кэширование результатов (+30% скорости).  
**Фишка:**  
🔒 Проверка на циклические зависимости.  
[![Code](https://img.shields.io/badge/Код-на_гитхабе-green)](https://github.com/realht/cpp-spreadsheet_in_console)  

---

### 🚍 Маршрутный справочник (Dijkstra + SVG)  
**Проблема:** Поиск оптимального маршрута за >200 мс.  
**Решение:**  
- Графы + алгоритм Дейкстры.  
- Визуализация в SVG.  
**Результат:**  
⏱️ Время расчета <100 мс.  
📉 Снижение нагрузки на CPU на 15%.  
[![Code](https://img.shields.io/badge/Код-на_гитхабе-red)](https://github.com/realht/cpp-transport_app)  

---

## 👔 Опыт управления
### Советник собственника по IT | Горно-металлургический комплекс (2018–н.в.)  
**Фокус:** Стратегия цифровой трансформации и оптимизация IT-инфраструктуры  
- 🛠️ Стратегическое управление IT-направлением: внедрение систем, оптимизация инфраструктуры, сокращение затрат на 15% без потери качества.  
- 📋 Руководство проектами: успешная реализация 10+ проектов в срок и бюджет, включая автоматизацию бизнес-процессов.  
- 🔒 Курс на безопасность: разработка политики информационной безопасности, снижение инцидентов на 30%.  
- 👥 Развитие команды: повышение квалификации сотрудников через воркшопы, рост удовлетворенности команды на 25%. 

---

## 🎓 Образование и сертификаты 

- **Яндекс Практикум** — Разработчик C++ (2024)  
- **Сбер Университет** — Digital Strategy (2024)  
- **Дополнительно**: Чтение книг ("Совершенный код" Макконнелла, "Чистый код" Мартина), участие в тренировках по алгоритмам (CodeWars, LeetCode).  

---

## 🚀 Сейчас изучаю  
- **C++23**:  
  - Корутины для асинхронных операций.  
  - `std::expected` для обработки ошибок (альтернатива исключениям).  
  - Модули C++ (улучшение компиляции и организации кода).  
- **Qt 6+**:  
  - QML для создания динамических интерфейсов.  
  - Интеграция с C++ через сигналы и слоты.  
- **Инструменты**:  
  - **Sanitizers** (Address/UBSan) для отладки.  
  - **gRPC** для межсервисного взаимодействия
- **Архитектура**:  
  - Event-driven микросервисы (Kafka/RabbitMQ для обмена сообщениями).  
  - Контейнеризация: **Docker** для изоляции сервисов.  
- **Дополнительно**:  
  - **gRPC** для межсервисного взаимодействия. 

---

## 💼 Контакты  
**Хотите обсудить проект?**  
- [![Telegram](https://img.shields.io/badge/Telegram-@iZur777-26A5E4)](https://t.me/iZur777)  
- [![Email](https://img.shields.io/badge/Email-realht@gmail.com-D14836)](mailto:realht@gmail.com)  

<!--
**realht/realht** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
