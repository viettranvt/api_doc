# Info

Group: Request
Method: POST
Status: Done
Url: /user/requests/investigate_slots/

**Example request**

```json
{
		investigate_slots     types.StringArray 
		request_id            int
}
```

**Example response**

```tsx
{
    "message": "Investigation slots is updated",
    "success": true
}
```