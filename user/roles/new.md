# info

Group: Role
Method: POST
Status: Done
Url: /user/roles/new

**Parameters**

- all: boolean    //only input multiple

**Example request**

```json
//input single
{
   name         string
   permissions  types.StringArray
}

//input multiple
[{
   name         string
   permissions  types.StringArray
   line_num     null,int
}]
```

**Example response**

```json
//single response
{
    "id": 17,
    "name": "test",
    "permissions": [
        "users:create",
        "users:update",
        "users:delete",
        "users:getone",
        "users:getall"
    ]
}

//multi response
//when all = true
[
    {
        "id": 18,
        "name": "test",
        "permissions": [
            "users:create",
            "users:update",
            "users:delete",
            "users:getone",
            "users:getall"
        ]
    }
]

//when all = false
{
    "data": [
        {
            "id": 19,
            "name": "test",
            "permissions": [
                "users:create",
                "users:update",
                "users:delete",
                "users:getone",
                "users:getall"
            ]
        }
    ],
    "error": [
        {
            "line_num": 0,
            "error": "name: cannot be blank."
        }
    ]
}
```