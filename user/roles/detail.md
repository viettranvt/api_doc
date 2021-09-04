# Info

Group: Role
Method: GET
Status: Done
Url: /user/roles/detail/<id>

**Example request**

```json
localhost:8080/api/user/roles/detail/2
```

**Example response**

```json
{
    "id": 3,
    "name": "Role_3508",
    "permissions": [
        "equipment_requests:getall",
        "account:getall",
        "bills:getall",
        "facility_maintenance_histories:getone",
        "requests:create",
        "notifications:create",
        "equipment_requests:getone",
        "facilities:getone"
    ],
    "assignees": [
        {
            "id": 3,
            "avatar": null,
            "username": "sodo.admin",
            "fullName": "Sodo Admin",
            "phone": "(+84) 0823 712 221",
            "email": "sodo.admin@gmail.com"
        },
        {
            "id": 8,
            "avatar": null,
            "username": "sodo.giang",
            "fullName": "Sodo User Giang",
            "phone": "(+84) 0973 222 333",
            "email": "sodo.giang@gmail.com"
        },
        {
            "id": 9,
            "avatar": null,
            "username": "sodo.huy",
            "fullName": "Sodo User Huy",
            "phone": "(+84) 0973 331 331",
            "email": "sodo.huy@gmail.com"
        },
        {
            "id": 10,
            "avatar": null,
            "username": "sodo.dat",
            "fullName": "Sodo User Dat",
            "phone": "(+84) 0973 442 448",
            "email": "sodo.dat@gmail.com"
        }
    ]
}
```