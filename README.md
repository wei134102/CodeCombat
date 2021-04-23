# CodeCombat
CodeCombat资料dump.tar.gz下载  
链接：https://pan.xunlei.com/s/VMYzHliP-dHLCamAwX_LypPjA1
提取码：yfz8


新开SSH窗口，使用命令

sudo docker exec -it codecombatAliyun /bin/bash

进入容器

$ mongo 
> use coco 
> db.users.update({'name':'wei134102'},{$set:{'earned.gems':1111111, permissions:["godmode","admin"]}},true,false);
> exit

earned.gems 是宝石&#128142;数量，用以兑换装备permissions 是权限:

    godmode 可以打开所有关卡，并永久订阅（不需要再订阅）
    admin 权限成为系统管理员，可以访问 /admin 页面
db.users.update({'name':'填写你的用户名'},{$set:{'earned.gems':9999999, permissions:["godmode","admin"]}},true,false);
