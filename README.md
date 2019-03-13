### shortuuid
---
.py
https://github.com/skorokithakis/shortuuid

.go
https://github.com/lithammer/shortuuid

```py
import shoruuid

import uuid ; u = uuid.uuid4() ; u
s = shortuuid.encode(u) ; s
shortuuid.decode(s) == u
short = s[:7] ; short
h = shortuuid.decode(short)
shortuuid.decode(shortuuid.encode(h)) == h

su = shoruuid.ShortUUID(alphabe="xxx")
su.uuid()
su.get_alphabe()
su.set_alphabet("xxx")
su.get_alphabet()

uuid = encode(decode(uuid))
```

```sh
shortuuid.uuid()

shortuuid.uuid(name="example.com")
shortuuid.uuid(name="http://example.com")
shortuuid.ShortUUID().random(length=22)
shortuuid.get_alphabet()
shortuuid.set_alphabet("xxxxxxx")
shortuuid.uuid()

shortuuid.get_alphabet()
```

```
```


