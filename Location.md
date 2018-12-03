## 获取用户所在城市

获取用户当前位置所在的城市

* ### **请求地址**

> /{prefix}/location

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| lng | string | Y | 经度 |
| lat | string | Y | 纬度 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "cityid": 1,
        "cityname": "北京"
    }
}
```



