## IOS

### 使用框架

- WebViewJavascriptBridge

### 返回调用方法eventClose
```
    setupWebViewJavascriptBridge(function(bridge) {
    ...
        bridge.callHandler('eventClose', {}, function (response) {})
    ...
    })
```

### 拉起新web调用方法openWithActionBar
```
    setupWebViewJavascriptBridge(function(bridge) {
    ...
        bridge.callHandler('openWithActionBar', {'url':'https://www.google.com'}, function (response) {})
    ...
    })
```

### 参考h5示例

https://yuanpengzhu.github.io/Muti-Platform-Web/index.html

### 参考资料：
1. [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge)
2. [示例H5](https://github.com/marcuswestin/WebViewJavascriptBridge/blob/master/Example%20Apps/ExampleApp.html)
