## 用户我的发布

我的发布信息

* ### **请求地址**

> /{prefix}/member/publish

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| uid | string | Y | 用户ID |
| page | int | N | 当前页码 |
| pageSize | int | N | 每页条数 |

* ### **返回示例**

```json
{
    "code": 200,
    "message": "success",
    "data": {
        "page": {
            "size": 10, //每页总条数
            "number": 1, //当前页码
            "total-pages": 39, //总页数
            "total-items": 384 //总条数
        },
        "page_data": [
            {
                "id": 87727,
                "title": "YAHOO<font color=red>竞拍</font>,上珍拍网,\r收藏酒哪个好",
                "img_path": "",
                "content": "珍拍网www.ZhenJP.com是国内最大的日本代拍、日本代购、雅虎拍卖、YAHOO竞拍、日拍、日",
                "userid": "金刚葫芦娃",
                "contact_who": "珍拍网",
                "hit": 10,
                "begintime": "18-10-20"
            },
            {
                "id": 87726,
                "title": "YAHOO<font color=red>竞拍</font>行业最低汇率,\r哈雷摩托车经销商",
                "img_path": "",
                "content": "珍拍网www.ZhenJP.com是国内最大的日本代拍、日本代购、雅虎拍卖、YAHOO竞拍、日拍、日",
                "userid": "金刚葫芦娃",
                "contact_who": "珍拍网",
                "hit": 0,
                "begintime": "18-10-20"
            }
        ]
    }
}
```



