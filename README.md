<h1 align="center">:snake: Telegram-RAT</h1>

<p align="center">
  Управляйте компьютером с помощью телеграмма!
</p>

# :page_facing_up: Установка
Для работоспособности скрипта установите Python 3.8 и следующие библиотеки
* `pip3 install pytelegrambotapi`
* `pip3 install opencv-python`
* `pip3 install cryptography`
* `pip3 install comtypes`
* `pip3 install pywin32`
* `pip3 install pyaudio`
* `pip3 install pillow`
* `pip3 install pycaw`

* Если есть ошибка с pyaudio, скачайте [отсюда](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)
  * Перейдите в директорию с whl-файлом и впишите в консоль `pip3 install pyaudio.x.x.x.whl`
#
* Создаём бота в телеграме через `@BotFather`, после чего находим его API-Токен

  <img src="https://i.imgur.com/3eWSJtZ.png">

* Теперь вам нужно получить ваш Telegram-ID. Для этого перейдите к `@my_id_bot` и сохраните ваш идентификатор.

  <img src="https://i.imgur.com/TIoauMO.png">

* Теперь вставьте скопированный токен и айди в скрипт `RAT.py`

  <img src="https://i.imgur.com/1T56OZL.png">

* Нажмите `CTRL + S`, чтобы сохранить изменения.                                                      
* Чтобы скомпилировать скрипт, воспользуйтесь pyinstaller'ом (`pip install pyinstaller`)
  * Откройте `CMD` в директории со скриптом и впишите `pyinstaller --onefile --noconsole RAT.py` и подождите.
  * Скомпилированный `.exe` файл будет в находиться в папке `dist`. И при запуске будет отправлять вам сообщение об онлайне.
  * Чтобы узнать список команд, используйте `/help`

# :grey_question: FAQ 
* При попытки запустить скрипт возникает ошибка `Нет подключения`
  * Как вы знаете, телеграмм заблокирован на территории РФ. Чтобы обойти эту блокировку воспользуйтесь встронным в скрипт socks5-прокси и установите требуемый модуль - `pip3 install pysocks`. Взять бесплатный Socks5 вы можете с [этого](https://hidemy.name/ru/proxy-list/?maxtime=800&type=5#list) сайта.

* При компиляции файла возникает ошибка `AttributeError: module 'enum' has no attribute 'IntFlag'`
  * Чтобы её решить, просто пропишите в консоле `pip uninstall -y enum34` и подтвердите удаление.

# :rose: Функции:
* АнтиБот (ВТ)
* Обнаружение антивирусного ПО
* Узнать версию OS
* Узнать IP жертвы
* Скриншот экрана
* Фото с вебки
* Видео с вебки
* Запись микрофона
* Управление питанием
   * Выключение
   * Перезагрузка
   * Синий экран смерти
* Автозагрузка
   * Сохранить в автозагрузку
     * Изменение даты и имени файла
   * Самоудаление
* Файловый менеджер
   * Просмотр текущей директории
   * Просмотр содержимого
   * Удаление файлов
      * Удаление всех файлов
   * Загрузить файл
   * Скачать файл
   * Запустить файл
      * Запустить от им. админа
* Диспетчер задач
  * Получить список процессов
  * Остановить процесс
     * Остановить все процессы
     * Отключить диспетчер задач
* Вывести сообщение на экран
* Озвучить сообщение
* Открыть ссылку
* Установить обои
* Запустить программу
  * Запустить один раз
  * Запустить много раз
* Стиллер паролей
* Буфер обмена
  * Просмотр буфера обмена
  * Редактирование буфера обмена

# Скриншоты
<p align="center">
    <img src="https://i.imgur.com/CzJ3u2t.png" Telegram-RAT">
</p>

# Кнопки навигации
<p align="center">
    <img src="https://i.imgur.com/LMsVw3L.png" Telegram-RAT">
</p>
