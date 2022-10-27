当忘记了登录密码，可以执行下面的命令，然后使用 `admin/admin123` 就可以登录了。

```
docker exec -ti arl_mongodb mongo -u admin -p admin
use arl
db.user.drop()
db.user.insert({ username: 'admin',  password: hex_md5('arlsalt!@#'+'admin123') })
```

