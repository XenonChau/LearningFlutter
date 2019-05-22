# LearningFlutter

> 给自己看的学习笔记

----------


## 封装 Dio
- [ ] hud(loading, success, failed)
- [ ] 请求头自动添加 user token：
```
dio.interceptors.add(InterceptorsWrapper(onRequest: (options) {}, onResponse: (response) {}, onError: (error) {});
```
- [ ] 拦截返回值，特定代码（例如401：弹登录页），做通用的操作。
- [ ] 拦截后需要取消请求队列里的其他返回。
- [ ] 取消后操作完成，重新开启请求队列里的全部请求。
- [ ] 页面 dispose 后取消当前全部请求。
