# API

```php
$api = $client->getApi();
```

## Class Name

`Api`


# Test Endpoint

```php
function testEndpoint(): ApiResponse
```

## Response Type

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` method on this instance returns the response data which is of type [`GetcodeResponse`](../../doc/models/getcode-response.md).

## Example Usage

```php
$apiResponse = $api->testEndpoint();
```

