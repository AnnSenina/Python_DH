# Python_DH

Сюда буду выкладывать все материалы для курса повышения квалификации [**"Введение в Python для Digital Humanities"**](https://www.hse.ru/edu/dpo/473204831)

Канал в [телеграме](https://t.me/pythonhse)

Постоянная [ссылка](https://teams.microsoft.com/l/meetup-join/19%3aX-fzX3OBi0y4JXkeqiIdlxMGbh0pc_4LJuy0AKLitIw1%40thread.tacv2/1652513895774?context=%7b%22Tid%22%3a%2221f26c24-0793-4b07-a73d-563cd2ec235f%22%2c%22Oid%22%3a%226c586e17-eb16-4201-bc5d-f272a52a09cd%22%7d) в MS Teams на встречи

# Программа курса: 
1. Установка Git и Python
2. Переменные, операторы, простые типы данных + операторы ввода/вывода
3. Типы данных посложнее: список, кортеж, множество, словарь
4. Условия+Циклы
5. Функции
6. Регулярные выражения
7. Работа с файлами: модуль OS
8. Краулеры+парсеры+скрейперы
9. Основные библиотеки питона для DH-задач

Расписание курса [здесь](https://github.com/AnnSenina/Python_DH/blob/main/Расписание%20курса)

## Встреча 1. Установка Git и Python 16.05.2022
[Презентация](https://www.canva.com/design/DAE884hS7do/wmu1YZ3ahhPch0hxOfxhug/view?utm_content=DAE884hS7do&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton), [pdf](https://github.com/AnnSenina/Python_DH/blob/main/Python%20%D0%B4%D0%BB%D1%8F%20DH.pdf)  
[Google Colaboratory](https://colab.research.google.com/?hl=ru-RU)  
[GitHub](https://github.com/AnnSenina/Python_DH)  

[Блокнот](https://colab.research.google.com/drive/1skt9dR_kvHJ7ePZjy61pZgFMBIooQvlv?usp=sharing) встречи 1 от 16.05.2022  
[Запись](https://eduhseru.sharepoint.com/sites/DataCulture/Shared%20Documents/%D0%98%D0%A1%D0%A2%D0%A0_1_3/Recordings/%D0%A1%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80%D1%8B%201%20%D0%BA%D1%83%D1%80%D1%81%201_3-20220514_130942-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D1%8F.mp4?web=1) встречи 1  

Домашнее задание:
1. Зарегистрировать аккаунт в Google ИЛИ установить [Anaconda](https://www.anaconda.com) #рекомендую Google
2. Зарегистрироваться на [GitHub](https://github.com/AnnSenina/Python_DH)
3. Установить [Git](https://git-scm.com/downloads)

Чтобы установить Git:  
- Windows - [скачать](https://git-scm.com/download/win), выбрав версию (32/64-разрядная система), установить как обычную программу (не менять никакие настройки про установке)  
- MacOS -  
если есть [homebrew](https://brew.sh): $ brew install git  
если нет, [ссылка](https://git-scm.com/download/mac), выбираем вариант **Binary installer**  
- Linux - команду в терминале для вашего дистрибутива со [страницы](https://git-scm.com/download/linux)  

## Встреча 2. Переменные, операторы, простые типы данных + операторы ввода/вывода
[Блокнот](https://colab.research.google.com/drive/1OHTTz8-7dvoZH21eeO2rwcRe53qTmzBw?usp=sharing) встречи 2 от 20.05.2022  
[Запись](https://eduhseru.sharepoint.com/sites/PythonDigitalHumanities/Shared%20Documents/General/Recordings/General-20220520_210001-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D1%8F.mp4?web=1) встречи 2  
Домашнее задание 1:
[Блокнот](https://colab.research.google.com/drive/14IlLXbowiEGT5X9npAdjjmfyCfOtWw_P?usp=sharing)  
скопируйте блокнот себе на диск перед тем, как начать решать. Для этого нажимаем:  
**Файл - сохранить копию на Диске**  
После решения задач отправьте мне доступ к вашему блокноту: справа вверху:  
**Поделиться - можно вписать мою почту ann.sotn@gmail.com**

## Встреча 3. Типы данных посложнее: список, кортеж, множество, словарь
[Презентация](https://www.canva.com/design/DAEqhovLdtY/oA_GuwdhHx5aWREeQXHoQQ/view?utm_content=DAEqhovLdtY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton), [pdf](https://github.com/AnnSenina/Python_DH/blob/main/Python.%20%D0%9C%D0%B5%D1%82%D0%BE%D0%B4%D1%8B%2C%20%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B0%2C%20%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%B8.pdf)  
[Блокнот](https://colab.research.google.com/drive/1EO-njZvfecVFf2UZsAcKONYXrvzU1tB3?usp=sharing) встречи 3 от 23.05.2022  
[Запись](https://eduhseru.sharepoint.com/sites/PythonDigitalHumanities/Shared%20Documents/General/Recordings/General-20220523_205928-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D1%8F.mp4?web=1) встречи 3  
Домашнее задание 2: Яндекс, по [ссылке](https://contest.yandex.ru/contest/38104/enter/)  
**UPD**: Добавила открытые тесты, теперь хорошо видно, что задача получает на вход и какой ответ должен получиться  

## Встреча 4. Условия+Циклы
[Презентация в pdf](https://github.com/AnnSenina/Python_DH/blob/main/%D0%A3%D1%81%D0%BB%D0%BE%D0%B2%D0%B8%D1%8F%2C%20%D1%86%D0%B8%D0%BA%D0%BB%D1%8B.pdf)  
[Блокнот](https://colab.research.google.com/drive/1h2p36jsxp5wVNWCk_XW_r-0mSk_FwZ8k?usp=sharing) встречи 4 от 27.05.2022  
[Запись](https://eduhseru.sharepoint.com/sites/PythonDigitalHumanities/Shared%20Documents/General/Recordings/General-20220527_205850-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D1%8F.mp4?web=1) встречи 4  
[Домашнее задание 3](https://contest.yandex.ru/contest/38215/enter/)
  
[Решение домашней работы_1](https://colab.research.google.com/drive/14IlLXbowiEGT5X9npAdjjmfyCfOtWw_P?usp=sharing)  
[Решение домашней работы_2](https://colab.research.google.com/drive/1Mod07QDV2xwSbnS8GYyVSQsRYcuFkdcN?usp=sharing)  
  
Разница между датами в днях: [блокнот](https://colab.research.google.com/drive/1OfiD0T1I9Elf1fract2iFKFY20Zmmja3?usp=sharing), автор - Никита Маткин  
Игра на Хэллоуин: [блокнот](https://colab.research.google.com/drive/1Vdy6qQPbww8_4mTTqSEz3G4aXfMFeemh?usp=sharing), автор - Анастасия Михайлова  

## Встреча 5. Функции (+ сортировки)
[Блокнот](https://colab.research.google.com/drive/16p2WjzLgpVkW87rbEJLtfyhMFevMrwm_?usp=sharing) встречи 5 от 30.05.2022  
[Запись](https://eduhseru.sharepoint.com/sites/PythonDigitalHumanities/Shared%20Documents/General/Recordings/%D0%A1%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B2%20%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB%D0%B5%20_%D0%9E%D0%B1%D1%89%D0%B8%D0%B9_-20220530_210033-%D0%97%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%B8%D1%8F.mp4?web=1) встречи 5

Разница между датами в днях: [Time+def](https://colab.research.google.com/drive/1pe2gyNPFL7L6P0q-bUC59h5ZKEMaImX9?usp=sharing) - сокращение программы Никиты Маткина

## Встреча 6. Регулярные выражения
[Презентация](https://docs.google.com/presentation/d/19FWFu710o5uvefMZCaLn5eux03Cul-MWeP9QDmB5HFI/edit?usp=sharing), [pdf](https://github.com/AnnSenina/Python_DH/blob/main/Python%20%26%20DH%2C%20%D1%80%D0%B5%D0%B3%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D1%8B%D0%B5%20%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F.pdf)  
[Блокнот](https://colab.research.google.com/drive/1pBWIV8pjyvEIIPTe8sRntUr7FQt-ZAoY?usp=sharing) встречи 5 от 03.06.2022  
[Запись](https://eduhseru.sharepoint.com/sites/PythonDigitalHumanities/Shared%20Documents/General/Recordings/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20Python_20220603_160158.mp4?web=1) встречи 5  
В презентации используются материалы Даниила Скоринкина, в блокноте - Татьяны Рогович (НИУ ВШЭ)  
  
[Решение домашней работы 3](https://colab.research.google.com/drive/1kivtKRfZ842mkyQbbRXlPPn6uFc7bL6g?usp=sharing)  
Примеры решения дополнительных сложных задач по [функциям](https://colab.research.google.com/drive/1V1SnDK6qUkX02v38K2hvkUzk6E18E6pZ?usp=sharing)  
Подробный разбор [задачи 1](https://colab.research.google.com/drive/1ERuiK3ld1vLCtW05kKNr6w64mkPEoSnF?usp=sharing) из домашней работы 2  

