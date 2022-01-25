# Создание Python приложения

Запустить консоль от администратора

## Перейти в папку с проектом

```shell
cd <project_path>
```

## Установить virtualenv для питона версии 3.6

```shell
py -3.6 -m pip install virtualenv
```

## Создать виртуальное окружение

```shell
py -3.6 -m venv venv
```

## Активировать виртуальное окружение

```shell
call venv\scripts\activate.bat
```

## Установить все необходимые пакеты

```shell
pip install fbs matplotlib==3.2.2 PyQt5==5.9.2
pip install pywin32
pip install -U pip setuptools
```

## Начать проект

```shell
fbs startproject

App name [MyApp] : Recon plotter
Author [Alexa] : Oleksandr Kolodkin
Mac bundle identifier (eg. com.oleksandr.reconplotter, optional): com.kolodkin.recon
```

## Запустить приложение

```shell
fbs run
```

## Сборка исполняемого файла

```shell
fbs freeze
```

## Сборка инсталятора

```shell
fbs installer
```
