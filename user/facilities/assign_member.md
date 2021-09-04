# Info

Group: Facility
Method: POST
Status: In progress
Url: /user/facilities/assign_member

**Parameters**

- all: boolean    //only input multiple

**Example request**

```json
//input single
{
   facility_id         int
   user_id             int

//input multiple
[{
   facility_id         int
   user_id             int
   line_num            null,int
}]
```

**Example response**

```json
//single response
{
    "id": 11,
    "user_id": 1,
    "facility_id": 1,
    "created_at": "2021-08-08T16:59:15.532011699Z",
    "updated_at": "2021-08-08T16:59:15.532011699Z"
}

//multi response
//when all = true
[
    {
        "id": 14,
        "user_id": 1,
        "facility_id": 1,
        "created_at": "2021-08-08T17:02:33.411529915Z",
        "updated_at": "2021-08-08T17:02:33.411529915Z"
    }
]

//when all = false
{
    "data": [
        {
            "id": 16,
            "user_id": 1,
            "facility_id": 1,
            "created_at": "2021-08-08T17:03:11.661748359Z",
            "updated_at": "2021-08-08T17:03:11.661748359Z"
        }
    ],
    "error": [
        {
            "line_num": 0,
            "error": "22"
        }
    ]
}
```