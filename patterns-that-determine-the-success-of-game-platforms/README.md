# Описание проекта
Используя исторические данные о продажах компьютерных игр, рейтинги пользователей и экспертов, жанры и платформы, выявим закономерности, определяющие успех игры.

Интернет-магазин продает компьютерные игры по всему миру. Исторические данные о продажах игр, рейтингах пользователей и экспертов, жанрах и платформах доступны из открытых источников. Выявлены параметры, определяющие успех игры в разных регионах мира. Определен потенциально популярный продукт и запланированы рекламные кампании. Выбран текущий период для анализа. Были составлены портреты пользователей каждого региона. Проверяемые гипотезы: средние оценки пользователей для платформ Xbox One и ПК одинаковы; средние оценки пользователей для жанров «Боевик» и «Спорт» различаются.

## Описание данных
- `Name` — название игры
- `Platform` — платформа
- `Year_of_Release` — год выпуска
- `Genre` — жанр игры
- `NA_sales` — продажи в Северной Америке (миллионы проданных копий)
- `EU_sales` — продажи в Европе (миллионы проданных копий)
- `JP_sales` — продажи в Японии (миллионы проданных копий)
- `Other_sales` — продажи в других странах (миллионы проданных копий)
- `Critic_Score` — оценка критиков (максимум 100)
- `User_Score` — оценка пользователей (максимум 10)
- `Rating` — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Навыки и инструменты
- python
- pandas
- numpy
- statistics
- re
- seaborn
- scipy
  - pearsonr
  - stats
