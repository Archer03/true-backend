# true-backend
## Start up a server by just a/an *.har file exported by chrome in f12 tool ✔
- When API is unstable, it's difficult to open frontend page to do my frontend work
- Or some crazy bugs occur on production version, we cannot debug to find problem because js code has been compiled ugly


- 某个页面需求ui联动逻辑多开发时间长，后端api总是挂，使用true-backend 自建服务
- SIT/UAT环境 线上代码没有source map却想要debug, 使用true-backend 在本地重现问题

通常情况下，前端开发需求或者定位问题，其实此时并不依赖整个后端服务，而只需要当前页面的某个或某些操作后的数据
理论上可以减少前端开发受外部条件的影响

#### And this is time for true-backend to show 🐱‍👤
