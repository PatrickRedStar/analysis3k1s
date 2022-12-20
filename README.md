# Анализ медицинского датасета
Всем привет! В своем проекте мы хотели рассмотреть набор данных, который посвящен сердечной недостаточности пациентов.

### Video - https://www.youtube.com/watch?v=GuQGhE495WI

## Постановка проблемы
Сердечно-сосудистые заболевания (ССЗ) являются причиной смерти номер 1 во всем мире, унося примерно 17,9 миллиона жизней ежегодно, что составляет 31% всех смертей в мире. Четыре из 5 смертей от сердечно-сосудистых заболеваний связаны с сердечными приступами и инсультами, и одна треть этих смертей происходит преждевременно среди людей в возрасте до 70 лет. Сердечная недостаточность является распространенным явлением, вызванным сердечно-сосудистыми заболеваниями, и этот набор данных содержит 11 признаков, которые можно использовать для прогнозирования возможного заболевания сердца.

Люди с сердечно-сосудистыми заболеваниями или с высоким сердечно-сосудистым риском (из-за наличия одного или нескольких факторов риска, таких как гипертония, диабет, гиперлипидемия или уже установленное заболевание) нуждаются в раннем выявлении и лечении, в чем большую помощь может оказать модель машинного обучения.

Датасет: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/code?datasetId=1582403&searchQuery=py

## Датасет
- Age: возраст пациента [лет]
- Sex: пол пациента [М: Мужской, Ж: Женский]
- ChestPainType: тип боли в груди [TA: типичная стенокардия, ATA: атипичная стенокардия, NAP: неангинальная боль, ASY: бессимптомная]
- RestingBP: артериальное давление в состоянии покоя [мм рт.ст.]
- Cholesterol: холестерин сыворотки [мм/дл]
- FastingBS: уровень сахара в крови натощак [1: если FastingBS > 120 мг/дл, 0: иначе]
- RestingECG: результаты электрокардиограммы в покое [норма: нормальная, ST: аномалия ST-T (инверсия зубца T и/или подъем или депрессия ST > 0,05 мВ), ГЛЖ: вероятная или определенная гипертрофия левого желудочка по критериям Эстеса]
- MaxHR: максимальная достигнутая частота сердечных сокращений [Числовое значение от 60 до 202]
- ExerciseAngina: [Д: Да, Н: Нет]
- Oldpeak: старый пик = ST [Числовое значение, измеренное в депрессии]
- ST_Slope: наклон сегмента ST пикового упражнения [Вверх: восходящий, Плоский: плоский, Вниз: нисходящий]
- HeartDisease: выходной класс [1: болезнь сердца, 0: нормальный]

## Результат

<img width="741" alt="Снимок экрана 2022-12-20 в 19 41 30" src="https://user-images.githubusercontent.com/82098533/208719617-8e25fd8c-76f6-4f52-b380-2e5ac573c366.png">

## Выполнили:
- Куркин Пётр 11-007
- Бронников Родион 11-007 
