# Info

Group: Request
Method: POST
Note: update status for request item (supplier)
Status: Done
Url: /user/requests/update_processing/

R**equest items status**

```json
processing: 0
done:       1
```

**Example request**

```json
{      
	request_id    int
  request_items: [{
    item_id     int
    status      int //[0,1]
    attachments types.StringArray
  }]                               
}
```

**Example response**

```tsx
{
    "message": "Processing has been updated",
    "success": true
}
```