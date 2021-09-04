# Info

Group: Item
Method: GET
Status: Done
Url: /user/items/list

**Parameters**

- offset: number
- limit: number
- filter: {"field":"facility_id","op":"in","val":["1"]}] or {"field":"owned_by","op":"eq","val":["1"]}]

// filter owned_ by only for supllier

**Example request**

```json
user/items/list?filter=[{"field":"facility_id","op":"eq","val":["1"]}]&limit=1&offset=0
```

**Example response**

```json
{
    "total_count": 5,
    "offset": 0,
    "data": [
        {
            "id": 1,
            "name": "Tủ lanh phòng bếp",
            "owned_by": 2,
            "token": "'1':1 'chính':8 'lg':3 'lạnh':5 'phòng':7 'tủ':4 'xb123v55y9':2 'ở':6",
            "facility_id": 1,
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z",
            "deleted_at": null,
            "specifications": "10L 15kg 12x12x8",
            "serial_number": "XB123V55y9",
            "branch": "LG",
            "description": "Tủ lạnh ở phòng chính "
        }
    ]
}
```