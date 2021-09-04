# Info

Group: Request
Method: POST
Note: Approve implementation
Status: Done
Url: /user/requests/approve_implementation/

R**equest items status**

```json
processing: 0
done:       1
confirmed:  2
rejected:   3
```

**Example request**

```json
{      
	request_id             int                     
  request_items[{
			item_id            int
      is_comfirmed       bool
	}]
}
```

**Example response**

```tsx
{
    "message": "Request item approved",
    "success": true
}
```