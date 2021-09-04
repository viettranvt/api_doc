# Info

Group: Request
Method: POST
Note: add request items for supplier
Status: Done
Url: /user/requests/add_investigate_item/

**Example request**

```json
{      
	request_id       int                     
  items: [{
			item_id           int          
			reason            null.String 
			service_id        null.Int    
			solution          null.String  
			amount            null.Int     
			item_pricing      null.Float64 
			labor_pricing     null.Float64 
			unit              null.String
      attachments       types.StringArray
      service_name      null.string
      service_price     null.float64
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