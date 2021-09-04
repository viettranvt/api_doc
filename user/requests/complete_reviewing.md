# Info

Group: Request
Method: POST
Note: Complete reviewing (customer) . move status  to AdminOverview
Status: In progress
Url: /user/requests/complete_reviewing/

**Example request**

```json
{      
	request_id    int                             
}
```

**Example response**

```tsx
{
    "message": "Review has been completed",
    "success": true
}
```