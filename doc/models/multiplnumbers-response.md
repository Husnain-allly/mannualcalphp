
# Multiplnumbers Response

*This model accepts additional fields of type array.*

## Structure

`MultiplnumbersResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `result` | `?float` | Optional | The product of the two numbers | getResult(): ?float | setResult(?float result): void |
| `additionalProperties` | `array<string, array>` | Optional | - | findAdditionalProperty(string key): array | additionalProperty(string key, array value): void |

## Example (as JSON)

```json
{
  "result": 152.24,
  "exampleAdditionalProperty": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

