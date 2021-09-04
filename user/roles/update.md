# Info

Group: Role
Method: PUT
Status: Done
Url: /user/roles/update

**Parameters**

- all: boolean    //only input multiple

**Example request**

```json
//input single
{
   id           int
   name         string
   permissions  types.StringArray
}

//input multiple
[{
   id           int{
    "id": 21,
    "name": "test21",
    "permissions": [
        "users:create",
        "users:update",
        "users:delete",
        "users:getone",
        "users:getall"
    ]
}
   name         string
   permissions  types.StringArray
   line_num     null,int
}]
```

**Example response**

```json
//single response
{
    "id": 21,
    "name": "test21",
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
        "id": 21,
        "name": "test210",
        "permissions": [
            "users:create",
            "users:update",
            "users:delete",
            "users:getone",
            "users:getall"
        ]
    },
    {
        "id": 20,
        "name": "test200",
        "permissions": [
            "users:create",
            "users:getone",
            "users:getall"
        ]
    }
]

//when all = false
{
    "data": [
        {
            "id": 21,
            "name": "test210",
            "permissions": [
                "users:create",
                "users:update",
                "users:delete"
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