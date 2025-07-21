# Createsquarerootmath

Creating square root operations

```php
$createsquarerootmathApi = $client->getCreatesquarerootmathApi();
```

## Class Name

`CreatesquarerootmathApi`


# Create Square Root

```php
function createSquareRoot(?float $number = null): ApiResponse
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `number` | `?float` | Form, Optional | - |

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`CreatesquarerootResponse`](../../doc/models/createsquareroot-response.md).

## Example Usage

```php
$apiResponse = $createsquarerootmathApi->createSquareRoot();
```

