#workers的功能及应用：
<pre>
1，worker是运行在后台的 JavaScript，不会影响页面的性能。就是多线程的意思，js已经不是只能玩玩浏览器的那个js啦！
2，js实现或模拟『多线程』的方法：
[1]定时器
[2]异步操作
[3]workers
3，可以用于实时通信(http://www.ibm.com/developerworks/cn/web/1112_sunch_webworker/)
4，前端一个重要的点--跨域问题：
[1]window添加属性：如window.name='';
[2]localStorage添加item。
[3]iframe+domain和josnp。
[4]postmessage：workers也是利用postmessage来通信的
[5]websocket：
4，它的强大，远不止这些，只有你想不到，没有它做不到！
[参考文献]
workers通信：https://www.html5rocks.com/zh/tutorials/workers/basics/
跨越问题博客：http://blog.csdn.net/joyhen/article/details/21631833
w3cshool:http://www.w3cschool.cn/html5/html5-serversentevents.html
MDN:https://developer.mozilla.org/zh-CN/docs/Web/API/Worker
</pre>
