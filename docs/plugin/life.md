# 生命周期

插件的 `main()` 只会在 `Kovi` 启动时运行一次。

向 `监听消息` 传入的闭包，会在每一次接收消息时运行。
