___
# Введение в Linux для робототехники.
___
## Задание 1. Установка Ubuntu Linux
1. Скачайте ISO-образ Ubuntu Linux выбранной версии (20.04 LTS для работы с ROS Noetic).
2. Создайте загрузочную флешку, подготовьте компьютер к установке и установите Ubuntu Linux.
3. Выполните первоначальную настройку операционной системы, ознакомьтесь с её интерфейсом.
## Результат
В результате на вашем персональном компьютере должна быть установлена ОС Ubuntu Linux. К отчёту прикрепите снимок рабочего стола с запущенным терминалом и программой Disks.
___
## Задание 2. Знакомство с консолью Linux
1. Запустите консоль.
2. Последовательно повторите представленные в видео к модулю команды, в том числе:
* просмотр содержимого текущего каталога (ls, попробуйте опции l, a, h);
* перемещение между каталогами (cd, попробуйте переход в домашний каталог, в каталог на уровень выше, к предыдущему каталогу), просмотр текущего пути (pwd);
* создание каталога для проекта (mkdir);
* вывод содержимого файла на экран (cat), поиск текста в файле (grep), вывод последних или первых строк файла (tail, head, more);
* копирование и перемещение файлов, директорий (mv);
* использование справки и руководств по командам (man, help, -h, –help);
* выполнение команды от имени суперпользователя (sudo).
Используйте удобные сочетания клавиш (Tab, стрелки вверх/вниз, Ctrl + C, Ctrl + R, Ctrl + A, Ctrl + E, Ctrl + D, Ctrl + L, Ctrl + Shift + C, Ctrl + Shift + V).
## Результат
Основные перечисленные команды и сочетания клавиш можно запомнить и применять.
По каждому пункту сделайте скриншот результата работы команды и прикрепите его к отчёту. Также запишите вопросы, если они возникнут, и составьте краткое впечатление о работе в консоли.
___
## Задание 3. Установка программ в Ubuntu Linux на примере ROS
1. Ознакомьтесь с разными способами установки программного обеспечения в Ubuntu Linux.
2. Установите ROS Noetic. Последовательно выполняйте команды для установки ROS согласно инструкции. Ознакомьтесь с назначением каждой команды, в том числе:
* добавление репозитория (в sources.list);
* добавление ключей репозитория ROS (apt-key add -);
* обновление списка пакетов (apt update);
* поиск пакетов (apt search);
* установка пакетов (apt install).
3. Настройте ROS (.bashrc, доустановка пакетов rosinstall, rosdep), создайте и инициализируйте рабочую область catkin_ws, выполните сборку, добавьте рабочую область в .bashrc.
## Результат
В результате у вас будет установленное и полностью готовое окружение для работы с ROS.
* После завершения установки и настройки запустите новую консоль, выполните команду roscd. Если все настройки выполнены верно, вы перейдёте в папку catkin_ws/devel в своём домашнем каталоге.
* Запустите команду roscore (пример с черепашками из туториалов ROS: Understanding ROS Nodes или ROS/Tutorials/UnderstandingTopics).
* Сделайте скриншоты терминала, в котором запустили roscore, терминала с выводом команды rosnode list, а также любые другие скриншоты в процессе ваших экспериментов и прикрепите их к отчёту.
___
## Задание 4. Консольные текстовые редакторы
1. Попрактикуйтесь в работе с двумя консольными текстовыми редакторами: Vi и Nano. Выберите тот, который будете использовать, чтобы подключаться к роботу в терминале без графического интерфейса.
2. Выполните основные действия по созданию и редактированию текстовых файлов в консольном текстовом редакторе:
* открытие файла, навигация по нему;
* поиск текста;
* редактирование, копирование/вставка/замена текста;
* сохранение файла, выход.
3. Сделайте скриншоты каждого пункта и прикрепите к отчёту, опишите свои впечатления о работе в каждом текстовом редакторе.
___
___
# Модуль пройден
* Все задания выполнены.
* Процесс выполнения оформлен в [документальном виде](https://github.com/al-sapsan/skill-linux/blob/module1/practice_work1.pdf).

