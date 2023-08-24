# README

Project exists to remind me how to use contexts in a Go server with Gorilla. Because I forget.

Originally nabbed from here: https://gist.github.com/AxelRHD/2344cc1105afc06723b363f21486dec8 

Test with `curl`.

```bash
curl http://localhost:3333/secret -H "Authorization: Basic bG9naW46cGFzc3dvcmQ="
# or
curl http://localhost:3333/secret -u "login:password"
```

