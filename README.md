使用说明

>安装过程中会提示输入管理员用户名、密码、邮箱，输入后耐心等待即可访问 http://IP 

>后台地址 http://IP/admin 

修改simdht_worker.py里的max_node_qsize的大小调节爬取速度（队列大小）

执行  python manage.py create_user  创建管理员

执行  python manage.py changepassword  修改管理员密码

执行  python manage.py init_db  创建表

 

**更多疑问？请[加群](http://shang.qq.com/wpa/qunwpa?idkey=d119da6023cc49729a61139ca4b8bb0ee770d8d9a89383939c4a45159f82bc6d)**

**Q：我以前使用的搜片大师/手撕包菜，可以迁移过来吗？**

A：程序在开发之初就已经考虑到从这些程序迁移过来的问题，所以你不用担心，完全可以无缝迁移。如果有需求，请联系作者QQ 153329152 付费为你提供服务

**Q：网站经常收到版权投诉，有没有好的解决办法？**

A：除了删除投诉的影片数据外，你可以使用前端Nginx、后端gunicorn+爬虫+数据库+索引在不同主机上的模式，甚至多前端模式，这样 即使前端被主机商强行封机，也能保证后端数据的安全。如果有需求，请联系作者QQ 153329152 付费为你提供服务

**郑重申明:**

若你从其他地方获取到源码，再联系我咨询程序的使用，将按500元/次收费！


