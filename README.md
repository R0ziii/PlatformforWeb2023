
核酸检测登记查询系统

\natweb:前端项目 (Vue+ElementUI+VantUI)

\natserver:后端(SpringBoot+SpringSecurity+Mybatis+MySQL)

\nat.sql:数据库文件(nat_with_v2_system为兼容数据库,admin默认密码123456)

前端配置路径 public/config.js

```javascript
const GlobeConfig={
    appid:"", 
    baseURL:"http://localhost:8888" 
}
```

后端配置 src/main/resources/application.yaml


```yaml
WeChat:
  appid: 
  secret: 
```


