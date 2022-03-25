# test_email_bсs
Сделала письмо без применения каких-либо фреймворков (foundation или mjml), но практически все блоки в письме сделаны на основе компонентов, взятых из писем, которые я делала для других проектов + точечная доработка дизайна десктоп/мобайл.

Безусловно применение сопутствующих инструментов облегчает жизнь разработчику, появляется автоматизация, не нужно что-то уже делать с нуля, но по своему опыту могу сказать, что даже в письмах, которые были сделаны в сборщике/фреймворке были свои косяки, в основном в outlook, в данном случае я очень ценю чужую работу и разработчик, который потратил огромное количество времени на верстку писем был не в курсе багов в outlook. 

Идеальный тандем разработки email-рассылки - это сборка его с помощью какого-либо инструмента (что быстрее), либо с нуля + фикс багов в outlook/др. почтовики (но там меньше всего). И далее переиспользование компонентов. На собеседовании был озвучен очень крутой момент - это компонентная база, было бы здорово собрать/собирать в процессе такое. Это уже что-то на "продуктовом" :)

Плюс ручной сборки безусловно это точность, практически pixel perfect, но занимает дОльше времени (но, если рука набита и постоянно собираешь письма, то думаю этот момент можно уменьшить в половину по трудоемкости).

Ссылка на [превью](https://carefulmore.github.io/test_email_bks/).

PS немного комментариев по самому письму:
- У bg-image задала фон (подходящий по дизайну), т.к. outlook не поддерживает это свойство
- border-radius так же не будет работать в outlook
- Все тексты прогнала через Типограф, чтобы не было висячих предлогов
- Протестила письмо в gmail/yandex/mail/outlook for mac, outlook на windows у меня к сожалению нет(
