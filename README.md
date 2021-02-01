# docker-hexo
[参考地址](https://github.com/zeusro/docker-hexo)

``` bash
git submodule add https://github.com/zeroleo12345/hexo-theme-tree.git  themes/tree
```

同步到docker-hub, 登录 https://hub.docker.com/ 去设置构建源代码
目前配置github代码仓库master分支变更时, 自动触发docker build


## Dev
- nodejs

``` bash
nvs add  10.16.3 
```

- 浏览器访问地址

``` bash
http://localhost:4000
```

