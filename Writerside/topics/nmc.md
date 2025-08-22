# 垣信文档



## 接口设计



### 接口公共要求



1. 时间同步

中国境内全部采用UTC+8，即北京标准时间。

2. 编码方式

所有消息和文件的数据编码，全部采用UTF-8编码方式。

3. 数据时间格式

如无特殊说明，全部采用以下格式：YYYY-MM-DD HH24:MM:SS

4. Restful API接口消息格式

采用JSON格式，包括输入数据和输出数据，全部采用key-value形式，本文档中定义的接口中，所有的参数，无论是输入还是输出，对应的key都是“data”。

如果不是数组，则为：

```json
“data”：{

“para 1”：“para 1 value”，

“para 2”：“para 2 value”，


}
```

如果是数组，则为：

```json
“data”：[

{

“para 1”:“para 1 value”

“para 2”:“para 2 value”

......

}，
```

注：“{}”之间为不同的数据对象实例。

回的HTTP Response消息Header都需要返回客户端请求的eventId，如文件准备好通知。