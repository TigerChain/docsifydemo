# Get individual user information

> Total path：/mobile/v1_0/user

* Address：`/fetchuserinfo`
* Demo address：[localhost:8899//mobile/v1_0/user/fetchuserinfo?uid=0001](localhost:8899//mobile/v1_0/user/fetchuserinfo?uid=0001)
* Request method：`GET`
* Request parameter


|Field|Description|Is it necessary|type|
|---|---|---|---|
| `uid` |User ID|`Y`|String|


* Return parameter  

``` json
{
    "status": "0001",
    "msg": "success",
    "data": {
        "uname": "TigerChain",
        "age": 28,
        "sex": "male",
        "address": "Shaanxi, China",
        "phone": "1**********"
    }
}
```

* Return field description

|Return value field|Field description|Field Type|Remarks|
|---|---|---|---|
|`status`|`状态码`|`String`|`0001` 表示请求成功|
|`msg`|`状态对应的信息`|`String`|有成功失败等信息|
|`data`|`返回数据json对象`|`jsonObject`|是一个对象|
|`uname`|`用户姓名`|`String`|data 中的字段|
|`...`|`...`|`...`|`...为了显示，其它省略`|
