# Login function

> Total path：/mobile/v1_0/user

* Address：`/login`
* Demo address：[localhost:8899//mobile/v1_0/user/login?userName=1&passWorld=123](localhost:8899//mobile/v1_0/user/login?userName=1&passWorld=123)
* Request method：`POST` [GET and POST are supported, POST is recommended]
* Request parameter


|Field|Description|Is it necessary|type|
|---|---|---|---|
| `userName` |`username`|`Y`|`String`|
| `passWorld` |`passworld`|`Y`|`String`|

* Return parameter 

``` json
{
  "status":"0001",
  "msg":"success"
}
```

* Return field description

|Return value field|Field description|Field Type|Remarks|
|---|---|---|---|
|status|status code|String|0001 Indicates the request was successful|
|msg|Status corresponding information|String|Have success and other information|








