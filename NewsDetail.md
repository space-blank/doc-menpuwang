## 新闻详情页

新闻详情页

* ### **请求地址**

> /{prefix}/news/detail

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| nid | int | Y | 新闻ID |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "breadcrumbs": [
            {
                "catid": 0,
                "catname": "新闻资讯"
            },
            {
                "catid": 1,
                "catname": "报刊专栏"
            }
        ],
        "info": {
            "id": 2181,
            "iscommend": 0,
            "isfocus": "",
            "isbold": 0,
            "isjump": 0,
            "redirect_url": "",
            "title": "252期",
            "keywords": "",
            "catid": 1,
            "begintime": 1539674458,
            "introduction": "",
            "content": "<img src=\"/attachment/editor/201810/1539673364ythtu.jpg\" alt=\"\" />",
            "author": "",
            "source": "门铺网",
            "hit": 70,
            "perhit": 1,
            "imgpath": "/attachment/editor/201810/1539673364ythtu.jpg",
            "html_path": "",
            "cityid": 281
        }
    }
}
```



