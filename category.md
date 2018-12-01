#### 获取分类列表

获取分类列表

<li> **请求地址** </li>

> category/index

<li>   **请求方式** </li> 

> *GET*  **请求方式**

<li>**请求参数**</li>

请求参数     |    参数类型   | 是否必须     |   参数说明   
:-----------| :-----------: | -----------:| -----------:
 cityid     | numeric       | N           |  城市ID，默认为1


<li> **返回示例** </li>
    
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






