# Info

Group: Request
Method: POST
Note: detele request item for supplier and customer
Status: Done
Url: /user/requests/delete_items/

**Example request**

```json
{      
	request_id  int                     
	item_ids    []int  //nullable
	item_id     int    //nullable           
}
```

**Example response**

```tsx
{
    "totalCount": 1
}
```