---
Title: Encoding to a String
Id: 15705
Score: 0
---
```go
str := base64.StdEncoding.EncodeToString([]byte(`foo bar`))
fmt.Println(str)
// Output: Zm9vIGJhcg==
```
