## 用户添加门铺展示页面

用户添加门铺展示页面

* ### **请求地址**

> /{prefix}/member/post

* ### **请求方式**

> GET

* ### **请求参数**

| 请求参数 | 参数类型 | 是否必须 | 参数说明 |
| :---: | :---: | :---: | :---: |
| uid | string | Y |用户ID |
| catid | int | Y | 分类ID |
| areaid | int | Y | 二级地域ID |
| streetid | int | Y | 三级地域ID |

* ### **返回示例**

```json
{
  "code": 200,
  "message": "success",
  "data": {
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
    "street": "南菜园", //地区
    "form": [ //后台生成的需要填写的表单
      {
        "title": "面积", //页面显示的文字
        "identifier": "acreage", //表单提交的参数名
        "value": "平方"
      },
      {
        "title": "来源",
        "identifier": "position",
        "value": {
          "1": "个人",
          "2": "经纪人"
        }
      },
      {
        "title": "租金",
        "identifier": "rent",
        "value": {
          "param": "danwei",
          "value": [
            "元/㎡/天",
            "元/月"
          ]
        }
      },
      {
        "title": "转让费",
        "identifier": "zhuanrang",
        "value": "万元"
      }
    ],
    "upImage": 1 //页面中是否需要有上传图片的功能
  }
}
```



