# Info

Group: Request
Method: POST
Note: update processing status for request
Status: In progress
Url: /user/requests/complete_confirming

**Example request**

```json
{      
	request_id   int                    
}
```

**Example response**

```tsx
{
    "message": "Request has been confirmed",
    "success": true
}
```