﻿# 
Бомбер c Top. Для большей анонимности рекомендую использовать VPN.
Запускается немного дольше с Тором, но отлично работает, если жалуется на 64 бита вместо 32, то ниже как исправить, переписывать в точно так как написано.

Как правильно установить СНАЧАЛА ПРОПИСЫВАЕМ ВСЕ ЭТО В Termux, а потом уже исправляем проблему с "64 бит"
1) pkg update
2) pkg upgrade
3) pkg install git
4) pkg install tsu
5) pkg install python
6) pkg install python2
7) pkg install openssh
git clone https://github.com/MARK-inc/MincBomb
9) cd MincBomb
10) tsu
11) chmod +x ./tron
12) ./tron

Проблема с 64 бит

$ su

$ which su

$ sh -x su

$ sh -x $(which su)

$ unset LD_PRELOAD
После этого пишем./tron и все должно запуститься. После перезапуска прийдется прописывать заново условие
$ which su
$ sh -x su
$ sh -x $(which su)
$ unset LD_PRELOAD
И только потом можно
1) cd tron
2) ./tron

После запуска можно запустить всё с помощью комманд:
cd
cd MincBomb
./tron
79123456789
3
1
0
- 3 Это режим SMS + Звонок
- 1 Показывать только удачные
- 0 Время в секундах ( Если значение 0 то бесконечно ) разработчик: https://www.youtube.com/channel/UCQoGYRCE1RP5bGNUlRUAVyA?view_as=subscriber