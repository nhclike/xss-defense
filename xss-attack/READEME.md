1启动
npm start

2插入攻击测试
浏览器输入
http://localhost:3000/?xss=<p onclick="alert(1)">点我</p>                      //插入诱惑代码

http://localhost:3000/?xss=<iframe src="http://www.baidu.com"></iframe>        //利用iframe插入广告