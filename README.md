# 

# 摘要

## 1. 项目服务器地址

> 线上部署地址：[http://api.menpuwang.com](http://api.menpuwang.com)

URL地址变量{prefix}： /api/v1

## 2. 服务端下发数据全局格式

服务端下发数据格式为 `json` 格式, 全局数据结构如下：

```json
{
    'code' : 200,
    'message' : '信息',
    'data' : {
        // 具体的接口数据
    }
}
```

## 3. 请求接口需携带信息

用户登录之后，要通过http发送一个需要认证通过的请求，需要设置Authorization头：

> Authorization: Bearer {yourtokenhere}

或者将token信息包含到URL中：

> [http://api.mysite.com/me?token={yourtokenhere}](http://api.mysite.com/me?token={yourtokenhere})



