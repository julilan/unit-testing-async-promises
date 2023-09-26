# Car Storage API

## cars.json

```json
[
  { "model": "Bored T-model", "licence": "ABC-1" },
  { "model": "Nova", "licence": "XYZ-123" },
  { "model": "Bored T-model", "licence": "GTF-10" },
  { "model": "XCT", "licence": "B-1" }
]
```

## **search(key, value)**

Function returns an array of cars that matches the given criterion. If no match, returns an empty array.

If parameters are missing, returns all cars in an array.

Parameters:

- key: model or licence
- value: value to be searched
