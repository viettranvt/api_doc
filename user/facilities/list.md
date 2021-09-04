# Info

Group: Facility
Method: GET
Status: Done
Url: /user/facilities/list

**Parameter**

- offset: number
- limit: number
- filter: json object  //TODO

**Example request**

```json
user/facilities/list?limit=1&offset=0
```

**Example response**

```json
{
    "total_count": 6,
    "offset": 0,
    "data": 
        {
            "id": 1,
            "name": "Co so 1",
            "owner": null,
            "author": null,
            "token": "'1':1,4 'co':2 'so':3",
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z",
            "deleted_at": null,
            "address_district": null,
            "address_ward": null,
            "address_province": null,
            "address": "Test address 1"
        }
    ]
}
```