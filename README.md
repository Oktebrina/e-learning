# e-learning

Проект e-learning (анализ данных для площадки с онлайн образованием) 

Для анализа использован язык #python

Данные собираются в 4 таблицы:

assessments.csv  - информация об оценках в тесте. 
courses.csv — список предметов по семестрам.
studentAssessment.csv — результаты тестов студентов. 
studentRegistration.csv — информация о времени, когда студент зарегистрировался для прохождения курса в семестре.
courses.csv — список предметов по семестрам.

Поставленные задачи:

1. Сколько студентов успешно сдали только один курс? (Успешная сдача — это зачёт по курсу на экзамене)

2. Выявить самый сложный и самый простой экзамен: найти курсы и экзамены в рамках курса, которые обладают самой низкой и самой высокой завершаемостью.

3. По каждому предмету определить средний срок сдачи экзаменов (под сдачей понимаем последнее успешное прохождение экзамена студентом).

4. Выявить самые популярные курсы (ТОП-3) по количеству регистраций на них. А также курсы с самым большим оттоком (ТОП-3).

5. Построить когортный (семестровый) анализ. В период с начала 2013 по конец 2014 выявить семестр с самой низкой завершаемостью курсов и самыми долгими средними сроками сдачи курсов.

6. Используя python, построить адаптированные RFM-кластеры студентов, чтобы качественно оценить свою аудиторию. Для каждого RFM-сегмента построить границы метрик recency, frequency и monetary для интерпретации этих кластеров. 
