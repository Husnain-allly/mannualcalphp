# Multipliednumbermath

Multiplying two numbers operations

```php
$multipliednumbermathApi = $client->getMultipliednumbermathApi();
```

## Class Name

`MultipliednumbermathApi`


# Multiply Numbers

```php
function multiplyNumbers(float $num1, float $num2): ApiResponse
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `num1` | `float` | Header, Required | - |
| `num2` | `float` | Header, Required | - |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`MultiplnumbersResponse`](../../doc/models/multiplnumbers-response.md).

## Example Usage

```php
$num1 = 70.32;

$num2 = 59.62;

$apiResponse = $multipliednumbermathApi->multiplyNumbers(
    $num1,
    $num2
);
```

