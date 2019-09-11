### 这里是dev分支
### 文件目录结构
  pages 页面
  component 组件
  style 样式
  utils 公有的库或组件
  router  路由文件
  store  全局状态管理文件
  assets 资源目录

### 预处理语言
  less
  npm less less-loader
  默认不支持less 需要在config中的webpack.config.js把所有的sass改成less

### UI框架
  antd  less
  npm install antd
  全局引入  
  在index.js中引入 import 'antd/dist/antd.css'
  按需引入

### 基本配置
  起别名
  config webpack.config.js  alias
  'style':path.join(__dirname,'../src/style')
  'style':path.resolve(__dirname,'../src/style')
  服务器代理

### 公有的库
  axios 二次封装
  路由
  react-redux
  
