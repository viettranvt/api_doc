# Info

Group: Profile
Method: POST
Status: Done
Url: /user/profiles/sign_upload

**Example request**

```json
{
    file_name      string
    content_type   string
    directory      null.string
}
```

**Example response**

```json
{
    "image_name": "image1.png",
    "url": "https://247bpo.storage.googleapis.com/avatar/1/image1.png?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=bucket-access%40bpo-247.iam.gserviceaccount.com%2F20210719%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210719T064316Z&X-Goog-Expires=899&X-Goog-Signature=673bbd2f9d8f37e1a7876b9b01369dc2960b0dddec82eb0b003d5cde452420aa9b3e06f33abc357a1e88264ece9145192e35ef5308aa13dd26bd92b958be65ef65669688b51bbe47fd9f78d18c3e85b3661405156df2ea4e19710844377ac54dc82198ff3f9c32dfe2f2cbc32fb6b0fc813134056d438eb60318cdd717d3981fd8a0888a84fd0eefdde60ab8806d73bac743e9752223ca8d58f9fa4a46c36f423340741f5a360810da200ef8372500b2a7476ce5be02f36ba11b5c5cbe81aafc3fb132cb6d81f18f627e80143bb6f1e82e53f85e370ee36a90652b390c251a10924c2962d0e7d542ed37337096cf14694199d84c5ea21226d3b691a857aefb5e&X-Goog-SignedHeaders=content-type%3Bhost"
}
```