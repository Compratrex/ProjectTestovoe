# ProjectTestovoe

## Развертывание
Чтобы развернуть приложение и сервер нужно сначала либо склонировать проект, либо скачать через кнопку code zip файл.

Если клонируем (Самый простой способ):
```
git clone https://github.com/Compratrex/ProjectTestovoe
```

Далее, нужно распаковать все что имеет .zip расширение в ту же папку, где находится.

Чтобы запустить сервер необходимо иметь питон 3й и выше.
### Запуск сервера
Необходимо открыть терминал в директории, где лежит socket_server.py и далее запустить команду:
```
python3 socket_server.py
```
Сервер - ждет подключений, поэтому перейдем к клиенту

### Запуск клиента
Чтобы запустить клиент необходимо перейти в папку с клиентом (game->sfml-app)
В терминале данной директории выполнить
```
sudo apt-get install libsfml-dev
```
После запустить:
```
./sfml-app
```
### веб-контейнер
Чтобы запустить веб контейнер, который указан в доп условиях, нужно:
Глобально, или в директории socket_server выполнить комманду:
```
sudo apt install pip
```
Если же pip установлен, то нужно установить flask
```
pip install flask
```
Ну и наконец выполняем команду:
```
python3 main.py
```
