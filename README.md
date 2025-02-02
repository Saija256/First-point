# First-point
## Открытие портов
### В зависимости от того, включён ли брандмауэр, осуществляется выбор алгоритма открытия портов. Чтобы не заниматься выбором вручную, был создан этот скрипт, принимающий в качестве аргументов один или несколько портов.

⠀### Синтаксис
```
. <(wget -qO- https://raw.githubusercontent.com/SecorD0/utils/main/miscellaneous/ports_opening.sh) \
порт_1 порт_2 порт_3 ...
```
###Примеры
```
. <(wget -qO- https://raw.githubusercontent.com/SecorD0/utils/main/miscellaneous/ports_opening.sh) \
9090 9091
```
