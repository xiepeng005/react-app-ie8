# react-app-ie8
 - react+redux+react-router+cmui+html5+css3+less+es6+webpack+兼容IE8
 - 适合开发各种webapp、企业网站、后台管理系统等等任何系统
 - cmui仓库为https://github.com/womendi/cmui.git
 - 代码实例：ai智能空间react版  http://react.aiplat.com 
 - 对应实例：ai智能空间vue版  http://www.aiplat.com 

---

# 代码目录结构
### 习惯vue后，改为与vueapp类似(https://github.com/womendi/vueapp)

 - build           ------webpack配置目录
 - config          ------webpack打包配置目录
 - dist            ------npm run build后实际布署代码目录
 - src             ------代码主体目录
 - --- api         ------静态json目录
 - --- assets      ------静态css、images、less文件目录
 - --- components  ------公共组件目录
 - --- plugins     ------公共函数或插件目录
 - --- redux       ------store、reducers、action目录
 - --- routes      ------路由配置目录
 - --- views       ------路由对应页面视图目录
 - --- main.js     ------应用入口文件
 - index.html      ------单页面应用公共html入口文件

---

# clone
 - $ git clone https://github.com/womendi/react-app-ie8.git

# 安装依赖
 - $ cd react-app-ie8
 - $ npm install -g cnpm --registry=https://registry.npm.taobao.org
 - $ cnpm install
 - 或者cd之后直接$  npm  install

# 开发模式(两种)

# 开发模式1(热更新代码，手动刷新页面，支持IE8调试)
 - $ npm run dev  或  npm start

# 开发模式2(热更新代码，自动刷新页面，不支持IE8调试)
 - $ npm run dev2
 - 
 - 最后看到以下这句 表示webpack编译成功
 - webpack: Compiled successfully.
 - 
 - 打开 http://本机ip:3008，方便手机在局域网访问

# 打包项目
 - $ npm run build
 - 整个项目代码打包到dist目录，打开其中index.html就是项目 首页
 - 布署到服务器，直接将dist目录中文件放在服务器根目录

# 兼容性
 - PC端兼容IE8及以上
 - 手机端兼容安卓与ios等等各种系统，不区分机型
 - 兼容一切可联网设备，比如TV等等,不区分尺寸大小