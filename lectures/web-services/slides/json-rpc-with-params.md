### rpc call with named parameters

Request
```json
{
    "jsonrpc": "2.0",
    "method": "subtract",
    "params": {
        "subtrahend": 23,
        "minuend": 42
    },
    "id": 1
}
```

Response
```json
{
    "jsonrpc": "2.0",
    "result": 19,
    "id": 1
}
```
