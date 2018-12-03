## 获取用户所在城市

获取用户当前位置所在的城市

* ### **请求地址**

> /{prefix}/location

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| lng | float | Y | 经度 |
| lat | float | Y | 纬度 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "location": {
            "cityid": 1,
            "cityname": "北京"
        },
        "list": [
            {
                "catid": 246,
                "catname": "商铺转让",
                "children": [
                    {
                        "catid": 528,
                        "catname": "酒楼餐饮"
                    },
                    {
                        "catid": 529,
                        "catname": "美容美发"
                    },
                    {
                        "catid": 530,
                        "catname": "百货超市"
                    },
                    {
                        "catid": 531,
                        "catname": "服饰鞋包"
                    }
                ]
            },
            {
                "catid": 247,
                "catname": "商铺转让",
                "children": [
                    {
                        "catid": 528,
                        "catname": "酒楼餐饮"
                    },
                    {
                        "catid": 529,
                        "catname": "美容美发"
                    },
                    {
                        "catid": 530,
                        "catname": "百货超市"
                    },
                    {
                        "catid": 531,
                        "catname": "服饰鞋包"
                    }
                ]
            },
        ]
    }
}
```



