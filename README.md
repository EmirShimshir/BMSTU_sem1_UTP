# BMSTU_sem1_UTP
Итоговое задание по практикуму __(linux, bash)__, семестр №1

## Разработать скрипт командной оболочки для обработки текстовых файлов.

1. У скрипта есть список расширений временных файлов. По умолчанию список состоит из «*.log».
2. У скрипта есть список расширений рабочих файлов. По умолчанию список состоит из «*.py».
3. У скрипта есть рабочая папка, в которой выполняется вся работа скрипта. По умолчанию это папка самого скрипта.
4. Настройки скрипта сохраняются в файле «.myconfig» рядом со скриптом. Если файл при запуске нельзя обнаружить, генерируется файл настроек по умолчанию.
5. У скрипта есть записанная пользователем в виде строки команда. По умолчанию это «grep def* program.py >last.log». 


### Скрипт должен предоставлять пользователю с помощью меню и текстового интерфейса следующие возможности:


1. Возможность просмотреть или задать заново список расширений временных файлов.
2. Возможность добавлять или удалять конкретное расширение из списка расширений временных файлов. Достаточно реализовать удаление по номеру.
3. Возможность просмотреть или задать заново список расширений рабочих файлов.
4. Возможность добавлять или удалять конкретное расширение из списка расширений рабочих файлов. Достаточно реализовать удаление по номеру.
5. Возможность просмотреть, изменить или задать заново рабочую папку скрипта.
6. Возможность удалить временные файлы.
7. Возможность выполнить или изменить записанную команду.
8. Возможность просмотреть все строки, ограниченные апострофами, во всех рабочих файлах.
9. Возможность просмотреть объём каждого временного файла.

### Скрипт должен иметь возможность запуска в тихом режиме (без меню), для чего следует использовать позиционные аргументы. Скрипт не должен позволять запуск от имени администратора.
