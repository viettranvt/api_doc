# Info

Group: Accounts
Method: GET
Status: Done
Url: user/accounts/list

**Parameter**

- offset: number
- limit: number
- filter: json object  //TODO

**Example request**

```json
localhost:8080/api/user/accounts/list?limit=1&offset=0
```

**Example response**

```json
//when there is pagination
{
    "total_count": 4,
    "offset": 0,
    "data": [
        {
            "id": 5,
            "username": "cheer.giang",
            "full_name": "Cheer User Giang",
            "phone": "(+84) 0973 002 333",
            "email": "cheer.giang@gmail.com",
            "partner_id": 2,
            "role_id": 1,
            "created_by": 1,
            "is_admin": false,
            "is_root": false,
            "created_at": "2020-09-19T06:44:11Z",
            "avatar": null
        }
    ]
}

//get all
[
    {
        "id": 5,
        "username": "cheer.giang",
        "full_name": "Cheer User Giang",
        "phone": "(+84) 0973 002 333",
        "email": "cheer.giang@gmail.com",
        "partner_id": 2,
        "role_id": 1,
        "created_by": 1,
        "is_admin": false,
        "is_root": false,
        "created_at": "2020-09-19T06:44:11Z",
        "avatar": null,
        "author": null,
        "partner": null,
        "role": null
    }
]
```