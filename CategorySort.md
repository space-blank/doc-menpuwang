## 分类搜索结果列表页

分类搜索结果列表页

* ### **请求地址**

> /{prefix}/category/sort

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| catid | int | Y | 分类ID |
| cityid | int | Y | 分类ID |
| page | int | N | 当前页码 |
| pageSize | int | N | 每页条数 |

* ### **返回示例**

```json
{
  "code": 200,
  "message": "success",
  "data": {
    "breadcrumbs": [ //导航
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
    "conditions": { //搜索的条件选项
      "category": [ //分类
        {
          "catid": 638,
          "catname": "餐馆"
        },
        {
          "catid": 639,
          "catname": "早餐店"
        }
      ],
      "area": [ //区域
        {
          "areaid": 1,
          "areaname": "朝阳"
        },
        {
          "areaid": 2,
          "areaname": "海淀"
        }
      ],
      "others": [ //这几个搜索条件是可配置
        {
          "title": "面积",
          "type": "number",
          "identifier": "acreage",
          "list": [
            {
              "id": 0,
              "name": "不限"
            },
            {
              "id": "1~30",
              "name": "50平米以内"
            }
          ]
        },
        {
          "list": [
            {
              "id": 0,
              "name": "不限"
            },
            {
              "id": 1,
              "name": "个人"
            },
            {
              "id": 2,
              "name": "经纪人"
            }
          ],
          "title": "来源",
          "type": "radio",
          "identifier": "position"
        },
        {
          "title": "租金",
          "type": "number",
          "identifier": "rent",
          "list": [
            {
              "id": 0,
              "name": "不限"
            },
            {
              "id": "1-2000",
              "name": "2000元以下"
            }
          ]
        }
      ]
    },
    "info": [
      {
        "areaname": "宣武",
        "id": 87728,
        "title": "Lottery",
        "hit": 0,
        "img_path": "/attachment/information/201812/pre_1544092578mgflm.jpg",
        "ifred": 0,
        "ifbold": 0,
        "img_count": 1,
        "upgrade_type": 1,
        "contact_who": "老板本人",
        "begintime": 1544092578,
        "danwei": "元/㎡/天",
        "zhuanrang": "107",
        "catname": "餐馆",
        "extra": {
          "acreage": {
            "title": "面积",
            "value": "97平方"
          },
          "position": {
            "title": "来源",
            "value": "经纪人"
          },
          "rent": {
            "title": "租金",
            "value": "1070"
          }
        }
      }
    ]
  }
}
```



