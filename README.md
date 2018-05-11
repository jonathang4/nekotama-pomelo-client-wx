
# NekotamaPomeloClientWX

**NekotamaPomeloClientWX** 是一个webpack模式下使用的pomelo web客户端js类库微信小程序版，该版本之能用于微信小程序/小游戏中。 
>由于[pomelo][1]  官方库中对于web客户端的js使用了component来管理，因此发布该类库方便webpack管理的客户端项目调用。

### 安装
``` javascript
npm i nekotama-pomelo-client-wx
```

### 添加引用
``` javascript
require("nekotama-pomelo-client-wx");
```

>调用请API参考[pomelo客户端开发][3]   注意:由于微信小程序限制，该库中的port字段不可设置，且链接方式修改为wss。

## 问题反馈
- Email: <jonathangdemon@gmail.com>

----------
代码整理自[pomelo][1]  官方代码库中示例[chatofpomelo-websocket][2]。

  [1]: https://github.com/NetEase/pomelo
  [2]: https://github.com/NetEase/chatofpomelo-websocket/tree/master/web-server/public/js/lib
  [3]: https://github.com/NetEase/pomelo/wiki/pomelo%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%BC%80%E5%8F%91