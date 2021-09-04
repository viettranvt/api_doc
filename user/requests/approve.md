# Info

Group: Request
Method: POST
Note: accept customer_agreement in request items.
Status: Done
Url: /user/requests/approve/

**Example request**

```json
{      
	request_id             int                     
  request_items[{
			item_id            int
      customer_agreement bool
	}]
}
```

**Example response**

```tsx
{
    "message": "Requested approved",
    "success": true
}
```