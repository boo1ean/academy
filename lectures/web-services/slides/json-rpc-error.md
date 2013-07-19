## Error response

Request
```json
{
    "jsonrpc": "2.0",
    "method": "div",
    "params": [42, 0],
    "id": 1
}
```

Response
```json
{
    "jsonrpc": "2.0",
    "error": {
        "code": -32600,
        "message": "Only admin can divide by zero."
    },
    "id": null
}
```
