
# Createsquareroot Response

*This model accepts additional fields of type array.*

## Structure

`CreatesquarerootResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `result` | `?float` | Optional | The square root of the number | getResult(): ?float | setResult(?float result): void |
| `additionalProperties` | `array<string, array>` | Optional | - | findAdditionalProperty(string key): array | additionalProperty(string key, array value): void |

## Example (as JSON)

```json
{
  "result": 59.42,
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

