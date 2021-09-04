# Info

Group: Request
Method: POST
Status: Done
Url: /user/requests/book_investigation

**Example request**

```json
{
		request_id               int       
		investigate_date         time.Time 
		booked_investigate_slot  string
    handler_ids              null.IntArray    
}
```

**Example response**

```tsx
{
    "message": "Investigation date is booked",
    "success": true
}
```