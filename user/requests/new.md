# Info

Group: Request
Method: POST
Status: Done
Url: /user/requests/new

**Example request**

```json
{
	title             string               
	facility_id       int                     
	requested_by      int                    
	represented_by    null.Int               
	investigate_slots types.StringArray      
	type              int
  request_items: [{
		item_id     int        
		amount      null.Int   
		description null.String 
    attachments types.StringArray
	}]                    
}

//or
[{
	title             string               
	facility_id       int                     
	requested_by      int                    
	represented_by    null.Int               
	investigate_slots types.StringArray      
	type              int
  request_items: [{
		item_id     int        
		amount      null.Int   
		description null.String 
    attachments types.StringArray
	}]                    
}]
```

**Example response**

```tsx
{
    "id": 23,
    "title": "Yêu cầu mới",
    "status": 0,
    "type": 1,
    "supervisor_id": 2,
    "requested_by": 2,
    "created_by": 3,
    "updated_by": 3,
    "token": null,
    "investigate_date": null,
    "confirmed_date": null,
    "confirm_description": null,
    "created_at": "2021-07-27T13:24:19.844803865Z",
    "updated_at": "2021-07-27T13:24:19.844803865Z",
    "customer_name": "",
    "supplier_name": null
}

//input array[
    {
        "id": 29,
        "status": 0,
        "created_at": "0001-01-01T00:00:00Z",
        "updated_at": "0001-01-01T00:00:00Z"
    }
]
```