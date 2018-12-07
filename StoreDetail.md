## 新闻详情页

新闻详情页

* ### **请求地址**

> /{prefix}/information/detail

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| iid | int | Y | 店铺信息ID |
| cityid | int | N | 城市ID |

* ### **返回示例**

```json
{
  "code": 200,
  "message": "success",
  "data": {
    "site_name": "门铺网",
    "breadcrumbs": [
      {
        "catid": 246,
        "catname": "商铺转让"
      },
      {
        "catid": 528,
        "catname": "酒楼餐饮"
      },
      {
        "catid": 638,
        "catname": "餐馆"
      }
    ],
    "detail": {
      "id": 87728,
      "catid": 638,
      "title": "Lottery",
      "begintime": 1544092578,
      "hit": 0,
      "cityid": 1,
      "endtime": "<font color=green>长期有效</font>",
      "img_count": 1,
      "qq": "3399510572",
      "tel": "13131313131",
      "contact_who": "老板本人",
      "content": "发的方法的发送到发送到发送到",
      "contactview": 1,
      "parentid": 528,
      "catname": "餐馆",
      "template_info": "info",
      "modid": 25,
      "usecoin": 0,
      "image": [
        {
          "prepath": "/attachment/information/201812/pre_1544092578mgflm.jpg",
          "path": "/attachment/information/201812/1544092578mgflm.jpg"
        }
      ],
      "extra": [
        {
          "title": "面积",
          "value": "97平方"
        },
        {
          "title": "来源",
          "value": "经纪人"
        },
        {
          "title": "租金",
          "value": "1070"
        }
      ]
    },
    "recommends": [
      {
        "id": 87728,
        "title": "Lottery",
        "begintime": "23小时前"
      }
    ]
  }
}
```



