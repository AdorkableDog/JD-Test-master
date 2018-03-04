# JD-Test
仿京东app 采用组件化架构 屏幕适配方案可以较好解决多分辨率及同分辨率不同dpi适配；

### 声明 ： 本项目资源采用抓包获取，仅供学习交流使用 。

### Specs

本项目为仿京东项目，项目框架采用路由框架 ARouter 进行模块间通讯，以功能模块进行划分的组件化开发 ，模块内部采用参考google开源的mvp架构 ，
核心框架 包含 retrofit 、rxjava 、dagger2 、fresco 以及个人开源的诸多优秀项目；当然现成的轮子也有不合适的地方，在这些轮子的基础上修改以及自己造轮子组成了
现有的项目，这套架构也是我应用与项目中的架构，后期也会不断扩展维护 ，欢迎大家提issues ，喜欢就直接拿去用 ，绝不收取任何费用（好吧 ， 想收也没人给 ^-^！） 。
后续也会写详细的博客介绍项目内的一些重要部分供大家参考。


***
再来几张非主流分辨率截图

![](https://gitee.com/yulu001/JD-Test-master/raw/master/screenshot/480x854.png) 
![](https://gitee.com/yulu001/JD-Test-master/raw/master/screenshot/screen_home.jpg) 
![](https://gitee.com/yulu001/JD-Test-master/raw/master/screenshot/home1.gif) 




不管是什么样的分辨率都会按 “比例” 显示，重点就是比例 ，根布局自定义后支持宽高比 ，而内部使用google开源的百分比库。百分比库也需要进行自定义支持占屏幕宽度百分比，
textsize也支持以屏幕宽度为基础的百分比定义，此处借鉴张鸿洋大神的自定义百分比库，具体也可参考项目内的自定义layout。



# License

```
Copyright 2017 aritraroy

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```