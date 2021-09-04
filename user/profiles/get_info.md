# Info

Group: Profile
Method: GET
Status: Done
Url: /user/profiles/get_info

**Example request**

```json

```

**Example response**

```json
{
    "user_id": 2,
    "permissions": [
        "users:create",
        "users:update",
        "users:delete",
        "users:getone",
        "users:getall",
        "partners:create",
        "partners:update",
        "partners:delete",
        "partners:getone",
        "partners:getall",
        "roles:create",
        "roles:update",
        "roles:delete",
        "roles:getone",
        "roles:getall",
        "services:create",
        "services:update",
        "services:delete",
        "services:getone",
        "services:getall",
        "requests:create",
        "requests:update",
        "requests:delete",
        "requests:getone",
        "requests:getall",
        "request_items:create",
        "request_items:update",
        "request_items:delete",
        "request_items:getone",
        "request_items:getall",
        "items:create",
        "items:update",
        "items:delete",
        "items:getone",
        "items:getall",
        "facilities:create",
        "facilities:update",
        "facilities:delete",
        "facilities:getone",
        "facilities:getall",
        "bills:create",
        "bills:update",
        "bills:delete",
        "bills:getone",
        "bills:getall",
        "evaluations:create",
        "evaluations:update",
        "evaluations:delete",
        "evaluations:getone",
        "evaluations:getall",
        "fields:create",
        "fields:update",
        "fields:delete",
        "fields:getone",
        "fields:getall",
        "partner_update_requests:create",
        "partner_update_requests:update",
        "partner_update_requests:delete",
        "partner_update_requests:getone",
        "partner_update_requests:getall"
    ],
    "partner": {
        "id": 2,
        "company_name": "Cheers",
        "phone": "38724054",
        "address": "8521 Hàng Ý Phi",
        "tax_number": "9876779301",
        "type": 1,
        "token": "'1':9 '2':1 '38724054':3 '8521':4 '9876779301':8 'cheers':2 'hàng':5 'phi':7 'ý':6",
        "address_district_id": 1,
        "address_ward_id": 4,
        "address_province_id": 1,
        "created_at": "2020-09-13T22:24:23Z",
        "updated_at": "2020-09-13T22:24:23Z",
        "deleted_at": null
    },
    "partner_type": 1,
    "partner_id": 2,
    "full_name": "Cheer Admin",
    "email": "cheer.admin@gmail.com",
    "phone": "(+84) 0973 943 579",
    "username": "cheer.admin",
    "role_id": 1,
    "is_admin": false,
    "is_root": true,
    "avatar": "https://247bpo.storage.googleapis.com/avatar/2/abc.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=bucket-access%40bpo-247.iam.gserviceaccount.com%2F20210719%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210719T095352Z&X-Goog-Expires=899&X-Goog-Signature=25419854ae2d7362cf4856c365b84232f3bf181d141010014ec1bc256b1795c3ffe70f56edbf1914209a46c10cba333f7af7bf806a1adb892442a51c9064e2d14d750e89011bc0e441ddf37562df20907bc329f93db65e8e042730ae49590078746f9dbf0068adc979351cc688b1d8b252648aab07e4deca775caa03d5828d88b8df7c20a8cd7756d809c371782406c665e81549484990435235899899194210c0d7fd27daac2711be5b767fd1d35f589546f1c332a1a80b08a39957ca899b4d2e24fda6253bd751daef4df94eecbb508e5350ae6226e3fa5ca3e36a24248bae5dbecc8117e3840605ab056f72fe803a96cd882778f6c36282127912322003da&X-Goog-SignedHeaders=host",
    "accessible_facilities": [],
    "updated_at": "2021-07-19T09:50:58.769119Z",
    "created_at": "2020-09-19T06:44:11Z"
}
```