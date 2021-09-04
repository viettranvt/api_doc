# Info

Group: Request
Method: POST
Note: update request items for customer
Status: Done
Url: /user/requests/update_items/

**Example request**

```json
{      
	request_id    int                     
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
    "message": "Request items are updated",
    "success": true
}
```