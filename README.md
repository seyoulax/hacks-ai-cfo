<div align=center><img src=https://i.otzovik.com/objects/b/1940000/1931091.png align=center width=150 margin=0/></div><h1 align=center>Решение кейса "Анализатор обратной связи студентов" в рамках хакатона Цифровой прорыв</h1>

### *Описание кейса:*
- В рамках кейса было необходимо автоматизировать анализ отзывов студентов на курсы от компании ***GeekBrains***

### *Описание решения:*
- Мы предлагаем высокотехнологичное решение для анализа отзывов студентов, а так же интерпретируемые визуализации на web-сайте. Наше решение использует модели *LLM*, что позволяет нам добиться хороших рекомендаций по улучшению пользовательского опыта. Реализован *веб интерфейс* и *телеграм бот* с обширным функционалом
- В стеке используемых технологий присутствует модель LLM: **Saiga-Mistral-7B**, **RuBert**, сайт написан на **FastAPI+Vue.js**, что позволяет *легко его масштабировать*
- Уникальность нашего решения заключается в **разнобразии визуализаций**, например с аспектами недовольства/удовлетворения юзера, что позволяет наиболее точно принимать решение по изменению вебинаров

### *Структура репозитория:*

1. */inference* - папка с кодом инференса для моделей **LLM, RuBert, SPAN-ASTE, Emotional-Bert**. Также здесь **класстеризация отзывов** и **отдельных вопросов из них**
2. */triplets* - папка анализом **триплетов, построением графиков и кластеразацией аспектов/мнений/аспектов+мнений**
   
