# 官方文档
文档地址：[https://developer.chrome.com/docs/devtools?hl=zh-cn](https://developer.chrome.com/docs/devtools?hl=zh-cn)
# 操作流程
1、手机通过USB连接电脑，手机开通USB调试
2、代码中开启webview支持debug
```
webview.setWebContentsDebuggingEnabled(true)
```
3、运行程序
4、GoogleChrome地址栏输入：
```
chrome://inspect/#devices
```
5、等待页面上出现设备信息及页面信息：（如果ADB连接不了，可以试一下换下数据线）
![](https://beta.appflowy.cloud/api/file_storage/132d4fe4-915c-4ef5-ba7d-d26a09a244c5/v1/blob/9196aea1%2D530a%2D4613%2Db0c4%2Dc95915aa44d1/961510624235236196.png)
6、可以看到，这里显示了设备型号、正在加载的网页链接，点击inspect会打开新窗口，可以在这里去进行调试
![](https://beta.appflowy.cloud/api/file_storage/132d4fe4-915c-4ef5-ba7d-d26a09a244c5/v1/blob/9196aea1%2D530a%2D4613%2Db0c4%2Dc95915aa44d1/5389462213612008509.png)

