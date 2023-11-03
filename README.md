# Отключение водоснабжения в случае аварии с водой / water-shut-off
water shut-off arduino

Простое устройство для перекрытия кранов при протечке воды, собранно на контроллере STM32. Собранно для личных целей, выложенно для интереса. Критика приветсвуется, но помните, я не являюсь профессиональным разработчиком.

В устройстве всего одна функциональная кнопка. Сделанно это осознано, для максимально простого управления без вникания: пищит - нажми, нет воды - нажми, хочешь закрыть краны - нажми, открыть - нажми, при этом всего одна и та же кнопка.

Устройство, на данный момент, при подключении питания становится в режим ожидания изменения сопротивления на датчиках. При срабатывании одного или нескольких датчиков, устройство по очередно закрывает краны, выводит на мини экран номера датчиков, противно пищит и больше не реагирует на изменения на датчиков.
Для отключения пронзительного писка, просто нажимаем кнопку. Повторное нажатие той же кнопки, заставит открыть краны один за другим. Но если датчики не высохли, то закроет краны снова.

При нажатии кнопки не в аварийном режими, заставит устройство открыть краны, если они закрыты или закрыть, если они открыты.

Внешний вид устройства:
<img src="files/IMG_20230620_155028.jpg" alt="Внешний вид платы" width="auto" height="auto" align="top">

Комплектация и ссылки для покупки элементов:
1. [Программатор](https://aliexpress.ru/item/32792513237.html?spm=a2g0o.order_list.order_list_main.611.5f1218029YgoDx&gatewayAdapt=glo2rus&sku_id=10000015042616724)

2. <a href="http://example.com" target="_blank">Link</a>


Небольшое видео работы устройства и мои колхозные рассуждения:
[![Watch the video](https://raw.githubusercontent.com/shliamb/water-shut-off/main/files/video.png)](https://www.youtube.com/embed/kJl_R9npxQE?si=utTMXmJ6Z3xOJjf_)






