# livego
go 实现直播服务
###服务器部署
    chmod 755 server.sh<br/>
    ./server.sh &（依赖go环境，有些情况需要用vim 打开 set ff=unix 然后:wq） <br/>
    或者直接执行 ./LiveGoServer (不依赖go环境)
###本地部署
    直接执行 LiveGoServer.exe
### use
    采用vue+webpack实现ui
    所有在config里
    日志在logs里
    http://localhost:8080/  (视频直播)<br/>
    http://localhost:8080/camera (录视频)(由于chrome的安全限制，建议在firefox下打开录视频页面)
###使用效果
![](https://github.com/qieangel2013/livego/blob/master/public/images/live.png)
###交流使用
    交流群：337937322
