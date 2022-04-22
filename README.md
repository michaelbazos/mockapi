# mockapi

This repository includes a `db.json` file which contains mocked data, for example:

```json
{
    "todos": [
        {
            "id": 0,
            "title": "Learn JavaScript",
            "completed": false
        },
        {
            "id": 1,
            "title": "Learn TypeScript",
            "completed": false
        }
    ]
}
```

## Query mocked data

### Query all *todos* objects

    GET https://my-json-server.typicode.com/michaelbazos/mockapi/todos

Returns

```json
[
    {
        "id": 0,
        "title": "Learn JavaScript",
        "completed": false
    },
    {
        "id": 1,
        "title": "Learn TypeScript",
        "completed": false
    }
]
```
    
### Query an object by *id*

    GET https://my-json-server.typicode.com/michaelbazos/mockapi/todos/1

Returns

```json
{
    "id": 1,
    "title": "Learn TypeScript",
    "completed": false
}
```
