# Python-RAT
Усовершенствованный инструмент удаленного администрирования для Windows-систем, написанный на чистом Python

## Предназначена для:
Windows

## Модули.
+ Pillow
+ pywin32
+ opencv-python
+ comtypes 
+ pycaw ([C++ Buils tools](https://visualstudio.microsoft.com/ru/visual-cpp-build-tools/) требуются)
+ pyautogui
+ vidstream ([VS Code](https://code.visualstudio.com/) требуется)

## Использование для сервера
```
#Клонируйте репозиторий
https://github.com/FZGbzuw412/Python-RAT

#перейдите в каталог с файлами
cd Python-RAT 

#установите необходимые зависимости
pip3 install -r server_requirements.txt

#запустите
server.py
```

## Использование для клиента
```
#клонирование или загрузка zip-архива
https://github.com/FZGbzuw412/Python-RAT

#перейдите в каталог с файлами
cd Python-RAT

#установить необходимые требования
pip3 install -r client_requirements.txt

#запуск 
client.pyw
```
