单个html要发布，根html要用index.html命名才可以

如果有额外的css文件要在引入到html里的路径里加上仓库名称

比如仓库名称是githubhtml

<link rel="preload stylesheet" href="/githubhtml/vp-icons.css" as="style">

经过多次试验，代码改变后会自动发布新包，但是由于网络和缓存的问题，需要等待和强制刷新才可以看到最新的结果

