# Info

Group: Request
Method: GET
Note: Nếu là service khác thì BE trả về service_id = null, service_name=string, service_price=float. Còn service bình thường thì BE trả về service_id = number, service_name=null, service_price=0.0
Status: Done
Url: /users/requests/detail/<id>

**Example request**

```json
user/requests/detail/1
```

**Example response**

```tsx
{
    "id": 4,
    "facility": {
        "id": 4,
        "name": "Co so 4",
        "owned_by": 2,
        "created_by": 1,
        "address_district_id": 1,
        "address_ward_id": 1,
        "address_province_id": 1,
        "address": "Test address 4",
        "token": "'4':1,4 'co':2 'so':3",
        "created_at": "2020-09-19T06:44:11Z",
        "updated_at": "2020-09-19T06:44:11Z",
        "deleted_at": null
    },
    "status": 3,
    "customer_items": null,
    "supplier_items": null,
    "customer": {
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
    "supplier": {
        "id": 3,
        "company_name": "So Do",
        "phone": "37543348",
        "address": "15 Trịnh Hậu Quý",
        "tax_number": "9876779300",
        "type": 2,
        "token": "'15':5 '2':10 '3':1 '37543348':4 '9876779300':9 'do':3 'hậu':7 'quý':8 'so':2 'trịnh':6",
        "address_district_id": 1,
        "address_ward_id": 6,
        "address_province_id": 1,
        "created_at": "2020-09-13T22:24:23Z",
        "updated_at": "2020-09-13T22:24:23Z",
        "deleted_at": null
    },
    "investigate_date": null,
    "investigate_slots": [
        "12h-14h",
        "14h-16h",
        "16h-18h"
    ],
    "booked_investigate_slot": "12h-14h",
    "created_by": {
        "id": 1,
        "username": "admin",
        "full_name": "",
        "partner_id": 1
    },
    "created_at": "2020-09-19T06:44:11Z",
    "updated_at": "2020-09-19T06:44:11Z",
    "type": 0,
    "handlers": [
        {
            "id": 4,
            "request_id": 4,
            "handled_by": 8,
            "created_at": "2021-07-27T09:41:08.8728Z",
            "updated_at": "2021-07-27T09:41:08.8728Z"
        }
    ],
    "supervisor": {
        "id": 2,
        "avatar": null,
        "username": "cheer.admin",
        "fullName": "Cheer Admin",
        "phone": "(+84) 0973 943 579",
        "email": "cheer.admin@gmail.com"
    }
}
```