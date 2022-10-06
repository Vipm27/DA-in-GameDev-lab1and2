# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил(а):
- Анофриев Данил Сергеевич
- ХПИ31
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Познакомиться с программными средствами для организции
передачи данных между инструментами google, Python и Unity 

## Задание 1
### Реализовать совместную работу и передачу данных в связке Python
- Google-Sheets – Unity. При выполнении задания используйте видео-материалы и
исходные данные, предоставленные преподавателя курса.
- В облачном сервисе google console подключить API для работы с google
sheets и google drive.
- Реализовать запись данных из скрипта на python в google-таблицу. Данные
описывают изменение темпа инфляции на протяжении 11 отсчётных периодов, с
учётом стоимости игрового объекта в каждый период.
- Создать новый проект на Unity, который будет получать данные из google-
таблицы, в которую были записаны данные в предыдущем пункте.
- Написать функционал на Unity, в котором будет воспризводиться аудио-
файл в зависимости от значения данных из таблицы.

Написал код, который заполняет таблицу гугл. После этого написал код, связанный с анализом этих данных и выводом определенных звуков

![2022-10-05_20-02-34](https://user-images.githubusercontent.com/86101819/194269399-aa15a398-3342-4b9e-8d6b-89257eb6a854.png)
![2022-10-05_20-02-30](https://user-images.githubusercontent.com/86101819/194269413-81ea9dfe-b089-4bfd-aeb8-5e363307a89c.png)
![2022-10-05_20-02-25](https://user-images.githubusercontent.com/86101819/194269419-dcf4dfa3-436b-4df6-aa67-d4816c066bd7.png)
![2022-10-05_19-38-42](https://user-images.githubusercontent.com/86101819/194269421-83fe308f-48c7-420e-9502-d9631b2d9682.png)
![2022-10-05_19-38-31](https://user-images.githubusercontent.com/86101819/194269427-36e262ac-64c9-425c-9641-cd950b833e5f.png)
![2022-10-05_20-02-41](https://user-images.githubusercontent.com/86101819/194269432-3239c440-5d8c-404c-afaa-0bb685d66840.png)
![2022-10-05_20-02-38](https://user-images.githubusercontent.com/86101819/194269439-c9797b53-8182-4f49-a5f1-914cca13650c.png)
![2022-10-06_11-51-26](https://user-images.githubusercontent.com/86101819/194269488-e18366d5-683d-4800-a56e-4a4791462a21.png)


## Задание 2
### Реализовать запись в Google-таблицу набора данных, полученных
с помощью линейной регрессии из лабораторной работы № 1

Интегрировал линейную регрессию, отредактировал код, протестил, все работает
![2022-10-05_20-38-16](https://user-images.githubusercontent.com/86101819/194270586-e5a5ba36-eb8d-48dd-880c-485c556b5145.png)
![2022-10-05_20-38-09](https://user-images.githubusercontent.com/86101819/194270593-be252d83-d34d-4d8c-8a6d-f145c29224b9.png)
![2022-10-05_20-38-24](https://user-images.githubusercontent.com/86101819/194270599-ac2f564b-2982-412f-a037-1e3b66aa9e73.png)
![2022-10-05_20-38-20](https://user-images.githubusercontent.com/86101819/194270571-eaf066b6-ad1e-4b95-a651-9a002e6dc0dd.png)
![2022-10-05_20-39-39](https://user-images.githubusercontent.com/86101819/194271297-05ac77a4-8abc-4a5a-92ae-c37183b9c828.png)


## Задание 3
### Самостоятельно разработать сценарий воспроизведения звукового
сопровождения в Unity в зависимости от изменения считанных данных в задании 2

Подправил код под линейную регрессию, проверил, звук выводится корректно
![2022-10-05_20-38-52](https://user-images.githubusercontent.com/86101819/194271482-b34d1a49-ac3e-4a2f-8dcc-3d1a1fd91147.png)
![2022-10-05_20-38-48](https://user-images.githubusercontent.com/86101819/194271493-420c290c-0377-4e0a-aeec-285a8ef3b7fa.png)
![2022-10-05_20-38-44](https://user-images.githubusercontent.com/86101819/194271498-d59cafde-2913-432b-ae82-852c9cfc4410.png)
![2022-10-05_20-38-56](https://user-images.githubusercontent.com/86101819/194271502-4fdc470c-bc79-43f5-9cfe-d9a1e5884231.png)
![2022-10-05_20-39-58](https://user-images.githubusercontent.com/86101819/194271534-d3020839-038a-4690-a142-bc66d47c5743.png)


## Выводы

Я смог разобраться, как заполнять гугл таблицу при помощи Python. Кроме того, смог подвязать это к Unity и организовать звуковую реакцию взависимости от этих значений в этой гугл таблице. Работа мне очень понравилась, особенно подвзяка линейной регрессии к этому всему. Пока код не совсем понимаю, но результат интересный

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
