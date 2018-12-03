## 切换城市

获取可以切换的城市列表

* ### **请求地址**

> /{prefix}/location/change

* ### **请求方式**

> GET

* ### **请求参数**

无

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "hot_cities": [
            {
                "cityid": 1,
                "cityname": "北京"
            },
            {
                "cityid": 2,
                "cityname": "上海"
            }
        ],
        "pin_yin": [
            "A",
            "B" 
        ],
        "cities": {
            "A": [
                {
                    "cityid": 45,
                    "cityname": "安庆"
                },
                {
                    "cityid": 95,
                    "cityname": "安顺"
                }
            ],
            "B": [
                {
                    "cityid": 1,
                    "cityname": "北京"
                },
                {
                    "cityid": 40,
                    "cityname": "蚌埠"
                }
            ]
        }
    }
}
    
```

