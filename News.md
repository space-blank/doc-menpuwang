## 输入关键词搜索

输入关键词搜索

* ### **请求地址**

> /{prefix}/news/list

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| catid | int | N | 分类ID |
| page | int | N | 当前页码 |
| pageSize | int | N | 每页条数 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "channel": [
            {
                "catid": 0,
                "catname": "最新"
            },
            {
                "catid": 1,
                "catname": "报刊专栏"
            }
        ],
        "response": {
            "page": {
                "size": 10,
                "number": 1,
                "total-pages": 203,
                "total-items": 2022
            },
            "page_data": [
                {
                    "id": 2181,
                    "title": "252期",
                    "imgpath": "http://localhost/attachment/editor/201810/1539673364ythtu.jpg",
                    "begintime": "10-16",
                    "introduction": ""
                },
                {
                    "id": 2180,
                    "title": "251期",
                    "imgpath": "http://localhost/attachment/editor/201810/1539673184hkk5s.jpg",
                    "begintime": "10-16",
                    "introduction": ""
                }
            ]
        }
    }
}
```



