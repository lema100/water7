Быстрый старт
=============

1. Получите последнюю версию библиотеки

    git clone https://github.com/Gordon01/waviot-water7

2. Скопируйте все содерджимое директории `lib` в соответствующие директории вашего проекта

3. Подключите библиотеку

    include "WVT_Water7.h"
4. Зарегистрируйте внешние обработчики

.. doxygenfunction:: WVT_W7_Register_Callbacks
5. При приеме downlink-пакета, должна вызываться функция

.. doxygenfunction:: WVT_W7_Parse
6. Для отправки стартового пакета, вызовите

.. doxygenfunction:: WVT_W7_Start
7. Библиотека готова к работе