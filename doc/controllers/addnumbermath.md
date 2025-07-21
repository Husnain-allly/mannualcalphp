# Addnumbermath

Adding two numbers operations

```php
$addnumbermathApi = $client->getAddnumbermathApi();
```

## Class Name

`AddnumbermathApi`


# Add Numbers

```php
function addNumbers(float $num1, float $num2): ApiResponse
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `num1` | `float` | Query, Required | - |
| `num2` | `float` | Query, Required | - |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`AddnumbersResponse`](../../doc/models/addnumbers-response.md).

## Example Usage

```php
$num1 = 70.32;

$num2 = 59.62;

$apiResponse = $addnumbermathApi->addNumbers(
    $num1,
    $num2
);
```

