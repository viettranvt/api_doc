# Info

Group: Request
Method: POST
Status: Done
Url: /user/requests/assign_handler

**Example request**

```json
{
		handler_ids []int 
		request_id  int
}
```

**Example response**

```tsx
{
    "success": true,
    "message": "Assigned successsfully"
}
```