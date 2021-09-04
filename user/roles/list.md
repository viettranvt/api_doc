# Info

Group: Role
Method: GET
Status: Done
Url: /user/roles/list

**Parameters**

- offset: number
- limit: number
- filter: json object

// filter owned_ by only for supllier

**Example request**

```json
localhost:8080/api/user/roles/list?limit=1&offset=0
```

**Example response**

```json
//when there is pagination
{
    "total_count": 1,
    "offset": 0,
    "data": [
        {
            "id": 2,
            "name": "Role_3509",
            "assignees": [
                {
                    "id": 2,
                    "avatar": null,
                    "username": "cheer.admin",
                    "fullName": "Cheer Admin",
                    "phone": "(+84) 0973 943 579",
                    "email": "cheer.admin@gmail.com"
                },
                {
                    "id": 5,
                    "avatar": null,
                    "username": "cheer.giang",
                    "fullName": "Cheer User Giang",
                    "phone": "(+84) 0973 002 333",
                    "email": "cheer.giang@gmail.com"
                },
                {
                    "id": 6,
                    "avatar": null,
                    "username": "cheer.huy",
                    "fullName": "Cheer User Huy",
                    "phone": "(+84) 0973 444 555",
                    "email": "cheer.huy@gmail.com"
                },
                {
                    "id": 7,
                    "avatar": null,
                    "username": "cheer.dat",
                    "fullName": "Cheer User Dat",
                    "phone": "(+84) 0973 111 333",
                    "email": "cheer.dat@gmail.com"
                }
            ]
        }
    ]
}

//get all
[
    {
        "id": 2,
        "name": "Role_3509",
        "assignees": [
            {
                "id": 2,
                "avatar": null,
                "username": "cheer.admin",
                "fullName": "Cheer Admin",
                "phone": "(+84) 0973 943 579",
                "email": "cheer.admin@gmail.com"
            },
            {
                "id": 5,
                "avatar": null,
                "username": "cheer.giang",
                "fullName": "Cheer User Giang",
                "phone": "(+84) 0973 002 333",
                "email": "cheer.giang@gmail.com"
            },
            {
                "id": 6,
                "avatar": null,
                "username": "cheer.huy",
                "fullName": "Cheer User Huy",
                "phone": "(+84) 0973 444 555",
                "email": "cheer.huy@gmail.com"
            },
            {
                "id": 7,
                "avatar": null,
                "username": "cheer.dat",
                "fullName": "Cheer User Dat",
                "phone": "(+84) 0973 111 333",
                "email": "cheer.dat@gmail.com"
            }
        ]
    }
]
```