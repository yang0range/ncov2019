# 2019新型冠状病毒疫情发展分析

我在此项目中使用了来自新浪的数据接口，并对数据使用做了如下约定

1. 只使用2019年1月21日及以后的数据，之前的数据由于没有进入紧急情况，所以统计有可能不能反映真实情况。
2. 只考虑增量，累积量用来反应形式发展并不直观。

## 项目部署

clone 此项目代码后在浏览器里打开 `dist` 目录下的 `index.html` 文件即可看到数据。数据是实时从远程接口获取。

如果需要修改代码，或者自己编译，需要安装 `parcel`

```
npm install -g parcel-bundler
```

安装完以后执行

```
npm run build
```

即可完成编译，如果缺失npm包，别忘了执行

```
npm install
```