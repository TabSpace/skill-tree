# skill-tree

个人资源积累，✭ 号表示强烈推荐

------

## 基础知识

### 标准与规范

* [w3c](https://www.w3.org/)
	* [w3c中国](http://www.chinaw3c.org/)
	* [规范列表](https://www.w3.org/TR/#w3c_all)
	* [css规范当前状态](https://www.w3.org/Style/CSS/current-work)
	* [如何阅读w3c规范](http://alistapart.com/article/readspec)
* [浏览器favicon cheat-sheet](https://github.com/audreyr/favicon-cheat-sheet)
* [meta元素整理](https://segmentfault.com/a/1190000002407912)
* [gradients 渐变](https://drafts.csswg.org/css-images-3/)

### 语言

* [javascript标准参考 阮一峰版](http://javascript.ruanyifeng.com/)
* [js 与 dom 参考(w3schools)](http://www.w3schools.com/jsref/)
* [TypeScript](https://www.typescriptlang.org/)
	* [TypeScript 中文网](https://www.tslang.cn/)
	* [TypeScript 入门教程](https://ts.xcatliu.com/)
* es6
	* [ECMAScript6入门](http://es6.ruanyifeng.com/)
	* [es5浏览器适配表](http://kangax.github.io/compat-table/es5/)
	* [es6浏览器适配表](http://kangax.github.io/compat-table/es6/)
	* [webpack es6 浏览器兼容](https://segmentfault.com/a/1190000005128101)
	* [babel](https://babeljs.io/) 提前使用es6,es7
* polyfill
	* [Promise](https://github.com/taylorhakes/promise-polyfill)
	* [es5-shim](https://github.com/es-shims/es5-shim)
	* [fetch](https://github.com/github/fetch)
	* [handjs](https://github.com/deltakosh/handjs) pointer events polyfill
* lua
	* [lua 入门](https://moonbingbing.gitbooks.io/openresty-best-practices/lua/main.html)
* shell
	* [30分钟shell入门](https://github.com/qinjx/30min_guides/blob/master/shell.md)
	* ✭ [命令行的艺术](https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md)

### HTML5

* [html5](http://html5index.org/)
	* [orientation 重力感应](http://w3c.github.io/deviceorientation/spec-source-orientation.html)
	* [html5rocks](https://www.html5rocks.com/en/) 各种demo
	* video
		* [video events and api](https://www.w3.org/2010/05/video/mediaevents.html)
	* canvas
		* [mdn canvas](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API)
		* [w3school canvas](http://www.w3schools.com/tags/ref_canvas.asp)
		* [webgl](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
		* [opengl](https://www.opengl.org/)
		* [khronos webgl wiki](https://www.khronos.org/webgl/wiki/Main_Page)
		* [让canvas像flash一样工作](https://my.oschina.net/cmw/blog/14963)
		* [canvas截图](https://tech.colla.me/zh/show/screenshot_feedback_implementation)
		* [rasterizeHTML](https://github.com/cburgmer/rasterizeHTML.js)
		* [dom-to-image](https://github.com/tsayen/dom-to-image) 用svg截图
	* svg
		* [使用脚本动态操作 SVG 文档](https://www.ibm.com/developerworks/cn/xml/x-svgscript/)
		* [mdn svg教程](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Tutorial)
		* [svg 中文教程](https://www.gitbook.com/book/brucewar/svg-tutorial/details)
		* [svg线条动画 vivus](https://github.com/maxwellito/vivus)
	* [navigator-share web share](https://developers.google.com/web/updates/2016/10/navigator-share)
* 开发调试 - 调试相关的工具与文章

* 兼容性
	* [w3c兼容性知识库](http://w3help.org/zh-cn/kb/)
	* ✭ [can i use](http://caniuse.com/)
	* [UC浏览器开发者中心](http://www.uc.cn/business/developer/)

### 打包

* ✭ [webpack](https://webpack.github.io/)
	* plugins
		* [html-webpack-plugin](https://www.npmjs.com/package/html-webpack-plugin)
		* [progress-bar-webpack-plugin](https://www.npmjs.com/package/progress-bar-webpack-plugin)
		* [extract-text-webpack-plugin](https://www.npmjs.com/package/extract-text-webpack-plugin)
	* 文章
		* [webpack使用优化](http://www.alloyteam.com/2016/01/webpack-use-optimization/)
		* [webpack指南](https://www.gitbook.com/book/toobug/webpack-guide/details)
		* [webpack cookbook](https://fakefish.github.io/react-webpack-cookbook/)
* [rollup](http://rollupjs.org/) 适合纯粹js打包
* [parcel](https://github.com/parcel-bundler/parcel) 配置简单易上手
* [fis](http://fis.baidu.com/)
	* [fis3-base 现成的脚手架](https://github.com/yanhaijing/fis3-base)

### 工程管理

* 项目模板
	* [yeoman](http://yeoman.io/)
* 任务管理
	* ✭ [gulp](http://gulpjs.com/)
	* [grunt](http://gruntjs.com/)
* 规范化
	* [semver](https://semver.org/lang/zh-CN/) 语义化版本说明
		* [commitizen](https://github.com/commitizen/cz-cli) 代码提交规范化
		* [semantic-release](https://github.com/semantic-release/semantic-release) 全自动化版本管理
	* [lerna](https://github.com/lerna/lerna/) 实现框架分包管理
	* [angular-CONTRIBUTING](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit) angular 提交规范，用于实现参考规范
	* [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) changelog 自动生成
	* [husky](https://github.com/typicode/husky) 便捷管理 Git hooks
	* [lint-staged](https://github.com/okonet/lint-staged) 提交前 lint
	* [gitflow](https://github.com/nvie/gitflow) git 工作流规范化

### 开发调试

* [devtools](https://developer.chrome.com/devtools)
* [BrowserSync](https://browsersync.io/) 浏览器代码实时同步
	* [中文官网](http://www.browsersync.cn/)
* ✭ [vConsole](https://github.com/WechatFE/vConsole) 提供一个Js编写的控制台，解决手机浏览器调试麻烦的问题
* [saucelabs 开放测试平台](https://saucelabs.com/) 可在github readme生成兼容列表
* 移动端调试
	* [weinre](https://github.com/nupthale/weinre) 移动应用调试工具
	* [adb](https://developer.android.com/studio/command-line/adb?hl=zh-cn#Enabling) Android 调试桥
* 代理
	* ✭ [http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) node代理中间件
	* ✭ [whistle](https://github.com/avwo/whistle) 基于node的调试代理工具
	* ✭ [VRouter](https://github.com/icymind/VRouter) 跨平台搭建透明代理
	* [anyproxy](https://github.com/alibaba/anyproxy) 基于 node 的代理工具，阿里出品
	* [nproxy](https://github.com/goddyZhao/nproxy) 基于 node 的静态文件代理
* 持续集成
	* [travis](https://travis-ci.org/) 适用于Github托管项目
		* [如何简单入门持续集成](https://github.com/nukc/how-to-use-travis-ci)
	* [jenkins](https://jenkins.io/)
	* [appveyor](https://www.appveyor.com/) 应用持续构建，适用于Github托管项目
	* [circleci](https://circleci.com/) 适用于Github托管项目
* 数据模拟
	* 图片占位
		* [placehold](http://placehold.it/)
		* [fakeimg](http://fakeimg.pl/)
	* 数据模拟工具
		* [json generator](http://beta.json-generator.com/)
		* ✭ [mock.js](https://github.com/nuysoft/Mock) 一个数据模拟工具
		* [Faker.js](https://github.com/marak/Faker.js/) 一个数据模拟工具
	* mock server
		* [rap](https://github.com/thx/RAP) 阿里 java mock server
		* [json server](https://github.com/typicode/json-server)
		* [swagger](https://swagger.io/)
		* [yapi](https://github.com/YMFE/yapi) 一个可本地部署的、打通前后端及QA的、可视化的接口管理平台
		* [spore-mock](https://github.com/SporeUI/spore-mock) 本地化mock服务
* 测试
	* [mocha](https://github.com/mochajs/mocha) 前端测试框架，既可以用于浏览器端，也可以用于服务器端
		* [chai](https://github.com/chaijs/chai) 测试断言库
		* [should.js](https://github.com/shouldjs/should.js) 测试断言库
	* [karma](https://github.com/karma-runner/karma) 测试自动化
	* [nightwatchjs](https://github.com/nightwatchjs/nightwatch) UI测试自动化
	* [macaca](https://github.com/alibaba/macaca) 多端自动化测试解决方案
* 无界面浏览器 (Headless Browser)
	* ✭ [puppeteer](https://github.com/GoogleChrome/puppeteer) 无界面 blink 内核浏览器，google 出品
	* [phantomjs](https://github.com/ariya/phantomjs) 无界面 webkit 内核浏览器，作者已宣布停止维护
* 日志管理与质量监控
	* [sentry](https://github.com/getsentry/sentry)
	* [BetterJS](https://github.com/BetterJS) 原名 BadJS
* chrome插件
	* [Edit-This-Cookie](https://github.com/fcapano/Edit-This-Cookie) cookie 编辑
	* [FeHelper](https://github.com/zxlie/FeHelper) 前端调试助手

### NPM

* [npm](https://npmjs.org/)
	* [npm的package.json中文文档](https://github.com/ericdum/mujiang.info/issues/6)
	* [淘宝npm镜像](http://npm.taobao.org/)
	* [yarn](https://github.com/yarnpkg) facebook 推出的 npm 替代方案，安装模块更迅速
	* [npm-runkit](https://npm.runkit.com/) 一个简单的npm模块实验室
	* [npms.io](https://npms.io/) npm模块搜索

### 开发规范

* [isobar 前端代码规范](http://coderlmn.github.io/code-standards/)
* 代码规范
	* [airbnb](https://github.com/airbnb/javascript)
	* [standard](https://github.com/standard/standard)
	* [prettier](https://github.com/prettier/prettier) 代码格式化
	* [idomatic](https://github.com/rwaldron/idiomatic.js)
	* [google styleguide](https://github.com/google/styleguide)
* css规范
	* [BEM 规范](http://getbem.com/)
	* [bootcss 编码规范（html, css）](http://codeguide.bootcss.com/)
	* [smacss](https://smacss.com/)
* 代码增强
	* [flow](https://github.com/facebook/flow)
		* [flow 介绍](http://www.alloyteam.com/2015/07/flow-a-static-type-checker-for-javascript-from-facebook/)
* lint
	* ✭ [eslint](https://github.com/eslint/eslint)

### 图标与字体

* ✭ [iconfont](http://iconfont.cn/) 阿里巴巴矢量图标库
* [icoMoon](https://icomoon.io/)
* [font-spider](https://github.com/aui/font-spider) 字蛛：智能 WebFont 压缩工具
* [font-awesome](http://fontawesome.io/) 开源图标字体库
* [fontmin](https://github.com/ecomfe/fontmin)
* [one div](http://one-div.com/)
* [a single div](http://a.singlediv.com/)
* [nicon](https://github.com/bolin-L/nicon) 图标管理服务器，支持私有部署

### 预处理

* ✭ [less](http://www.lesscss.net/)
	* [lesstester](http://lesstester.com/) less 代码测试
* [sass](http://sass-lang.com/)
	* [sass-reference](http://sass.bootcss.com/docs/sass-reference/) sass中文参考手册
	* [sass用法指南](http://www.ruanyifeng.com/blog/2012/06/sass.html) 阮一峰版
	* [sass-compatibility](https://sass-compatibility.github.io/) sass兼容性问题
	* [sass-guidelin](https://sass-guidelin.es/) sass书写风格指导
* js
	* [prepack](https://github.com/facebook/prepack) 代码优化，结合webpack与gulp使用

### 版本控制

* git
	* [TortoiseGit](https://tortoisegit.org/) windows git可视化工具
	* [git中文参考手册](http://gitref.org/zh/)
	* [git bash](https://git-scm.com/)
	* [git magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/)
	* [坑：换行符自动转换](https://github.com/cssmagic/blog/issues/22)
	* [git pro 中文](https://sandwind.gitbooks.io/git-pro-cn/content/index.html)
* svn
	* [tortoise svn](https://tortoisesvn.net/index.zh.html)
		* [TortoiseSVN中文帮助手册](http://svndoc.iusesvn.com/tsvn/1.4/index.html)
	* [Linux下安装svn client](http://blog.csdn.net/kenera/article/details/5746585)

### 服务器环境

* [apache](https://httpd.apache.org/)
	* [apache 配置详解](http://liudaoru.iteye.com/blog/336338)
* [nginx](https://nginx.org/en/)

### 命令行

* [cygwin](http://www.cygwin.cn/) windows上使用命令行
* [Oh My ZSH](http://ohmyz.sh/) 操作增强
* [tmux](https://github.com/tmux/tmux) 终端窗口复用

### 安全

* [html xss cheatsheet](https://github.com/cure53/H5SC)
* [xss](http://baike.baidu.com/item/XSS%E6%94%BB%E5%87%BB)
* [csrf](http://baike.baidu.com/item/csrf)
* [ddos](http://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%94%BB%E5%87%BB/3802159?fromtitle=DDOS&fromid=444572)
* 简单攻击方式--刷票
	* [voteRobot](https://github.com/debugtalk/VoteRobot)

### 算法

* 集合
	* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) javascript 算法集合
* 寻路算法
	* [path-finding](https://github.com/qiao/PathFinding.js)
* 人工智能
	* [深度学习阅读路线图](https://github.com/songrotek/Deep-Learning-Papers-Reading-Roadmap)
	* [cheatsheets-ai](https://github.com/kailashahirwar/cheatsheets-ai)
	* [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
	* [deeplearnjs](https://github.com/PAIR-code/deeplearnjs)
	* [neurojs](https://github.com/janhuenermann/neurojs)
	* [tensorflow](https://github.com/tensorflow)
		* [tensorflow-zh](https://github.com/jikexueyuanwiki/tensorflow-zh)
	* [convnetjs](https://github.com/karpathy/convnetjs) 深度学习js版本

### github

* 工具
	* [github trending](https://github.com/trending?l=javascript) javascript 热门趋势
	* [github showcases](https://github.com/showcases/) 开源范例
	* [github explorer](https://github.com/explore) 资源浏览器
	* [静态站点搭建](https://pages.github.com/)
* 文章
	* [GotGithub](http://www.worldhello.net/gotgithub/) 熟练掌握 github
	* [技巧：github上传图片和在线示例](http://solutionoptimist.com/2013/12/28/awesome-github-tricks/)
	* [如何为开源做贡献](https://guides.github.com/activities/contributing-to-open-source/index.html)
	* [如何在github上fork一个项目来贡献代码以及同步原作者的修改](http://www.cnblogs.com/rubylouvre/archive/2013/01/24/2874694.html)
	* [少有人知的github使用技巧](https://segmentfault.com/a/1190000000475547)
	* [GitHub 漫游指南](https://github.com/phodal/github-roam)
	* [果壳中的git](https://github.com/geeeeeeeeek/git-recipes/wiki)
	* [为开源项目弄个漂亮的文档](https://laravel-china.org/topics/1965/how-to-get-a-good-document-for-your-open-source-projects)
* 第三方工具
	* [Astral](https://app.astralapp.com/dashboard) 资源管理工具
	* [waffle](https://waffle.io/) 把issue变成任务管理器

### 培训资料

* 资源
	* [JS入门](http://shichuan.github.io/javascript-patterns/)
	* [w3schools](http://www.w3schools.com/)
		* [中文站](http://www.w3school.com.cn/)
	* [Mozilla MDN](https://developer.mozilla.org/zh-CN/)
	* [css tricks](https://css-tricks.com/css/) css技巧获取
	* [面试题](https://github.com/jackqqxu/FE-interview)
	* [慕课网](http://www.imooc.com/)
	* [laravel 视频教程](https://www.laravist.com/)
* 知识点
	* [科学上网](https://github.com/bannedbook/fanqiang) 通用翻墙资料
	* [ajax](https://segmentfault.com/a/1190000004322487)
	* [cors](http://www.ruanyifeng.com/blog/2016/04/cors.html)
		* [cors跨域发送cookie](http://harttle.com/2016/12/28/cors-with-cookie.html)
	* [pwa](https://huangxuan.me/2017/02/09/nextgen-web-pwa/)
	* [referrer-policy](https://imququ.com/post/referrer-policy.html)
	* [flex布局教程](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
		* [flex bug 列表](https://github.com/philipwalton/flexbugs)
	* transform
		* [Understanding the CSS Transforms Matrix](https://dev.opera.com/articles/understanding-the-css-transforms-matrix/)
		* [理解矩阵](http://blog.csdn.net/pizi0475/article/details/5440136)
	* [js版本号的故事](https://huangxuan.me/2015/09/22/js-version/)
	* [wtf js](https://github.com/denysdovhan/wtfjs)
	* [开源许可协议 license](http://www.ruanyifeng.com/blog/2011/05/how_to_choose_free_software_licenses.html)
	* webgl
		* [3D图形:矩阵与线性变换](https://www.jianshu.com/p/6c2c0542071d)
		* [图形学 光栅化详解](https://www.jianshu.com/p/54fe91a946e2)
	* [stream-handbook node stream 概念说明](https://github.com/jabez128/stream-handbook)
	* [webassembly](http://webassembly.org/)
* 工具
	* [ntn选择器精通-练习工具与实验场](http://nthmaster.com/)
* 文章
	* [浏览器交互流程](https://github.com/skyline75489/what-happens-when-zh_CN) --当你按下回车键时发生了什么
	* [浏览器性能优化指导](https://developers.google.com/speed/docs/insights/rules?csw=1)
		* [14 rules](http://stevesouders.com/hpws/rules.php)
		* [浏览器渲染原理](http://coolshell.cn/articles/9666.html)
			* ✭ [how browser work](http://taligarsiel.com/Projects/howbrowserswork1.htm)
		* [实现达到 60FPS 的高性能交互动画](https://zhuanlan.zhihu.com/p/29729996?refer=FrontendMagazine)
		* [狙杀页面卡顿 —— Performance 工具指北](https://zhuanlan.zhihu.com/p/41017888)
	* css
		* [css3不为人知的高级属性](http://www.cnblogs.com/radom/archive/2012/04/19/2457356.html)
		* [一些试验性css属性](http://www.cnblogs.com/html5salon/archive/2012/06/13/2547798.html)
	* [正则表达式回溯法原理](https://mp.weixin.qq.com/s/sT8kQkfLDvB1ahoJ6Ss0Uw)
	* [前端研发生态环境构建经验谈](http://www.csdn.net/article/2014-03-19/2818831)
	* [移动端前端开发调试](http://yujiangshui.com/multidevice-frontend-debug/)
	* [用JSON构建API的标准指南](http://jsonapi.org.cn/)
* 方法论建设
	* [spellbook-of-modern-webdev](https://github.com/dexteryy/spellbook-of-modern-webdev)
	* [《屋中的大象》-- Apache基金会副总裁几十年的观察](https://www.oschina.net/news/79166/apache-foundation-ceo-decades-views)
	* [编程哲学（一）：愚者无疑，智者多虑](https://zhuanlan.zhihu.com/p/37653499) 后续有 1-10 多篇文章，都在一个专栏下

### 其他文章

* [android webapp](https://developer.android.com/guide/webapps/index.html)
* [渐进式jpeg](http://blog.jobbole.com/44038/)
* [知乎的模糊预览](https://www.zhihu.com/question/55622930)

------

## 技术栈

### 资料集合

* [awesome-javascript](https://github.com/sorrycc/awesome-javascript) 资源集合
* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
* [SporeUI](https://github.com/SporeUI) 个人工具库

### 实用工具

* 基本工具集合
	* [underscore](https://github.com/jashkenas/underscore) 老牌工具库
	* [lodash](https://lodash.com/) 更为现代的工具函数库
	* [lazy](https://github.com/dtao/lazy.js) 延迟计算的工具函数
	* [collect](https://github.com/ecrmnn/collect.js) 处理 JavaScript 中的数组和对象
* [js-cookie](https://github.com/js-cookie/js-cookie)
* [step](https://github.com/creationix/step) 流程控制
* [axios](https://github.com/mzabriskie/axios) 代替 $.ajax，可运行于node，适用于同构
* [PreloadJS](https://github.com/CreateJS/PreloadJS) 解决资源预加载
* [chancejs](https://github.com/chancejs/chancejs) 生成随机数据
* [math.js](https://github.com/josdejong/mathjs) 简化数学计算
* [city](https://github.com/basecss/city) 国家行政区划分数据
* [moment](http://momentjs.cn/) 时间日期处理
* [dayjs](https://github.com/iamkun/dayjs) 日期处理
* [kibo](https://github.com/marquete/kibo) 键盘事件绑定
* [ua-device](https://github.com/fex-team/ua-device) UA解析
* [lazyload](https://github.com/verlok/lazyload) 图片延迟加载
* [minimatch](https://github.com/isaacs/minimatch) 文件路径匹配
* [voca](https://github.com/panzerdp/voca) 字符串处理
* [sortable](https://github.com/RubaXa/Sortable) 拖拽排序
* [gl-matrix](https://github.com/toji/gl-matrix) 矩阵计算，3d场景常用

### 模板引擎

* [pug](https://pugjs.org/)
	* [pug-loader](https://github.com/pugjs/pug-loader)
	* [jade2php](https://github.com/SE7ENSKY/jade2php)
	* [learn jade](http://learnjade.com/) 代码测试
	* [jade 中文说明](http://expressjs.jser.us/jade.html)

### 数据可视化

* [数据可视化](https://github.com/showcases/data-visualization) 各种图表工具
* [d3](https://github.com/d3/d3) 用于制作复杂图表
* [chart.js](https://github.com/chartjs/Chart.js) 体积小，适合 h5
* [highcharts](https://github.com/highcharts/highcharts) 开源图表框架，兼容性好
* [echarts](https://github.com/ecomfe/echarts) 百度推出的图表工具，功能强大，提供了webgl版本
* [g2](https://github.com/antvis/g2) 蚂蚁金服推出的图表工具
* [vis](https://github.com/almende/vis)

### 路由

* [page](https://github.com/visionmedia/page.js)
* [history](https://github.com/browserstate/history.js)

### 文件上传

* [fineuploader](https://github.com/FineUploader/fine-uploader)
* [plupload](https://github.com/moxiecode/plupload)

### UI

* dialog
	* 适用pc
		* [artDialog](https://github.com/aui/artDialog) 简洁的对话框，QQ空间在用
		* [sweetalert](https://github.com/t4t5/sweetalert) 动画效果惊艳，但展示面积较大，不太适合移动端
	* 均可
		* [vex](https://github.com/HubSpot/vex) 3d队列值得参考
		* [layer](https://github.com/sentsin/layer) 具有高兼容性的对话框
* 集合
	* [framework7](http://framework7.io/) 适合传统h5站点开发
		* [framework7-taobao](http://framework7.taobao.org/)
		* [msui-taobao](http://m.sui.taobao.org/components/)
	* [spectre](https://github.com/picturepan2/spectre) 轻量级响应式css框架
	* [foundation](https://github.com/zurb/foundation-sites) 很多响应式框架依赖的响应式样式框架
	* [amaze ui](https://github.com/amazeui/amazeui) 重视动画交互
	* [flat ui](https://github.com/designmodo/Flat-UI) 扁平化
	* [Semantic-UI](https://github.com/Semantic-Org/Semantic-UI) 响应式样式框架
	* [bootstrap](https://github.com/twbs/bootstrap) twitter 出品的响应式框架
		* [bootstrap中文网](http://v3.bootcss.com/)
	* [layer UI](https://github.com/sentsin/layui/) 原生代码框架
	* [weui](https://github.com/weui/weui) 微信风格样式框架，适合移动端开发
	* [spectre](https://github.com/picturepan2/spectre) 一个响应式css框架
	* [飞冰](https://github.com/alibaba/ice/) 阿里的飞冰，用于中后台项目搭建

### 多媒体展示

* [Javascript-Load-Image](https://github.com/blueimp/JavaScript-Load-Image) 加载图片并缩放
* [fullPage](https://github.com/alvarotrigo/fullPage.js) 创建全屏滚动页面的框架
* 图片裁剪
	* [jcrop](https://github.com/tapmodo/Jcrop/)
	* [cropperjs](https://github.com/fengyuanchen/cropperjs)
* 幻灯
	* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) 经典桌面swiper
	* [swiper](https://github.com/nolimits4web/Swiper) 幻灯，h5slides
	* [impress](https://github.com/impress/impress.js) 创建炫目的幻灯展示
	* [webslides](https://github.com/webslides/webslides) 快速创建幻灯
* [video.js](https://github.com/videojs/video.js) 视频
* [SoundJS](https://github.com/CreateJS/SoundJS) 基于Audio Api 音频处理
* [EaselJS](https://github.com/CreateJS/EaselJS) 对 canvas api 的封装

### 动画

* [AlloyTouch](https://github.com/AlloyTeam/AlloyTouch) 平滑滚动
* [walkway](https://github.com/ConnorAtherton/walkway) svn路径动画
* [TweenJS](https://github.com/CreateJS/TweenJS) 动画过渡管理
* [tween.js](https://github.com/tweenjs/tween.js) 动画过渡管理
* [velocity](https://github.com/julianshapiro/velocity) 动画过渡管理
* [bezier-easing](https://github.com/gre/bezier-easing) 贝塞尔函数生成器
	* [simple easing](https://gist.github.com/gre/1650294) 简单过渡动画函数
* js动画引擎
	* [白鹭引擎](http://developer.egret.com/cn/) 国产，2d,3d都支持，支持小游戏
	* [cocos2d](https://github.com/cocos2d/) 主要用于物理引擎
	* [layabox](https://www.layabox.com/) 国产，2d,3d都支持，支持小游戏
* 3d引擎
	* [webgl框架列表](https://en.wikipedia.org/wiki/List_of_WebGL_frameworks)
	* [sketchfab](https://sketchfab.com/)
	* [BabylonJS](https://github.com/BabylonJS/Babylon.js) 可引入高复杂度场景
		* [doc](http://doc.babylonjs.com/)
		* [editor](http://editor.babylonjs.com/)
			* [intro](https://medium.com/babylon-js/welcome-to-the-babylon-js-editor-c08dccdcec07)
	* [three.js](https://github.com/mrdoob/three.js) 精简基础3d框架
		* [ar.js](https://github.com/jeromeetienne/AR.js)
		* [three.ar.js](https://github.com/google-ar/three.ar.js)
	* [playcanvas](https://playcanvas.com/) 里面的浮空小岛是经典案例

### 终端/命令行

* [top-command-line-tools](https://stackify.com/top-command-line-tools/) 最受欢迎的命令行工具
* [chalk](https://github.com/chalk/chalk) 用于在终端渲染文本颜色
* [prompt](https://github.com/flatiron/prompt) 用于在终端构建交互式输入
* [commander](https://github.com/tj/commander.js) 命令行界面开发库
* [clui](https://github.com/nathanpeck/clui) spinners、sparklines、progress bars图样显示组件
* [shelljs](https://github.com/shelljs/shelljs) node.js运行shell命令组件
* [blessed-contrib](https://github.com/yaronn/blessed-contrib) 命令行可视化组件
* [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) 命令行交互信息收集组件

### 编辑器

* [CodeMirror](https://github.com/codemirror/CodeMirror/) 代码编辑器
* [mathjax](https://github.com/mathjax/mathjax) 公式编辑器

### Node

* 运维
	* [pm2 多进程管理](https://github.com/Unitech/PM2/) 进程失败后重新拉起进程
	* [pandora](https://github.com/midwayjs/pandora) 专业的 Node.js 应用监控管理器，阿里开源
* 工具
	* [node-inspector](https://github.com/node-inspector/node-inspector) node调试工具
	* [execa](https://github.com/sindresorhus/execa) better child_process
	* [node-svn-ultimate](https://github.com/peteward44/node-svn-ultimate) svn 操作 node api 版
	* hotload
		* [nodemon](https://github.com/remy/nodemon) 监听文件重启服务
		* [node-supervisor](https://github.com/petruisfan/node-supervisor) 代码保存触发hotload
	* [ora](https://github.com/sindresorhus/ora) 命令行loading
	* [vorpal](https://github.com/dthree/vorpal) 创建交互式CLI的框架
	* [vantage](https://github.com/dthree/vantage) 将一个应用转化为命令行交互工具
* 即时通讯
	* [socket.io](https://github.com/socketio/socket.io) 传统 websocket 库
	* [websockets/ws](https://github.com/websockets/ws) 性能更好的 websocket 库
* 框架
	* [thinkjs](https://github.com/thinkjs/thinkjs)
	* [koa](https://github.com/koajs/koa) 现代 node 框架
	* [express](http://expressjs.com/zh-cn/)
		* [express中文文档](http://expressjs.jser.us/)
		* [helmet](https://github.com/helmetjs/helmet) 安全中间件
		* [cors](https://github.com/expressjs/cors) 中间件
	* [egg](https://github.com/eggjs/egg) 基于koa2的上层封装，企业级nodejs框架
* 自动化
	* [robotjs](https://github.com/octalmage/robotjs) node桌面自动化实现
	* [chrome-protocol-proxy](https://github.com/wendigo/chrome-protocol-proxy) chrome控制台调试接口代理
* 桌面应用开发
	* [electron](https://github.com/electron/electron) 构建桌面app
		* [electron-vue](https://github.com/SimulatedGREG/electron-vue) 基于vue框架的electron应用
	* [node-webkit](https://github.com/nwjs/nw.js/)
		* [nw-cn](http://nwjs-cn.readthedocs.io/zh_CN/latest/index.html) nw 中文文档
		* [nw 中文教程](https://wizardforcel.gitbooks.io/nwjs-doc/content/wiki/index.html)
* Node实用库积累
	* [opencv4nodejs](https://github.com/justadudewhohacks/opencv4nodejs) opencv node 版，人脸识别，智能识别
	* [url-join](https://github.com/jfromaniello/url-join) url 字符串连接
	* [iconv](https://github.com/bnoordhuis/node-iconv) 页面编码转换
	* [fs-extra](https://github.com/jprichardson/node-fs-extra) 文件操作增强
	* [svn-ultimate](https://github.com/peteward44/node-svn-ultimate) svn操作的node封装
	* [url-parse](https://github.com/unshiftio/url-parse) url解析
	* [winston](https://github.com/winstonjs/winston) 日志管理
	* [file-stream-rotator](https://github.com/rogerc/file-stream-rotator/) 文件循环，可以用来做日志循环
	* [sofa-rpc-node](https://github.com/alipay/sofa-rpc-node) 一个通用的 Nodejs RPC 解决方案
	* [sofa-bolt-node](https://github.com/alipay/sofa-bolt-node) SOFABolt 的 Nodejs 实现，它包含了 Bolt 通讯层协议框架，以及 RPC 应用层协议定制

### jQuery

* [jquery](http://jquery.com/)
	* [jquery-ui](https://jqueryui.com/)
	* [jquery file upload](https://github.com/blueimp/jQuery-File-Upload)
	* [viewerjs](https://github.com/fengyuanchen/viewerjs) 图片展示jquery插件
	* [cropper](https://github.com/fengyuanchen/cropper) 图片裁剪jquery插件
	* [bxslider](https://github.com/stevenwanderski/bxslider-4) 基于jquery的响应式幻灯组件

### React

* [react](https://facebook.github.io/react/)
* 教程与学习
	* [react技术栈教程](http://www.ruanyifeng.com/blog/2016/09/react-technology-stack.html) 阮一峰版
	* [react-china](http://react-china.org/)
* UI
	* [ant-design](https://github.com/ant-design/ant-design)
	* [element react](https://github.com/eleme/element-react)
	* [ring-ui](https://github.com/JetBrains/ring-ui) 使用 Typescript 进行开发
	* [blueprint](https://github.com/palantir/blueprint) 使用 Typescript 进行开发
* 替代品
	* [anu](https://github.com/RubyLouvre/anu)
	* [preact](https://github.com/developit/preact/) 轻量级react
* ssr
	* [reactphp](https://github.com/reactphp/react)
* 架构
	* [draft-js](https://github.com/facebook/draft-js) 基于react的编辑器
	* [redux](https://github.com/reactjs/redux) 通用react数据仓库
		* [redux-devtools](https://github.com/gaearon/redux-devtools)
	* [mobx](https://github.com/mobxjs/mobx) 另一个数据仓库
		* [中文文档](https://cn.mobx.js.org/)
	* [immer](https://github.com/mweststrate/immer) immutable state 管理器
* 工程
	* [jest](https://github.com/facebook/jest) 测试工具
	* [create-react-pwa](https://github.com/jeffposnick/create-react-pwa)
	* [create-react-app](https://github.com/facebookincubator/create-react-app)
	* [enzyme](https://github.com/airbnb/enzyme) JavaScript Testing utility for React

### VUE

* [vue](http://vuejs.org/)
* [awesome-vue](https://github.com/vuejs/awesome-vue)
* UI
	* [element ui](https://github.com/ElemeFE/element) 适用于桌面端ie9+
	* [mint ui](https://github.com/ElemeFE/mint-ui) 适用于移动端
	* [iview](https://github.com/iview/iview) 适合做数据报表
	* [vant](https://github.com/youzan/vant) 有赞出品，更全更轻量
* ssr
	* [vue ssr](https://ssr.vuejs.org/zh/) vue 服务端渲染方案
	* [nuxt](https://github.com/nuxt/nuxt.js) vue 服务端渲染框架
	* [vue-php](https://github.com/Joe3Ray/vue-php) php渲染 vue
* 工程
	* [lavas vue pwa](https://github.com/lavas-project/lavas) vue pwa 应用示例
	* [bowl](https://github.com/ElemeFE/bowl/) 初始文件 localstorage 缓存
	* [vue-router](https://github.com/vuejs/vue-router) vue 路由
	* [vue-cli](https://github.com/vuejs/vue-cli) vue 项目创建工具
	* [vue-test-utils](https://github.com/vuejs/vue-test-utils) vue ui 测试工具
	* [DejaVue](https://github.com/MiCottOn/DejaVue) vue 可视化调试工具
* other
	* [weex](https://github.com/apache/incubator-weex) vue移动app
	* [vuido](https://github.com/mimecorg/vuido) 用 vue 构建桌面应用
	* [vuepress](https://github.com/vuejs/vuepress) 静态站点生成器，用于写文档
	* [vue-awesome-swiper](https://surmon-china.github.io/vue-awesome-swiper/) 基于 swiper 4，支持SSR

### GOOGLE

* [polymer](https://github.com/Polymer/polymer) 基于 web components 理念规范的库
* [angular](https://angularjs.org/) 完善的后台应用框架，推荐使用 TypeScript
	* [angular 中文社区](http://www.angularjs.cn/)
	* [ngDialog](https://github.com/likeastore/ngDialog)
* [flutter](https://github.com/flutter/flutter) 基于 Dart 的 app 开发框架
* fastpage SEO整站优化方案
	* [amp](https://www.ampproject.org/) 来自谷歌
		* [amp页面](https://www.ze3kr.com/2016/10/amp-html/amp/)
	* [mip](https://www.mipengine.org/) 来自百度
* [prerender](https://prerender.io/) 生成静态站点供搜索引擎识别

### 函数式

* [cycle](https://github.com/cyclejs/cyclejs/)
	* [cycle.js.org](https://cycle.js.org/)
	* [cyclejs.cn](http://cyclejs.cn/)
* [rxjs 事件流](https://github.com/Reactive-Extensions/RxJS)
	* [rxjs](https://github.com/ReactiveX/RxJS)
* [ramda](https://github.com/ramda/ramda) 创建具有不变性和无副作用的函数

### 微信小程序

* [微信小程序](https://mp.weixin.qq.com/debug/wxadoc/dev/?t=1474887496775)
* [spore-kit-wapp](https://www.npmjs.com/package/spore-kit-wapp) 个人工具，视图组件封装
* [微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp)
* 图表
	* [wx-charts](https://github.com/xiaolin3303/wx-charts)
* 框架
	* [wepy](https://github.com/wepyjs/wepy) 小程序开发框架，bug较多，打包机制不太合理
	* [mpvue](https://github.com/Meituan-Dianping/mpvue) 小程序开发框架，更贴近vue的写法
	* [wafer](https://github.com/tencentyun/wafer) 快速构建具备弹性能力的微信小程序

### 其他库与框架

* [PxLoader](https://github.com/thinkpixellab/PxLoader) 用于实现各种资源加载中状态
* [masonry](https://github.com/desandro/masonry) 瀑布流快速实现
* [SpinKit](https://github.com/tobiasahlin/SpinKit) 几个 css3 loading 效果
* [JSPatch](https://github.com/bang590/JSPatch) 封装js与ios交互
* [cheerio](https://github.com/cheeriojs/cheerio) 服务端的类jquery语法库
* [AlloyImage](https://github.com/AlloyTeam/AlloyImage) 腾讯出品，图形图像处理
* [AlloyFinger](https://github.com/AlloyTeam/AlloyFinger) 多点触控封装
* [mescroll](https://github.com/mescroll/mescroll) 上拉刷新，下拉加载交互库
* [smooth-scroll](https://github.com/cferdinandi/smooth-scroll) 点击锚点，平滑滚动
* [scrollama](https://github.com/russellgoldenberg/scrollama) 基于 IntersectionObserver 的滚动交互组件
* [twemoji](https://github.com/twitter/twemoji) 实现 Emoji 展示
* [prism](https://github.com/PrismJS/prism) 实现代码高亮

------

## 工具

### 文档

* wiki
	* [wiki语法说明](https://zh.wikipedia.org/wiki/Help:%E7%BC%96%E8%BE%91%E9%A1%B5%E9%9D%A2)
* markdown
	* [markdown语法说明](http://wowubuntu.com/markdown/)
	* [markdown语法示例](http://equation85.github.io/blog/markdown-examples/)
	* [md 转静态站](https://github.com/AlloyTeam/omi/tree/master/md2site)
	* [markdown-it](https://github.com/markdown-it/markdown-it) Markdown 解析器，vuepress 使用它完成对 md 文件的解析
	* [typora](https://typora.io/) 极致简洁的 markdown 编辑器
		* [typora](https://github.com/typora) typora 的 github 地址
* [gitbook](https://github.com/GitbookIO/gitbook)
	* [gitbook-cli](https://github.com/GitbookIO/gitbook-cli)
	* [gitbook 简明教程](http://www.chengweiyang.cn/gitbook/introduction/README.html)
* 文档撰写
	* ✭ [documentation](https://github.com/documentationjs/documentation) 使用jsdoc语法，生成文档更贴近现代风格，适合注释转文档
		* [jsdoc](https://github.com/jsdoc3/jsdoc) 部分格式陈旧，支持node生成方面不错
	* ✭ [vuepress](https://github.com/vuejs/vuepress) vue静态站点生成器，
	* ✭ [docsify](https://github.com/QingWei-Li/docsify) 适合md转文档，wepy使用这个撰写了文档，看起来很舒服
	* [docute](https://github.com/egoist/docute) 便捷的单页文档，风格比较现代
	* [typedoc](https://github.com/TypeStrong/typedoc) TypeScript项目的文档生成器，但看起来生成的文档过重
		* [deeplearnjs-doc](https://deeplearnjs.org/docs/api/globals.html) deeplearn.js 的文档，用typedoc生成
	* [docdash](https://github.com/clenemt/docdash) jsdoc模板，界面看起来比较舒服，移动端界面看起来不完善
	* [jsduck](https://github.com/senchalabs/jsduck) sencha出品，适合命名空间与类的文档描述，适合传统js库，不适合单独模块文档构建

### 代码编辑

* ✭ [vscode](https://github.com/Microsoft/vscode) 插件无需翻墙就能下载，整体功能对现代前端开发十分友好
	* Beautify, Prettier 美化代码
	* Debugger for Chrome 配合 chrome 控制台进行代码调试
	* Eslint, markdownlint, TSLint 检查代码规范
	* Vetur vue开发支持
	* Sublime Text Keymap and Settings Importer 支持使用 Sublime 的快捷键操作编辑器
* [sublime](https://www.sublimetext.com/) 性能很好，但是配置起来比较麻烦，而且插件资源都需要翻墙才能下载
	* [DocBlockr](https://github.com/spadgos/sublime-jsdocs) 便捷生成jsdoc可以处理的多行注释
* [vim](http://www.vim.org/) vim官方资源
	* [Learn-Vim-Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)
		* [循序渐进学习 vim](http://coolshell.cn/articles/5426.html)
	* [Vim快速选中、删除、复制引号或者括号中的内容](https://www.linuxsong.org/2010/09/vim-quick-select-copy-delete/)

### 代码展示

* ✭ [codepen](http://codepen.io/) 更适合编写showcase，在线编辑比较方便，各种预处理器齐全
* [jsbin](http://jsbin.com/?html,js,output)
* [jsfiddler](https://jsfiddle.net/) 访问感觉比较缓慢，但属于老牌代码展示工具，对于代码展示功能齐备

### 云服务

* [七牛云 免费CDN服务，图片上传](http://www.qiniu.com/)
* [语音识别，人脸识别 科大讯飞](http://www.xfyun.cn/)
* [腾讯文智中文语义平台](http://nlp.qq.com/)
* [讯飞开放平台](http://www.xfyun.cn/)

### 设计

* [sketch 轻量矢量设计工具](https://www.sketchapp.com/)
	* [sketch 中文网](http://www.sketchcn.com/)
* [cutterman 图片裁剪](http://www.cutterman.cn/zh)

### 协作

* ✭ [zeplin](https://www.zeplin.io/) 前端协作工具
	* [介绍](http://36kr.com/p/5036576.html)
* [蓝湖](https://lanhuapp.com/) 国内项目协作工具
* ✭ [leangoo](https://www.leangoo.com/) 看板工具
* [trello](https://trello.com/)看板 工具

### 分享

* [asciinema](https://asciinema.org/) 终端命令行录制工具
* [repl](https://repl.it/) 在线开源交互执行平台，可以演示在服务端运行的代码，jest在用
* [licecap](https://www.cockos.com/licecap/) 屏幕操作录制 gif

### 其他工具

* [检查设备屏幕相关参数](http://liangdong.sinaapp.com/tools/screen.html)
* [unicode 图表字符集合](http://www.unicode.org/charts/)
* [各个CDN服务提供的静态资源](https://cdnjs.com/)
	* [通用CDN文件](https://unpkg.com/#/)
* [在线JS代码格式化](http://tool.chinaz.com/Tools/JsFormat.aspx)
* [给项目起名](http://mrsharpoblunto.github.io/foswig.js/)
* [简繁转换](http://tool.chinaz.com/Tools/Gb_big.aspx)
* [贝塞尔动画生成器](http://greweb.me/bezier-easing-editor/example/)
* [TimeIs](https://time.is/zh/Beijing) 用于校对时间，验证直播延迟时有用
* [文件转base64](http://www.motobit.com/util/base64-decoder-encoder.asp)
* [regex101](https://regex101.com/) 在线正则检查工具，可用来研究正则是否存在致命缺陷
	* [一个正则表达式引发的血案，让线上CPU100%异常！](https://juejin.im/post/5b287ea6f265da596d04a324)
* [obsproject](https://obsproject.com/) 跨平台直播推流工具，适合测试rtmp直播
* [FSCapture](http://www.faststone.org/FSCaptureDetail.htm) 屏幕像素数值测量工具

------

## 其他资料

* 工具
	* [elasticsearch](https://github.com/elastic/elasticsearch) 开源搜索引擎
		* [Elasticsearch 权威指南（中文版）](https://legacy.gitbook.com/book/looly/elasticsearch-the-definitive-guide-cn/details)
	* [rsyslog](https://www.rsyslog.com/)
		* [日志管理Rsyslog](https://www.jianshu.com/p/e129ed893362)
		* [rsyslogd服务器及负载均衡](http://xstarcd.github.io/wiki/Linux/rsyslog_logrotate.html)
	* [docker](https://www.docker.com/)
		* [docker 从入门到实践](https://yeasy.gitbooks.io/docker_practice/introduction/what.html)
		* [dockerhub](https://hub.docker.com/) docker 仓库
		* [阿里云docker镜像服务](https://cr.console.aliyun.com)
* go
	* Beego 模块化的web框架
		* Bee 脚手架工具，支持项目结构生成，热编译，打包，版本升级，容器化
		* Beego Swagger 代码注释生成 api 在线文档
	* Termui 跨平台，自适应的UI/Dashboard工具
	* gomobile 在移动平台使用和构建 Go 的一套工具集，做原生应用
	* therecipe/qt 跨平台GUI库
	* present 幻灯片展示工具
* php
	* [smarty](http://www.smarty.net/)
	* [php之道](http://wulijun.github.io/php-the-right-way/)
	* [php Socket编程起步](http://www.downcodes.com/info/2009/05/30/20090530-114.html)
	* [swoole](https://github.com/swoole/swoole-src) 现代 PHP 开发，面向生产环境的 PHP 异步网络通信引擎
* 统计
	* [如何使用第三方统计工具](http://e.qq.com/faq/list074.html)
	* 数据可视化
		* [bdp](https://me.bdp.cn/home.html)
	* 站点统计
		* [baidu](http://tongji.baidu.com/)
		* [qq mta](http://mta.qq.com/)
		* [友盟](http://www.umeng.com/)
* 数据库
	* [FireBase](https://firebase.google.com/)
* 代码托管
	* [coding.net](https://coding.net/user)
	* [coding 码市](https://mart.coding.net/)
* 个人博客搭建
	* [hexo](https://hexo.io/)
* 聊天机器人
	* 微信
		* [wxpy](https://github.com/youfou/wxpy)
		* [itChat](https://github.com/littlecodersh/ItChat)
	* qq
		* [qqbot](https://github.com/nodejh/qqbot)
	* facebook
		* [claudia-bot-builder](https://github.com/claudiajs/claudia-bot-builder)
* 教学
	* [warriorjs](https://github.com/olistic/warriorjs) 一个编程游戏
	* [codecombat](https://github.com/codecombat/codecombat)

------

## 待整理
