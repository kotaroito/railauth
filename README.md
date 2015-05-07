railoauth
=========

### 
```bash
curl -u "$CLIENT_ID:$CLIENT_SECRET" -F "grant_type=authorization_code" -F "code=$CODE" -F "redirect_uri=http://localhost:3000/" -XPOST http://localhost:3000/oauth/token
```

```bash
curl -s -XGET -H "Authorization: Bearer $ACCESS_TOKEN" http://localhost:3000/api/v1/me.json
```
