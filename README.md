# 🌍 Многоязычный генератор ников

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Languages](https://img.shields.io/badge/🌐_Языки-10_языков-blue)
![Version](https://img.shields.io/badge/Версия-2.0-brightgreen)

> **Генератор случайных ников** с поддержкой 10 языков, плавным UI, настройкой длины и символов. Идеально для игр, соцсетей и форумов!

---

## 🎯 Демо

🔗 [Запустить генератор](https://твой-ник.github.io/nickname-generator) — (ссылка появится после публикации на GitHub Pages)

---

## 📸 Превью

<img width="2560" height="1600" alt="Скриншот генератора ников" src="https://github.com/user-attachments/assets/0eafc93e-7930-4c70-99e0-8ef293b6c9e0" />

*Элегантный интерфейс с тёмным переключателем и 8 ника за генерацию*

---

## ✨ Особенности

| Функция | Описание |
|---------|----------|
| 🌍 **10 языков** | Русский, английский, белорусский, украинский, казахский, французский, испанский, японский, немецкий, итальянский |
| 🎲 **Случайная генерация** | 8 уникальных ников за один клик |
| 📏 **Настройка длины** | От 2 до 18 символов (мин./макс. длина) |
| ✨ **Гибкие символы** | Можно включить/выключить добавление цифр, знаков (_ . -) |
| 💡 **Клик + копирование** | Нажми на любой ник — он скопируется в буфер |
| 🎨 **Адаптивный дизайн** | Красиво работает на телефонах, планшетах и ПК |
| ⚡ **Анимации** | Плавное появление ников и hover-эффекты |

---

## 🗂️ Список поддерживаемых языков

| Флаг | Язык | Код |
|------|------|-----|
| 🇬🇧 | English | `english` |
| 🇷🇺 | Русский | `russian` |
| 🇧🇾 | Беларуская | `belarusian` |
| 🇺🇦 | Українська | `ukrainian` |
| 🇰🇿 | Қазақша | `kazakh` |
| 🇫🇷 | Français | `french` |
| 🇪🇸 | Español | `spanish` |
| 🇯🇵 | 日本語 | `japanese` |
| 🇩🇪 | Deutsch | `german` |
| 🇮🇹 | Italiano | `italian` |

---

## 🧠 Как это работает

Генератор использует **слоговый метод** — для каждого языка заданы:

- **набор слогов** (`ar`, `el`, `an`...)
- **окончания** (`a`, `e`, `ing`...)
- **специальные символы** (можно включать/выключать)

Алгоритм собирает ник из слогов, подгоняет под выбранную длину, добавляет символы и капитализирует первую букву. Результат — **звучные, читаемые ники**, похожие на реальные имена или логины.

---

## 🚀 Быстрый старт

### Локальный запуск

```bash
git clone https://github.com/твой-профиль/nickname-generator.git
cd nickname-generator
# Открой файл index.html в любом браузере
