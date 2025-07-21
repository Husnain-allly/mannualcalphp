# Subtractnumbermath

Subtracting two numbers operations

```php
$subtractnumbermathApi = $client->getSubtractnumbermathApi();
```

## Class Name

`SubtractnumbermathApi`


# Subtract Numbers

```php
function subtractNumbers(float $num1, float $num2): ApiResponse
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `num1` | `float` | Template, Required | - |
| `num2` | `float` | Template, Required | - |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`SubtractnumbersResponse`](../../doc/models/subtractnumbers-response.md).

## Example Usage

```php
$num1 = 70.32;

$num2 = 59.62;

$apiResponse = $subtractnumbermathApi->subtractNumbers(
    $num1,
    $num2
);
```

