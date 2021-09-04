# Info

Group: Request
Method: POST
Note: update confirm status for request
Status: In progress
Url: /user/requests/complete_investigation/

**Example request**

```json
{      
	request_id    int                                  
}
```

**Example response**

```tsx
{
    "message": "Request is waiting to be confirmed",
    "success": true
}
```