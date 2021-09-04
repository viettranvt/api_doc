# Info

Group: Request
Method: POST
Note: singUrl for customer
Status: Done
Url: /user/requests/sign_upload

**Example request**

```json
{
		file_name    string      
		content_type string      
		directory    null.String
}

//input array
[{
		file_name    string      
		content_type string      
		directory    null.String
}]
```

**Example response**

```tsx
[
    {
        "image_name": "image1.png",
        "url": "https://247bpo.storage.googleapis.com/2/image1.png?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=bucket-access%40bpo-247.iam.gserviceaccount.com%2F20210616%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210616T132440Z&X-Goog-Expires=899&X-Goog-Signature=135f0cf1bb84e5c8a90f9467d51334ec938ead5de5df8cfb7d9c22156a57b0ccdf9b2d16f34e28868e54bb20854543fec324d8a1d6600eaa3ebddc63cde3163263c3011d045e5f6632fa04c2ce29d3d07e468a971a13aed086a0a118eb2f85e626d030e2a6875347989c364f1e477d59c2212e49d04bf59302beb05d9e715bf1ae9c3b7aaca1080463cb8fb0ca9314b58c3a37afe1e7390869ad148fc3986e46bf9b6c100ef9a151f3442c8d0ce7a5b2a135b7a57f6f50e51e8943eb6e2f40690f8a761224988b286cd046f162f117819b0008f78fb2d0618016cb6ec93cc37b57c4e8d726e0b383c58b55c399d8de1d0df508b9a9f5abac446a3c05b8eb5b00&X-Goog-SignedHeaders=host"
    }
]
```