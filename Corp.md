## 输入关键词搜索

输入关键词搜索

* ### **请求地址**

> /{prefix}/corp/list

* ### **请求方式**

> GET

* ### **请求参数**

无

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": [
        {
            "corpid": 6,
            "corpname": "休闲娱乐",
            "children": [
                {
                    "corpid": 14,
                    "corpname": "酒吧"
                },
                {
                    "corpid": 15,
                    "corpname": "茶楼"
                }
            ]
        },
        {
            "corpid": 7,
            "corpname": "餐饮美食",
            "children": [
                {
                    "corpid": 24,
                    "corpname": "快餐"
                },
                {
                    "corpid": 25,
                    "corpname": "火锅"
                }
            ]
        }
    ]
}
```



