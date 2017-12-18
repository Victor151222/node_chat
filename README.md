- 网络聊天中协议的重要性

- `socket.remoteAddress`

如果 `socket` 被销毁了（如客户端已经失去连接）则其值为 `undefined`。所以在`socket.on('error', (err) => { }`中不能使用它。