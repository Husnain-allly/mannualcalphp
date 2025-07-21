# Updatenumbermath

Updating a number operations

```php
$updatenumbermathApi = $client->getUpdatenumbermathApi();
```

## Class Name

`UpdatenumbermathApi`


# Update Number

```php
function updateNumber(int $body): ApiResponse
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`int(Complexvalueset)`](../../doc/models/complexvalueset.md) | Body, Required | - |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`UpdatenumberResponse`](../../doc/models/updatenumber-response.md).

## Example Usage

```php
$body = Complexvalueset::ENUM_4;

$apiResponse = $updatenumbermathApi->updateNumber($body);
```

