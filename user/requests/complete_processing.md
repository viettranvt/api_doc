# Info

Group: Request
Method: POST
Note: update reviewing status for request
Status: In progress
Url: /user/requests/complete_processing/

**Example request**

```json
{      
	request_id    int                             
}
```

**Example response**

```tsx
{
    "message": "Processing has been completed",
    "success": true
}
```