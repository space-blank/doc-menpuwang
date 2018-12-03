## 获取分类列表

获取分类列表

* ### **请求地址**

> /{prefix}/category/list

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
            "catid": 246,
            "catname": "商铺转让",
            "icon": "http://localhost",
            "children": [
                {
                    "catid": 528,
                    "catname": "酒楼餐饮"
                },
                {
                    "catid": 529,
                    "catname": "美容美发"
                }
            ]
        },
        {
            "catid": 519,
            "catname": "商铺租售",
            "icon": "http://localhost",
            "children": [
                {
                    "catid": 584,
                    "catname": "酒楼餐饮 "
                },
                {
                    "catid": 585,
                    "catname": "美容美发"
                }
            ]
        }
    }
}
```



