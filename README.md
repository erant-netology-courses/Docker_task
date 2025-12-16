## Задача 0

Docker-compose нет. На первых темах модуля разбирался в чем разница и в нюансах
<img width="693" height="900" alt="image" src="https://github.com/user-attachments/assets/ae458a6d-cfba-4fac-9917-b5bfb1a62af0" />

## Задача 1

1. https://github.com/erant-netology-courses/shvirtd-example-python
2. Проверка билда

<img width="900" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/1_checked-build.JPG" />
   
3. Поднял бд для раздельного запуска  
<img width="1200" height="1200" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/1_installed-mysql.JPG" />
Запустил приложение без докера по гайду
<img width="1200" height="1200" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/1_no-docker-start.JPG" />

4. Управляю таблицей в бд через переменную окружения
<img width="1200" height="1200" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/1_specified-table-name-via-env.JPG" />


## Задача 2
Отчет сканирования - https://github.com/erant-netology-courses/Docker_task/blob/main/2_report.csv

## Задача 3
Скриншот запроса после подключения в бд 
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/3.JPG" />

## Задача 4
Скриншот где бд с данными, после теста
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/4.JPG" />

Зачем то подключился к сокету и потом к докеру на сервере
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/4_5.JPG" />

## Задача 5
Очень хотелось с помощью другого образа сделать бекап, но в итоге:
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/5.JPG" />

## Задача 6
Тут я потратил 2 суток.
Дайв образа терраформа:
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/6_dive.JPG" />

Запуск одних и тех же команд на локальной винде и на ВМ в YC с убунту.
<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/6_done.JPG" />

История:
Я начал делать на локальной машине с виндой (как в ТЗ), но у меня отличались хэши в dive от хэшей в архиве.
Когда я сделал все то же самое на ВМ в YC, хэши совпадали. Оказывается, хоть докер и запускается на WSL, но архивы образов для винды и убунты разные.
Хочу узнать информацию про это, я думал я сошел с ума или не так понял как "залезать" в образ.

<img width="693" height="900" alt="image" src="https://github.com/erant-netology-courses/Docker_task/blob/main/6_different-digests.JPG" />


## Задача 6.1
Через docker cp вытащил файл

<img width="1512" height="257" alt="image" src="https://github.com/user-attachments/assets/3f4a1dff-8cb4-4e8a-8708-336de902c88e" />

## Задача 6.2
Через build вытащил файл

https://github.com/erant-netology-courses/Docker_task/blob/main/6_2.JPG


