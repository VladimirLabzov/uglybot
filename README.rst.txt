CatBot
======

CatBot - это бот для Telegram, созданный делать Вашу жизнь лучше присылая фотки котанов.

Установка
=========

Создайте виртуальное окружение и активируйте его. Потом в виртуальном окружении выполните:

.. code-block:: text

    pip install -r requirements.txt 

Положите картинки с котиками в папку images. Название файлов должно начинаться с catб а заканчиваться .jpg. Например: cat123456789.jpg

Настройка
=========

Создайте файл settings.py и добавьте туда следующие настройки:

.. code-block:: python

PROXY = {'proxy_url': 'socks5://ВАШ_SOCKS5_ПРОКСИ:1080',
    'urllib3_proxy_kwargs': {'username': 'ЛОГИН', 'password': 'ПАРОЛЬ'}}

API_KEY = 'API ключ, который Вы получили у BotFather'      

USER_EMOJI = [':smiley_cat:', ':smiling_imp:', ':panda_face:', ':dog:']

Запуск
======

В активированном виртуальом окружении вполните:

.. code-block:: text

    pytnon bot.py
