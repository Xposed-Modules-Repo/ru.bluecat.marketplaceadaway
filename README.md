<div align="center">
<h1>Marketplace AdAway</h1>

![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway/total)
[![GitHub release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway)](https://github.com/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway)](https://github.com/Xposed-Modules-Repo/ru.bluecat.marketplaceadaway/releases)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-blue.svg?logo=telegram)](https://t.me/lsposed_workshop)
[![Telegram Group](https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram)](https://t.me/lsposed_workshop_forum)
[![4PDA](https://img.shields.io/badge/4PDA-Topic-blue)](https://4pda.to/forum/index.php?showtopic=603033&view=findpost&p=136661029)
[![Donate](https://img.shields.io/badge/Donate_Form-blue)](https://pay.cloudtips.ru/p/85f8cf00)

<p>Скрывает рекламу и рекомендации в российских маркетплейсах.</p>
</div>

### Описание:
- Это мульти пакетный модуль сосредоточенный на двух задачах, скрытие баннеров с плашками реклама и каруселей рекомендаций. Прошу учесть что карусели скрыты не все, а лишь в тех местах которые отвлекают от оформления покупки, например профиль/корзина/карточка товара. 
- Данный модуль не содержит интерфейса т.к. выбор от пользователя в нём не требуется, в связи с этим все ошибки и требования от модуля поступают в лог LSPosed менеджера.
- Сброс технических данных осуществляется вручную по необходимости.

### Особенности:
Ozon:
- Вкладка Ozon банка построена по web технологиям и не обработана.

Яндекс Маркет:
- Управление проверкой на VPN и Root доступ для банкинга.
- Не редактируемые разделы в связи с web технологиями построения:
Большая часть разделов в каталоге
Яндекс Лавка
Часть разделов профиля

Магнит Маркет:
- Дополнительное управление рекламой подписки и опросов.
- Некоторые кнопки с надписью реклама не скрыты.
- Разделы главной маркета пересортированы.

### Требования:
- Android 7.0+
- Установленные приложения: [Ozon](https://www.rustore.ru/catalog/app/ru.ozon.app.android) / [Wildberries](https://www.rustore.ru/catalog/app/com.wildberries.ru) / [Яндекс Маркет](https://www.rustore.ru/catalog/app/ru.beru.android) / [Магнит](https://www.rustore.ru/catalog/app/ru.tander.magnit)

### Обратите внимание:
- В приложениях встречаются экраны полностью сделанные по web технологиям(javascript, html). С такими техниками построения интерфейса к сожалению фреймворк работать не умеет.
- Модуль имеет возможность работать в режиме [LSPatch](https://github.com/JingMatrix/LSPatch), подробнее смотрите в telegram канале.

## For non-Russian users:
This is a module for the russian "marketplaces", sites for shopping.
You don't need to use it, apps working only in Russia and some nearby republics. This module has support only for the Russian language.
