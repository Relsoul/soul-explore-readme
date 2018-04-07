# 规范与约束

### 返回body(参照wordpress-rest-api)

```
{
    code rest_forbidden,            返回描述与code
    message 抱歉，您不能做那个。,     说明
    data {
        
    }
}
```

业务必填规范

 code  message 
 ---  --- 
 -1 拒绝  String 
 1  通过   
 String  参考wordpress返回描述,前端判断需要=== -11   



