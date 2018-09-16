# 登录功能

> 总路径：/mobile/v1_0/user

* 地址：`/login`
* 演示地址：[localhost:8899//mobile/v1_0/user/login?userName=1&passWorld=123](localhost:8899//mobile/v1_0/user/login?userName=1&passWorld=123)
* 请求方式：`POST` [GET 和 POST 均支持，建议使用 POST]
* 请求参数


|字段|说明|是否必须|类型|
|---|---|---|---|
| `userName` |`用户名`|`Y`|`String`|
| `passWorld` |`密码`|`Y`|`String`|

* 返回参数 

``` json
{
  "status":"0001",
  "msg":"success"
}
```

* 返回字段说明

|返回值字段|字段说明|字段类型|备注|
|---|---|---|---|
|status|状态码|String|0001 表示请求成功|
|msg|状态对应的信息|String|有成功失败等信息|








