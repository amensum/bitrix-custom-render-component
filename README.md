# Bitrix custom render component

__Calling example:__
```php
$APPLICATION->IncludeComponent(
    "custom:render",
    "",
    [
        "ORDER" => [
            "SORT" => "ASC",
        ],
        "FILTER" => [
            "IBLOCK_ID" => "1",
            "ACTIVE" => "Y",
        ],
        "NAV_PARAMS" => [
            "nTopCount" => "1",
        ],
        "FIELDS" => [
            "ID",
            "IBLOCK_ID",
            "NAME",
            "PREVIEW_PICTURE",
            "DETAIL_PICTURE",
        ],
        "PICTURES_WIDTH" => "256",
        "PICTURES_HEIGHT" => "256",
    ]
);
```
