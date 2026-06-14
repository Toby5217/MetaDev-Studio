# 🚀 MetaDev Studio (Beta 1)

**AI‑powered application builder** — команда ИИ‑агентов, которая пишет код за вас.  
Локально, без интернета, на базе ваших собственных моделей.

![License](https://img.shields.io/badge/license-Proprietary-red)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2B-blue)
![Version](https://img.shields.io/badge/version-1.0.0--beta-brightgreen)

---

## 🧠 Что такое MetaDev Studio?

**MetaDev Studio** — автономная студия разработки, состоящая из нескольких
специализированных ИИ‑агентов. Каждый агент — это **отдельная модель**,
обученная под свою роль:

| Агент | Роль | Модель |
|-------|------|--------|
| 🎯 **Director** | Планирует проект, разбивает задачи | `mitrai-director.gguf` |
| 💻 **Developer** | Генерирует готовый код (HTML/CSS/JS, Python) | `mitrai-developer.gguf` |
| 📦 **Integrator** | Собирает файлы в структуру проекта | `mitrai-integrator.gguf` |
| 🔍 **Tester** | Проверяет код на ошибки и уязвимости | `mitrai-tester.gguf` |
| 🔧 **Fixer** | Исправляет JSON‑ответы и структуру | `mitrai-fixer.gguf` |
| 📋 **Supervisor** | Ведёт подробный лог всей работы | `mitrai-supervisor.gguf` |

Вы вводите описание приложения — агенты создают папку с полностью рабочим проектом.

---

## ⚡ Быстрый старт

### 📋 Системные требования
- **Windows 10/11** (x64)
- **Python 3.12** (включён в сборку)
- **8 ГБ ОЗУ** для 7B‑моделей, **16 ГБ** для 14B
- **2 ГБ свободного места** на диске
- Видеокарта **не обязательна** — всё работает на CPU

### 📦 Установка
1. Скачайте последний релиз **MetaDev‑Studio‑Beta1.zip** со страницы [Releases]().
2. Распакуйте архив в любую папку, например `D:\metadev_studio`.
3. Готово! Никакие зависимости не требуются.

### 🚀 Первый запуск
```powershell
cd D:\metadev_studio
MetaDev.exe "Калькулятор на HTML/CSS/JS с тёмной темой"