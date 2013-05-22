=====================
Данные в формате JSON
=====================

`JSON`_ - наиболее простой и в то же время надежный формат передачи данных,
в силу чего сейчас набирает все больше популярности. И следовательно, для его
обработки производится масса качественного ПО на многих языках.

.. _`JSON`: http://ru.wikipedia.org/wiki/JSON

Мы принимаем данные в этом формате, с очень простой структурой: *массив/список
объектов с* :doc:`определенными атрибутами </attributes>`. Каждый объект -
квартира, дом и т.д.

В следующем примере выдачи - три квартиры, находящиеся на 1-ом этаже 2-ой
секции 3-го корпуса 4-ой очереди::

    [
        {
            'quarter_number': 4,
            'building_number': 3,
            'section_number': 2,
            'floor_number': 1,
            'number': 1,
            'room_count': 2,
            'square': 34.6,
            'status': 1,
            'cost_per_meter': 5200.78
        },
        {
            'quarter_number': 4,
            'building_number': 3,
            'section_number': 2,
            'floor_number': 1,
            'number': 2,
            'room_count': 2,
            'square': 94.67,
            'status': 4,
            'cost_per_meter': 5200.78
        },
        {
            'quarter_number': 4,
            'building_number': 3,
            'section_number': 2,
            'floor_number': 1,
            'number': 3,
            'room_count': 3,
            'square': 60.1,
            'status': 1,
            'cost_per_meter': 5200.78
        },
    ]

.. note::
   Порядок объектов не имеет значения.