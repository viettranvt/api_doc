# Info

Group: Profile
Method: PUT
Status: Done
Url: /user/profiles/update_password

**Example request**

```json
{
   current_password    string
	 new_password        string
}
```

**Example response**

```json
{
    "success": true,
    "message": "Password update successful"
}
```