# yii2-json-attribute-behavior
Yii2 Behavior for encode and decode json stored attributes

## Instalation
composer require kfreiman/yii2-json-attribute-behavior "dev-master"

## Use
```php

public function behaviors()
{
    return [
        'jsonAttributes' => [
            'class' => JsonAttributeBehavior::className(),
            'attributes' => [
                'attrJson' => 'attr'
            ],
        ],
    ];
}

```
