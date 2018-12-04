## 获取分类栏目下的搜索配置信息

获取分类栏目下的搜索配置信息

* ### **请求地址**

> /{prefix}/category/condition

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| catid | int | Y | 分类ID |
| cityid | int | N | 城市ID |

* ### **返回示例**

```json
{
  "code": 200,
  "message": "success",
  "data": {
    "breadCrumbs": [
      {
        "catid": 246,
        "catname": "商铺转让"
      },
      {
        "catid": 528,
        "catname": "酒楼餐饮",
        "parentid": 246
      },
      {
        "catid": 639,
        "catname": "早餐店"
      }
    ],
    "conditions": {
      "category": [
        {
          "catid": 528,
          "catname": "酒楼餐饮"
        },
        {
          "catid": 529,
          "catname": "美容美发"
        }
      ],
      "area": [
        {
          "areaid": 1,
          "areaname": "朝阳"
        },
        {
          "areaid": 2,
          "areaname": "海淀"
        }
      ],
      "others": [
        {
          "title": "面积",
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
          "identifier": "position"
        },
        {
          "title": "租金",
          "identifier": "rent",
          "list": [
            {
              "id": 0,
              "name": "不限"
            },
            {
              "id": "1-2000",
              "name": "2000元以下"
            },
            {
              "id": "2000~5000",
              "name": "2000~5000元"
            }
          ]
        }
      ]
    }
  }
}
```



