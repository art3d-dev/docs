====================
Данные в формате XML
====================

`XML`_ - формат, который используется уже много лет для описания любого рода
данных. На нем основаны такие популярные форматы как `HTML`, `SVG` и др. Он
максимально структурирован, типизирован, однако часто сложен для чтения человеком.

.. _XML: http://ru.wikipedia.org/wiki/XML
.. highlight:: xml

Мы принимаем XML-данные с простейшей структурой, где в корневом элементе
находятся элементы квартиры с :doc:`атрибутами </attributes>`::

    <?xml version="1.0" encoding="UTF-8"?>
    <data>
        <apartment
                quarter_number="1"
                building_number="1"
                section_number="1"
                floor_number="1"
                number="1"
                square="56.7"
                room_count="3"
                total_cost="3456321"
                cost_per_meter="1200"
                status="1"
                note=""/>
        <apartment
                quarter_number="1"
                building_number="1"
                section_number="1"
                floor_number="1"
                number="2"
                square="56.7"
                room_count="3"
                total_cost="3456321"
                cost_per_meter="1200"
                status="1"
                note=""/>
        <apartment
                quarter_number="1"
                building_number="1"
                section_number="1"
                floor_number="1"
                number="2"
                square="86.7"
                room_count="4"
                total_cost="5456321"
                cost_per_meter="1200"
                status="1"
                note=""/>
    </data>

