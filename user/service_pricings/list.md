# Info

Group: Service Pricing
Method: GET
Status: Done
Url: /user/service_pricings/list

**Parameter**

- offset: number
- limit: number

**Example request**

```json
user/service_pricings/list?offset=0&limit=1
```

**Example response**

```json
//when there is pagination
{
    "total_count": 20,
    "offset": 0,
    "data": [
        {
            "id": 1,
            "partner_id": 1,
            "service_id": 1,
            "description": "description",
            "price": 100000,
            "unit": "cái",
            "token": "'1':1",
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z",
            "service": {
                "id": 1,
                "name": "Cleaning Service",
                "comment": "No comment",
                "field_id": 2,
                "token": "'1':1 'cleaning':2 'comment':5 'no':4 'service':3",
                "created_at": "2020-09-19T06:44:11Z",
                "updated_at": "2020-09-19T06:44:11Z",
                "deleted_at": null
            },
            "partner": {
                "id": 1,
                "company_name": "247BPO",
                "phone": "0",
                "address": "HCM",
                "tax_number": "111111111",
                "type": 0,
                "token": "'0':3,6 '1':1 '111111111':5 '247bpo':2 'hcm':4",
                "address_district_id": 1,
                "address_ward_id": 4,
                "address_province_id": 1,
                "created_at": "2020-09-13T22:24:23Z",
                "updated_at": "2020-09-13T22:24:23Z",
                "deleted_at": null
            }
        }
    ]
}

//get all
[
    {
            "id": 1,
            "partner_id": 1,
            "service_id": 1,
            "description": "description",
            "price": 100000,
            "unit": "cái",
            "token": "'1':1",
            "created_at": "2020-09-19T06:44:11Z",
            "updated_at": "2020-09-19T06:44:11Z",
            "service": {
                "id": 1,
                "name": "Cleaning Service",
                "comment": "No comment",
                "field_id": 2,
                "token": "'1':1 'cleaning':2 'comment':5 'no':4 'service':3",
                "created_at": "2020-09-19T06:44:11Z",
                "updated_at": "2020-09-19T06:44:11Z",
                "deleted_at": null
            },
            "partner": {
                "id": 1,
                "company_name": "247BPO",
                "phone": "0",
                "address": "HCM",
                "tax_number": "111111111",
                "type": 0,
                "token": "'0':3,6 '1':1 '111111111':5 '247bpo':2 'hcm':4",
                "address_district_id": 1,
                "address_ward_id": 4,
                "address_province_id": 1,
                "created_at": "2020-09-13T22:24:23Z",
                "updated_at": "2020-09-13T22:24:23Z",
                "deleted_at": null
            }
        }
]
```