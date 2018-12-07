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
        "catid": 3,
        "catname": "成交案例"
      }
    ],
    "info": {
      "id": 2172,
      "iscommend": 0,
      "isfocus": "",
      "isbold": 0,
      "isjump": 0,
      "redirect_url": "",
      "title": "捡漏子！岳麓区大学城奶茶店转让",
      "keywords": "",
      "catid": 3,
      "begintime": "2018-10-07 02:22:41",
      "introduction": "",
      "content": "<table border=\"0\" cellpadding=\"0\" cellspacing=\"0\" width=\"598\" style=\"width:449pt;\">\r\n\t<tbody>\r\n\t\t<tr>\r\n\t\t\t<td height=\"22\" width=\"402\">\r\n\t\t\t\t已转&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 捡漏子！岳麓区大学城奶茶店转让\r\n\t\t\t</td>\r\n\t\t\t<td width=\"196\">\r\n\t\t\t\t电话：18874140626\r\n\t\t\t</td>\r\n\t\t</tr>\r\n\t</tbody>\r\n</table>",
      "author": "",
      "source": "门铺网",
      "hit": 190,
      "perhit": 1,
      "imgpath": "http://www.money.com",
      "html_path": "",
      "cityid": 158
    },
    "recommends": [
      {
        "id": 2020,
        "title": "日营5千物流学院食堂档口优转",
        "begintime": "05-28"
      },
      {
        "id": 1442,
        "title": "心华大药房2天转出",
        "begintime": "11-11"
      },
      {
        "id": 1441,
        "title": "发亿超市第二次在同城信息成功转出",
        "begintime": "11-11"
      },
      {
        "id": 1440,
        "title": "名门雅秀减肥美容馆7天转出",
        "begintime": "11-11"
      }
    ]
  }
}
```



