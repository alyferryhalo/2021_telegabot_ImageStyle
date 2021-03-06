# 2021_telegabot_ImageStyle
🖌🤖 Стилизация изображений в телеграм-боте
Идея взята из перечня проектов Deep Learning School
____
## Основная часть
1. Написать код простой модели, которая сможет переносить стиль с одной фотографии на другую. Можно использовать медленный алгоритм.
2. Сделать бота, которому можно отправить две фотографии и получить в ответ фото с перенесенным стилем.
Дополнительная часть: 
3. Добавить возможность переносить стиль с помощью GAN'ов.

### Для основной части
1. Еще раз посмотреть на код в занятии и перенести всю функциональность в класс, чтобы потом можно было удобнее работать.
2. Написать бота, у которого будет диалог, предлагающий прислать картинки, и хэндлер, вызывающий класс из предыдущего пункта, чтобы ссгенерировать ответную картинку.
3. (опционально) Асиинхронность. Если вы раньше не писали приложения для сервера, то ваш код получится не асинхронным, а именно, во время обработки картинки бот будет просто висеть и не сможет ответить другому человеку. Это можно исправить, но потребуется хорошее понимание фреймворка, на котором Вы пишете бота.

## Дополнительная часть:
1. Выбрать какой GAN Вы хотите использовать и какой стиль преносить. Возможно, Вы захотите сделать не совсем перенос стиля, а какую-то другую обработку картинок, что тоже принимается.
2. Прочитать, как алгоритм работает и понять.
3. Теперь есть два варианта: Найти готовую реализацию и как-то вызывать ее из своего кода **ИЛИ** Натренировать свой GAN. Этот вариант скорее всего потребует вычислительных мощностей и времени, поэтому выбирайте его только если уверены в своих силах. 
4. Дописать бота, чтобы он мог использовать GAN."

## Для прочтения
1. https://hardikbansal.github.io/CycleGANBlog/
2. https://github.com/luanfujun/deep-photo-styletransfer
3. https://github.com/eternnoir/pyTelegramBotAPI/
4. https://aiogram.readthedocs.io/
