# Info

Group: Request
Method: GET
Status: Done
Url: /user/requests/list

**Parameters**

- offset: number
- limit: number
- sort: updated_at:asc || updated_at:desc

**Example request**

```json
user/requests/list?limit=1&offset=0
```

**Example response**

```tsx
{
    "total_count": 17,
    "offset": 0,
    "data": [
        {
            "id": 1,
            "title": "Request 1",
            "status": 0,
            "supervisor_id": 2,
            "facility": "Co so 1",
            "address": "Test address 1",
            "requested_by": 2,
            "created_by": 1,
            "updated_by": 1,
            "token": null,
            "investigate_date": null,
            "confirmed_date": null,
            "confirm_description": null,
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z",
            "customer_name": "Cheers",
            "supplier_name": "So Do",
            "handlers": [
                {
                    "id": 1,
                    "request_id": 1,
                    "handled_by": 8,
                    "created_at": "2021-07-27T09:41:08.8728Z",
                    "updated_at": "2021-07-27T09:41:08.8728Z",
                    "handler": {
                        "id": 8,
                        "avatar": null,
                        "username": "sodo.giang",
                        "fullName": "Sodo User Giang",
                        "phone": "(+84) 0973 222 333",
                        "email": "sodo.giang@gmail.com"
                    }
                }
            ],
            "supervisor": {
                "id": 2,
                "avatar": "https://247bpo.storage.googleapis.com/avatar/2/abc.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=bucket-access%40bpo-247.iam.gserviceaccount.com%2F20210727%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210727T132129Z&X-Goog-Expires=899&X-Goog-Signature=40783989f5aaddb88cb7c009237cef0c86737bf95b344db42d11d779110aa4bfe2bd426c7f61de849d5872ee665af8fab6f58ed539428fc3662ce5b4434a39c6dba7444ef41995d6efd3868873ef96e23ca0068e1d47153f96852afe38821cf4d239e04f75ae90eebbab03a10358874a1104f905ed46bdc1b64c2e09d63611b4b6e0443a8dc1dcd1cdc197b950f1ff667e6a4b0980fed1e91ece09162bec1fd811c268a5f8fafd80cc3801866a260ac3fcefe638dc63f6c3bdc0ec5b8ad5354243b5f0b23015893ef23755b281d5513fa923176e5f664cf7a4b748a856ccd6166178577f7a00069e5349d7668343252d695b6bfa84d43e860eb63cb3f40f1286&X-Goog-SignedHeaders=host",
                "username": "cheer.admin",
                "fullName": "Cheer Admin",
                "phone": "0328839669",
                "email": "cheer.admin@gmail.com"
            }
        }
    ]
}
```