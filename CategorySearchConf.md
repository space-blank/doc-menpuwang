## 获取分类栏目下的搜索配置信息

获取分类栏目下的搜索配置信息

* ### **请求地址**

> /{prefix}/category/config

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


