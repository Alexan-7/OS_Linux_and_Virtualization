Система Ubu2 - на большом компьютере
Имя Sashux
Имя комп-ра Compux
Пароль 0

____________________________________
-ssh Sashux@10.0.2.4 - через консоль Windows подключиться к виртуальной машине - ЭТО ДЛЯ СЕТЕВОГО РЕЖИМА "МОСТ" BRIDGE, А НЕ ДЛЯ БЕСПРОВОДНОГО АДАПТЕРА!
----------------------------------------


ssh -p 8022 sashux@localhost - через консоль Windows подключиться к виртуальной машине - ДЛЯ БЕСПРОВОДНОГО АДАПТЕРА

На другой день "sashux@localhost's password:
Welcome to Ubuntu 22.04.3 LTS" - УРА!

команда "mc" - файловый менеджер Линукса (Midnight Commander)

Адрес iPv4 при беспров. подключ-я - 10.0.2.15

sudo apt update - проверить, все ли в порядке с сетью

sudo apt install gcc make perl openssh-server mc - установка гостевых пакетов

systemstl status ssh - установлен ли ssh-сервер

sudo ss -ntlp