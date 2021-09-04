# Info

Group: Request
Method: POST
Note: add request items for customer
Status: Done
Url: /user/requests/add_items/

**Example request**

```json
{      
	request_id       int                     
  items: [{
		item_id     int        
		amount      null.Int   
		description null.String 
    attachments types.StringArray
	}]                    
}
```

**Example response**

```tsx
{
    "message": "Request items are created",
    "success": true
}
```