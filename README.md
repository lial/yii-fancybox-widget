# yii-fancybox-widget
Виджет Fancybox (v.2.1.5) для Yii 1.x

## Подключение
Скопируйте папку **fancybox** в нужную вам директорию. Например в protected/extensions, тогда подключение будет выглядеть так:

```
$this->widget('application.extensions.fancybox.AlFancybox', [
        'targetDOM' => '.answer',
        'asDialog' => true,
        'hideDOM'  => '#comment-form',
    ]
);
```

## Параметры виджета
* **lang** - Язык блока. Локализуются подписи кнопок соцсетей и кнопка Скопировать ссылку.
* **iconLimit** - Ограничение на количество отображаемых иконок
* **iconSize** - Размер кнопок соцсетей (medium|small), по умолчанию medium
* **title** - Текст-заголовок для кнопок (текст в блоке перед кнопками)
* **asText** - Отображать ссылки в виде текста
* **showCopyLink** - Отображать кнопку Скопировать ссылку (first|last|hidden)
* **services** - Список идентификаторов социальных сетей, отображаемых в блоке (*all* - все возможные варианты или через запятую, нужные вам на выбор из списка: *blogger, delicious, digg, evernote, facebook, gplus, linkedin, lj, moimir, odnoklassniki, pocket, qzone, renren, sinaWeibo, surfingburd, tencentWeibo, tumblr, twitter, viber, vkontakte, whatsapp*)

