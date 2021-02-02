HTTP POST:

```
POST /micropub HTTP/1.1
Host: example.com
Content-type: application/x-www-form-urlencoded
Authorization: Bearer XXXXXXX

h=entry
&content=Hello+World
```

cURL:

```
curl https://example.com/micropub -d h=entry -d "content=Hello World" -H "Authorization: Bearer XXXXXXX"
```
