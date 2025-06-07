# Установка Git

***Установка в Linux***  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Если вы хотите установить Git под Linux как бинарный пакет, это можно сделать, используя обычный менеджер пакетов вашего дистрибутива. Если у вас Fedora (или другой похожий дистрибутив, такой как RHEL или CentOS), можно воспользоваться <font color="red">dnf</font>:

```
$ sudo dnf install git-all
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Если же у вас дистрибутив, основанный на Debian, например, Ubuntu, попробуйте <font color="red">apt:</font>

```
$ sudo apt install git
```

***Установка на Mac***

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Существует несколько способов установки Git на Mac. Самый простой — установить Xcode. В версии Mavericks (10.9) и выше вы можете добиться этого просто первый раз выполнив 'git' в терминале.
```
$ git - - version
```
*Homebrew*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Установите homebrew, если у вас его ещё нет, затем:
```
$ brew install git
```
*MacPorts*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Установите MacPorts, если у вас его ещё нет, затем:
```
$ sudo port install git
```

***Установка в Windows***

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Для установки Git в Windows также имеется несколько способов. Официальная сборка доступна для скачивания на официальном сайте Git. Просто перейдите на страницу: https://git-scm.com/downloads/win, и скачайте нужный файл.
Или используйте инструмент winget. Установите инструмент winget если у вас его еще нет, затем введите эту команду в командной строке или Powershell.
```
winget install --id Git.Git -e --source winget
```
[Вернуться обратно](README.md)
