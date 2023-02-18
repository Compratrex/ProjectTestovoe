# ProjectTestovoe

## Развертывание
Чтобы развернуть приложение и сервер нужно сначала либо клонировать проект, либо скачать через кнопку code zip файл.

Если клонируем (Самый простой способ):
```
git clone https://github.com/Compratrex/ProjectTestovoe.git
```

Далее, нужно распаковать все что имеет .zip расширение в ту же папку, где находится.

Чтобы запустить сервер необходимо иметь питон 3 й и выше.
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
Глобально, или в директории socket_server выполнить команду:
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
Все протестировано и работает на ubuntu 22.04
Приложение написано на c++
Сервер на python, модель связи unicast
Присутствует функционал телеметрии
Графическое приложение клиента использует движок sfml
Объект находится в 2д пространстве
Сервер имеет веб интерфейс для работы с БД
![image](https://user-images.githubusercontent.com/76513693/219665757-4a1aa23f-fa53-4066-bb9e-2b10108d6a2f.png)


