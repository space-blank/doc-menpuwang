## 用户我的收藏

我的收藏列表

* ### **请求地址**

> /{prefix}/member/favor

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| uid | int | Y | 用户ID |
| page | int | N | 当前页码 |
| pageSize | int | N | 每页条数 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": [
        {
            "fid": 43,
            "infoid": 50255, //消息的ID
            "catname": "餐馆", //分类名称
            "title": "纯一楼小区餐馆急转",
            "intime": "2017-04-26 07:01:53" //收藏的时间
        },
        {
            "fid": 42,
            "infoid": 48470,
            "catname": "家居建材",
            "title": "华南城家居建材店转让（可空转）",
            "intime": "2017-04-26 05:46:25"
        }
    ]
}
```



