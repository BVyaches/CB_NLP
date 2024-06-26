# Классификатор пресс-релизов ЦБ с предсказанием будущей ключевой ставки

Этот проект разработан для автоматического анализа пресс-релизов Центрального банка (ЦБ) с целью предсказания изменений в ключевой ставке на следующем заседании. Используя методы анализа семантики текста и машинного обучения, классификатор определяет по последнему пресс-релизу ЦБ, что наиболее вероятно произойдет с ключевой ставкой: она будет повышена, понижена, или останется неизменной.

**data_parsing.py**: файл, содержащий методы, необходимые для чтения данных с сайта ЦБ и добавления текста последнего пресс-релиза

**model.py**: файл, содержащий модель **CatModel**, используемую в веб-приложении

**main.py**: веб-приложение с использованием библиотеки Streamlit.

**requirements.txt**: файл с указанием всех зависимостей, необходимых для работы проекта


## Пакет data

 В этом пакете содержится файл **dataset.csv** с текстами пресс-релизов и таргетами.

## Пакет model_data

В этом пакете содержится сериализованный объект TF-IDF векторизатора и сериализованная модель классификатора

## Пакет ntb

В этом  пакете содержатся файлы Jupyter Notebook с кодом для парсинга, предобработки данных, обучения и тестирования модели классификатора.



## Авторы

Большагин Вячеслав Сергеевич, @BVyaches

Васина Дарья Анатольевна, @daria_vasina

Карпович Лидия Александровна, @lidakarpovich

Шамьюнов Камиль Маратович, @xhcxggxx

## Лицензия

[License](https://github.com/BVyaches/CB_NLP/blob/main/LICENSE)
