# Домашнее задание к занятию «Резервное копирование» - `Костюк Денис`

### Задание 1
#### •	Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup
#### •	Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)
#### •	Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.
#### •	На проверку направить скриншот с командой и результатом ее выполнения

Исходное состояние домашней директории:
![Скрин1](https://github.com/denniskostyuk/rsync/blob/main/task_11.png)

Делаем копирование:
![Скрин2](https://github.com/denniskostyuk/rsync/blob/main/task_12.png)
   
Состояние целевой директории (с бэкапом):
![Скрин3](https://github.com/denniskostyuk/rsync/blob/main/task_13.png)


### Задание 2
#### •	Запустите три simple python сервера на своей виртуальной машине на разных портах
![Скрин6](https://github.com/denniskostyuk/balans/blob/main/task_21.png)
![Скрин7](https://github.com/denniskostyuk/balans/blob/main/task_22.png)
![Скрин8](https://github.com/denniskostyuk/balans/blob/main/task_23.png)
#### •	Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
#### •	HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
#### •	На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
![Скрин9](https://github.com/denniskostyuk/balans/blob/main/task_24.png)
![Скрин10](https://github.com/denniskostyuk/balans/blob/main/task_25.png)
![Скрин11](https://github.com/denniskostyuk/balans/blob/main/task_26.png)
