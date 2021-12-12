# wechat-miniprogram-optimize-strategy

微信小程序性能/体验优化策略。

- 分包异步化
- 独立分包
- 懒加载
- 骨架屏


## 工具

- [真机性能分析工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/performancetool.html)


[kbone](https://developers.weixin.qq.com/miniprogram/dev/platform-capabilities/extended/kbone/)


[按需注入](https://developers.weixin.qq.com/miniprogram/dev/framework/ability/lazyload.html#%E6%8C%89%E9%9C%80%E6%B3%A8%E5%85%A5)


目录结构：

```bash
src
  resouces
    utils
    services
    assets
      icons
      styles
    components
    constants
  home
    index.tsx
    index.less
  user
    index.tsx
    index.less
```

101.33.213.134