## 微信小程序用户登陆接口

小程序用户注册接口

* ### **请求地址**

> /{prefix}/auth/wxlogin

* ### **请求方式**

> POST

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| code | string | Y | 微信数据 |
| iv | string | Y | 微信数据 |
| encrypt_data | string | Y | 微信数据 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "access_token": "fsadtegsaf",
        "token_type": "bearer",
        "user": {
            "name": "小明"
        }
    }
}
    
```

