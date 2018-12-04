## 获取三级地域

获取该城市下的市/县/区/街道

* ### **请求地址**

> /{prefix}/location/street

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| areaid | int | Y | 地域ID |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": [
        {
            "streetid": 63,
            "streetname": "北苑"
        },
        {
            "streetid": 64,
            "streetname": "来广营"
        }
    }
}
```



