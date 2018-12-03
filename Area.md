## 获取二级地域

获取所有城市

* ### **请求地址**

> /{prefix}/location/area

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| keyword | string | N | 关键词 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": [
        {
            "areaid": 1,
            "areaname": "朝阳"
        },
        {
            "areaid": 2,
            "areaname": "海淀"
        }
    }
}
```



