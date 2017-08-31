## 个人信息
- 期望职位：web 前端开发
- 谢杨玲/男/1994  本科/深圳大学 计算机科学与技术
- Email：nicksite68@gmail.com

## 工作经历

### [微影时代（娱票儿）](http://www.yupiao.com) （2016.7 ~ ）          前端工程师

#### 手Q演出 (h5）
- 应用简介：演出在线票务平台，入口：手机QQ -> 钱包 -> 娱乐购物 -> 演出票
- 技术栈：ES6 + ReactJs + Redux
- 负责部分：购票流程（选座、非选座页面）以及详情页
- 要点：
  - 组件封装：将代码数量过长的组件进行拆分，自己实现一个日历组件
  - 代码质量：为了适应 redux， 尝试函数编程范式编写与重构代码
  - 性能优化：为了优化选择页面的加载速度，实现了 Canvas 选座方案（绘制 + 手势识别）
  - 模块封装：抽象 Canvas 渲染方案成开源库 weRender，改写 IScroll 支持手势触发 Canvas 实时绘制 weScroll

#### 演出后台管理系统
- 应用简介：PC 端内部管理系统前端界面
- 技术栈：ES6 + ReactJs + freactal + Ant Design
- 负责部分：报表相关、取票系统订单及取票部分
- 要点：
  - 代码优化：实现复杂表格（多表头）构建方案，抽象成库 weTable，减少了耦合，提高了代码可读性
  - 技术选型：选择了 freactal 做状态管理库，简化了状态管理流程

#### 格瓦拉生活小程序
- 应用简介：微信小程序在线票务平台，入口：微信 -> 小程序 -> 格瓦拉生活
- 负责部分：演出购票流程（分区页、支付页）以及详情页
- 要点：
  - 难点攻破：为了能支持 HTML， 实现HTML 转化 WXML 方案
  - 难点攻破：为了能支持 SVG， 实现 SVG 转化 Canvas 方案
  - 模块封装：抽象 HTML 转化成 JSON 方案 html-parser

#### 马来微信电影票（h5）
- 应用简介：马拉西亚电影在线票务平台，入口：马来微信钱包
- 技术栈：ES6 + ReactJs + Redux
- 负责部分：前端主程
- 要点：
  - 角色定位：前期搭建项目框架，中期负责大部分页面与逻辑，后期独立维护
  - 难点解决：前端调起不了支付，通过查看老项目源码（php）最终发现问题，沟通解决

### [耳语 Whisper](http://www.eryuapp.com) （2015.10 ~ 2016.6）         工程师

#### 全能墙（h5）项目
- 应用简介：社区型应用，入口：QQ空间 –> 同学
- 技术栈：Coffeescript + Mithril.js (mvc)
- 要点：
  - 工作要求：与设计师协作，准确还原设计
  - 代码质量：拆分组件，抽象功能代码

#### 社区后台管理系统项目
- 应用简介： PC 端内部管理系统前端界面
- 技术栈：Coffeescript + ReactJs + flux
- 亮点：
  - 角色定位：独立负责与维护前端项目
  - 难点解决：实现页面无刷新实时审核流

## 技术积累

- 技术博客：[http://blog.nicksite.me](http://blog.nicksite.me)
- Github: [https://github.com/henryluki](https://github.com/henryluki)

### 开源项目和个人作品
- [2D渲染](https://github.com/weiying-shenzhen/weRender) 从 Canvas 绘制座位图的实践中抽象的简单的类库
- [手势识别](https://github.com/weiying-shenzhen/weScroll) 基于 IScroll 实现的支持 Canvas 的手势识别类库
- [HTML解析](https://github.com/henryluki/html-parser) HMTL 解析生成 JSON 的解决方案
- [代码生成工具](https://github.com/henryluki/acgt) 为了提高开发效率，定义 api 描述文件让程序自动生成前后端相关接口代码
- [每日阅读](http://readdaily.cc) 资讯阅读类 web 端应用，这款应用的目的是实现资讯的获取与阅读，资讯内容有简单介绍也有深度阅读

### 技术文章
- [模板预编译技术](http://blog.nicksite.me/index.php/archives/419.html)
- [我在开发"小程序"中做的一些"转换"的工作](http://blog.nicksite.me/index.php/archives/418.html)
- [关于 Redux 中间件](http://blog.nicksite.me/index.php/archives/417.html)
- [关于 FormData](http://blog.nicksite.me/index.php/archives/414.html)

### 其他
- 拥有一项专利发明[一种绘制座位图的方法和装置](http://cpquery.sipo.gov.cn/txnQueryBibliographicData.do?select-key:shenqingh=2017100694603&select-key:gonggaobj=1&select-key:backPage=http%3A%2F%2Fcpquery.sipo.gov.cn%2FtxnQueryOrdinaryPatents.do%3Fselect-key%3Ashenqingh%3D%26select-key%3Azhuanlim) 为第一发明人

## 技能清单
- JavaScript：能熟练使用 ES6 ES5；有 Canvas 动画开发经验
- CSS: 熟悉 Sass、CSS盒子模型、Flex 布局
- 前端框架：能熟练使用 React 全家桶
- 版本管理：熟练使用 Git
- 数据库：熟悉 MySQL
- 后端开发：熟悉使用 Python, Golang, NodeJs