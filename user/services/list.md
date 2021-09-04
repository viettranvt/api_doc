# Info

Group: Service
Method: GET
Status: Done
Url: /user/services/list

**Parameter**

- offset: number
- limit: number
- filter: json object  //TODO

**Example request**

```json
{
}
```

**Example response**

```json
//when there is pagination
{
    "total_count": 9,
    "offset": 0,
    "data": [
        {
            "id": 1,
            "name": "Cleaning Service",
            "comment": "No comment",
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z"
        }
    ]
}

//get all
[
    {
          "id": 1,
          "name": "Cleaning Service",
          "comment": "No comment",
          "created_at": "2020-09-19T06:44:11Z",
          "updated_at": "2020-09-19T06:44:11Z"
     }
]
```