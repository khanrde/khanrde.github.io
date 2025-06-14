---
title: 美国地址生成器
---

```python
# website:https://www.meiguodizhi.com/

import requests

url = "https://www.meiguodizhi.com/api/v1/dz"

data = {
    "city": "",
    "path": "/",
    "method": "refresh"
}

response = requests.post(url, json=data)

print("Status Code:", response.status_code)
print("Response Content:", response.text)
```

