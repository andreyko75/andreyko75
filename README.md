# Привет! 👋 Я Андрей

Работаю с современными технологиями искусственного интеллекта, автоматизации и анализа данных. 
Этот репозиторий — подборка учебных и прикладных проектов, в которых я проектирую и применяю AI-решения на практике.

---

## 🚀 Чем занимаюсь сейчас

- Разработка Telegram-ботов с AI-интеграцией (aiogram + OpenAI API)
- Проектирование и разработка LLM-приложений и цепочек через LangChain
- Применение и тестирование техник промпт-инжиниринга (Zero-Shot, Few-Shot, CoT, CoV)
- Автоматизация рабочих процессов через n8n и API-интеграции
- Построение RAG-систем для поиска, анализа и обогащения данных
- Развёртывание и сопровождение VDS-серверов (Linux Ubuntu, Nginx, SSL)
- Работа с мультимодальными моделями: изображения, документы, голос, структурированные данные
- Построение мультимодальных пайплайнов (Vision → JSON → Text → Audio)

---

## 🛠 Технологии и инструменты

_Стеки всех репозиториев портфолио_

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-2C2C2C?logo=langchain&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2C2C2C?logo=telegram&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-4D4D4D?logo=weaviate&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B00?logo=chroma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-2C2C2C)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?logo=qt&logoColor=white)
![PyInstaller](https://img.shields.io/badge/PyInstaller-404040)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white)
![Typer](https://img.shields.io/badge/Typer-CLI-378BA3)
![requests](https://img.shields.io/badge/requests-2496ED)
![python-dotenv](https://img.shields.io/badge/python--dotenv-3776AB?logo=python&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?logo=python&logoColor=white)
![MoviePy](https://img.shields.io/badge/MoviePy-FF0000)
![tqdm](https://img.shields.io/badge/tqdm-FFD700)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?logo=openai&logoColor=white)
![DALL·E](https://img.shields.io/badge/DALL·E-412991?logo=openai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-2C2C2C)
![FusionBrain](https://img.shields.io/badge/FusionBrain_Kandinsky-FF6B00)
![NewsAPI](https://img.shields.io/badge/NewsAPI-6BA539)
![Pixabay](https://img.shields.io/badge/Pixabay-2C2C2C)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B62?logo=n8n&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white)

---

## 🤖 AI-модели и направления

**Текст и логика:** 
ChatGPT · GPT-4.1 · GPT-4o · LangChain · RAG

**Компьютерное зрение (Vision):** 
GPT Vision · анализ изображений и документов · извлечение структурированных данных

**Голос:** 
Text-to-Speech (TTS) · Speech-to-Text (STT) · генерация и транскрибация аудио

**Изображения и визуал:** 
DALL·E · генерация иллюстраций и визуальных концептов

**Мультимодальность:** 
Связки Image → JSON → Text → Audio 
Комплексные сценарии обработки данных через несколько моделей

---

## 📂 Проекты

_В репозитории представлены выборочные проекты из моей практики_

| Проект | Описание | Стек |
|------|----------|------|
| [RAG-assist](https://github.com/andreyko75/RAG-assist) | RAG-ассистент с векторной базой Weaviate на VDS и генерацией ответов через OpenAI API. Отвечает на вопросы по загруженным документам, использует кеш (SQLite) и поддерживает оценку качества через RAGAS (Faithfulness, Context Precision). | Python, OpenAI API, Weaviate, SQLite, RAGAS |
| [elf_lang](https://github.com/andreyko75/elf_lang) | Экспериментальный проект по созданию искусственного языка (DSL) для взаимодействия с LLM. Исследуется идея промежуточного «языка мышления» между человеком и моделью: формализация намерений, структурирование смысла, контроль интерпретаций и снижение неоднозначности промптов. Проект носит исследовательский характер и направлен на углублённое понимание логики работы LLM. | Python, Prompt Engineering, LLM |
| [comp_analis](https://github.com/andreyko75/comp_analis) | Мультимодальный ассистент для анализа конкурентов. Поддерживает анализ текста, изображений и веб-сайтов (URL) с использованием GPT-4o. Реализован полный end-to-end пайплайн: Web UI (FastAPI) + нативное desktop-приложение для macOS (PyQt6). Включает Selenium-парсинг сайтов, строгие JSON-контракты ответов, историю запросов и REST API для интеграций. | Python, FastAPI, OpenAI API (GPT-4o, Vision), Selenium, PyQt6, PyInstaller |
| [recept_info](https://github.com/andreyko75/recept_info) | Мультимодальный кулинарный ассистент (CLI + Flask). Принимает изображение блюда или аудиофайл с голосовым описанием, автоматически определяет блюдо, генерирует классический рецепт и создаёт реалистичное изображение блюда. Реализован полный мультимодальный пайплайн с выделенной бизнес-логикой и двумя интерфейсами. | Python, Flask, OpenAI API (GPT-4.1, Vision, Whisper, DALL·E 2), DeepSeek |
| [analize_stamp](https://github.com/andreyko75/analize_stamp) | Мультимодальный анализ почтовых марок: GPT Vision для анализа изображений → структурированный JSON → генерация связного текстового и голосового описания (TTS). Проект демонстрирует полный мультимодальный пайплайн и контроль ограничений анализа. | Python, OpenAI API (GPT-4.1 Vision, TTS), JSON |
| [tgbot_OpanAI_assist](https://github.com/andreyko75/tgbot_OpanAI_assist) | Telegram-бот с использованием OpenAI Assistants API. Отдельный контекст для каждого пользователя, асинхронная обработка сообщений. | Python, aiogram, OpenAI API |
| [pf_covenants_checker](https://github.com/andreyko75/pf_covenants_checker) | Проверка банковских ковенантов (LTV, LLCR, DSCR). Используются LangChain и техники промпт-инжиниринга. | Python, LangChain, OpenAI API |
| [ChatGPT_Assistant_FSO](https://github.com/andreyko75/ChatGPT_Assistant_FSO) | Генерация тестов по ФСО с использованием OpenAI Responses API и специализированных промптов. | Python, OpenAI API |
| [fusionbrain_api](https://github.com/andreyko75/fusionbrain_api) | Генерация изображений через FusionBrain (Kandinsky). Веб-интерфейс. | Python, Flask |
| [pixabay_api](https://github.com/andreyko75/pixabay_api) | Автоматическая сборка видеороликов из материалов Pixabay. | Python, MoviePy |
| [api_news_learn](https://github.com/andreyko75/api_news_learn) | Консольный инструмент для работы с NewsAPI. | Python, requests |

---

## 🎯 Цель репозитория

Собрать **портфолио прикладных и учебных проектов**, отражающих реальный подход к работе с:

- LLM и промпт-инжинирингом,
- GPT Vision и мультимодальными моделями,
- Text-to-Speech / Speech-to-Text,
- автоматизацией и интеграцией AI в практические сценарии.

---

## 📬 Контакты

- Email: [andreyko75@gmail.com](mailto:andreyko75@gmail.com)
- Telegram: [@hunter_xv](https://t.me/hunter_xv)
- GitHub: [andreyko75](https://github.com/andreyko75)

---

_Интерес, системность и практика — ключевые инструменты._
