# 客户端JavaScript的限制

## 浏览器的限制

浏览器限制了JavaScript任务的运行时间。这种限制是有必要的，它确保某些恶意代码不能通过永不停止的密集操作锁住用户的浏览器或计算机。 
此类限制分为两种

1. 调用栈大小限制
2. 长时间运行脚本限制

单个JavaScript操作花费的总时间(最大值)不应该超过100毫秒。这个数字源自Robert Miller于1968年的研究。Nielsen指出如果界面在100毫秒内响应用户输入，用户会认为自己在“直接操纵界面中的对象”。超过100毫秒意味着用户会感到自己与界面失去的联系。

*建议是在50ms内*

## 浏览器不支持的功能

1. JavaScript没有权限写入或删除客户计算机上的任意文件或列出任意目录

    意味着JavaScript程序不能删除数据或植入病毒。

2. 客户端JavaScript没有任何通用的网络能力。

    虽然客户端JavaScript程序可以对HTTP协议编程，此外还有WebSockets，但是这些API都不允许对于范围更广的网络进行直接访问。

## 浏览器限制的功能

1. JavaScript程序可以打开一个新的浏览器窗口，但是为了防止广告商滥用弹出窗口，很多浏览器限制这一功能，使得只有`为了响应鼠标单击这样的用户触发事件的时候`，才能使用。

2. JavaScript程序可以关闭自己打开的浏览器窗口，但是不允许它不经过用户确认就关闭其他的窗口。

3. HTML FileUpload元素的value属性是只读的。

4. 脚本不能读取从不同服务器载入的文档的内容，除非这个就是包含该脚本的文档。

