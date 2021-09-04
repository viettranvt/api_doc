# Info

Group: Facility
Method: GET
Status: Done
Url: /user/facilities/detail/<id>

**Example request**

```json
user/facilities/1
```

**Example response**

```json
{
    "id": 1,
    "name": "Co so 1",
    "owner": null,
    "author": {
        "id": 1,
        "username": "admin",
        "password": "$2a$10$1kSVcXrY03lCk2aOEosyAOxWdF65wkWs2U7ceTr8ilFm5ciHMAYaC",
        "full_name": "admin",
        "phone": "90000000",
        "email": "admin@247bpo.com",
        "partner_id": 1,
        "role_id": 1,
        "created_by": null,
        "is_admin": true,
        "is_root": false,
        "token": "'1':1 '90000000':5 'admin':2,4 'admin@247bpo.com':3",
        "created_at": "2021-02-21T04:44:23Z",
        "updated_at": "2021-02-21T04:44:23Z",
        "deleted_at": null
    },
    "token": "'1':1,4 'co':2 'so':3",
    "created_at": "2020-09-19T06:44:11Z",
    "updated_at": "2020-09-19T06:44:11Z",
    "deleted_at": null,
    "address_district": null,
    "address_ward": null,
    "address_province": null,
    "address": "Test address 1"
}
```