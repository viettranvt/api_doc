# Info

Group: Item
Method: GET
Status: Done
Url: /user/items/ldetail/<id>

**Example request**

```json
user/items/detail/1
```

**Example response**

```json
{
    "id": 1,
    "name": "Tủ lanh phòng bếp",
    "owned_by": 2,
    "token": "'1':1 'chính':8 'lg':3 'lạnh':5 'phòng':7 'tủ':4 'xb123v55y9':2 'ở':6",
    "facility_id": 1,
    "created_at": "2020-09-19T06:44:11Z",
    "updated_at": "2020-09-19T06:44:11Z",
    "deleted_at": null,
    "serial_number": "XB123V55y9",
    "branch": "LG",
    "description": "Tủ lạnh ở phòng chính "
}
```