# 👋《手把手教您使用Nuxt3框架(Nuxt3中文开发教程)》配套示例源码
《手把手教您使用Nuxt3框架(Nuxt3中文开发教程)》v3.0.0共有83页，基于Nuxt v3.0.0 stable稳定版撰写和验证通过。本源代码是中文教程的配套示例，按章节分类提供，有详细注解。
## 适合对象
Nuxt3中文教程适合Nuxt3初学者学习和实践，资深者快速参考，爱好者持续跟踪新功能和最佳实践。
## 示例在线预览
Nuxt3中文教程共有89个章节，源代码为其中关键的35个章节示例，详情浏览[示例在线预览网址](https://www.dvtop.cn/nuxt/examples/3.0.0/)体验。   
示例在线预览网址：<https://www.dvtop.cn/nuxt/examples/3.0.0/>
## 获取中文教程
![“nuxt”微信订阅号](https://www.dvtop.cn/nuxt/examples/3.0.0/resource/img/qrcode.jpg)   
原创不易，请关注“nuxt”微信订阅号后浏览各章节内容或有偿提前下载全文档。   
“nuxt”微信订阅号提供持续中文操作指南，关键功能示例代码，项目开发实例和源代码，SEO优化，技术咨询等混合渲染应用相关内容。
## 中文教程全文目录（83页）
<font size=2>每行分为3列，通过空格分开，依次为章节数、标题、页数。</font>    
> 1 修订记录	5   
> 1.1 v3.0.0-rc.10	5   
> 1.2 v3.0.0 5   
> 2 初识Nuxt3	6   
> 2.1 框架特色	6   
> 2.2 渲染流程	7   
> 2.3 版本差异	7   
> 3 上机准备	9   
> 3.1 知识准备	9   
> 3.2 Node.js环境	10   
> 3.3 Visual Studio Code开发工具	11   
> 3.3.1 下载和安装工具	11   
> 3.3.2 安装工具扩展包	11   
> 3.3.3 工具常用设置	12   
> 3.4 创建Nuxt3项目	12   
> 3.5 示例代码下载	14   
> 4 开发教程	15   
> 4.1 目录和文件	15   
> 4.2 页面（pages）	16   
> 4.3 页面组件（components）	17   
> 4.3.1 约定引用	17   
> 4.3.2 动态引用	18   
> 4.3.3 懒加载组件	19   
> 4.3.4 更多组件使用	19   
> 4.4 页面布局（layouts）	19   
> 4.4.1 默认全局布局	20   
> 4.4.2 自定义布局	20   
> 4.5 模块化代码	21   
> 4.5.1 工具包（utils）	22   
> 4.5.2 公共函数（composables）	22   
> 4.6 路由模式	24   
> 4.6.1 页面路径	24   
> 4.6.2 动态路由	24   
> 4.6.3 通配路由	25   
> 4.6.4 嵌套路由	25   
> 4.6.5 自定义路由	26   
> 4.7 路由中间件（middleware）	27   
> 4.7.1 全局路由中间件	28   
> 4.7.2 命名路由中间件	28   
> 4.7.3 内联路由中间件	29   
> 4.7.4 页面路由验证器	29   
> 4.8 导航	30   
> 4.8.1 组件式导航	31   
> 4.8.2 编程式导航	31   
> 4.9 过渡动画	32   
> 4.9.1 页面过渡	32   
> 4.9.2 布局过渡	34   
> 4.9.3 更多过渡	35   
> 4.10 插件（plugins）	35   
> 4.10.1 自主开发插件	35   
> 4.10.2 使用AntD插件	36   
> 4.10.3 使用Bootstrap插件	37   
> 4.11 内容管理（content）	41   
> 4.11.1 简单使用	41   
> 4.11.2 高阶应用	42   
> 4.12 静态资源（assets和public）	42   
> 4.12.1 public目录	42   
> 4.12.2 assets目录	43   
> 4.13 服务端处理（server）	44   
> 4.13.1 MIDDLEWARE中间件	44   
> 4.13.2 API接口	45   
> 4.13.3 ROUTES路由	46   
> 4.14 数据获取	47   
> 4.14.1 准备数据和API	48   
> 4.14.2 $fetch	50   
> 4.14.3 useAsyncData和useLazyAsyncData	52   
> 4.14.4 useFetch和useLazyFetch	54   
> 4.15 异常处理	56   
> 4.15.1 异常处理分类	56   
> 4.15.2 全局异常处理	57   
> 4.15.3 异常处理函数	58   
> 4.15.4 异常嵌入页面展示	58   
> 4.16 渲染模式	60   
> 4.16.1 客户端渲染	61   
> 4.16.2 服务端渲染	62   
> 4.16.3 混合渲染	63   
> 4.16.4 边缘计算渲染	65   
> 4.17 搜索引擎优化SEO	65   
> 4.17.1 SEO技术要点	65   
> 4.17.2 SEO配置	66   
> 4.17.3 robots.txt	70   
> 4.18 其他	71   
> 4.18.1 全局sass变量和动态样式	71   
> 4.18.2 Nuxt3模块（color-mode示例）	72   
> 4.18.3 常用配置和常见问题	75   
> 5 打包部署	78   
> 5.1 项目打包	78   
> 5.2 部署使用	78   
> 5.2.1 Node.js	78   
> 5.2.2 PM2	79   
> 5.2.3 Nginx等静态服务器	80   
> 5.2.4 云服务	81   
> 6 联系我们	82   
> 附：参考资料	83   
## 源代码使用
克隆源码：git clone https://github.com/eoctdm/nuxt3-chinese-examples.git   
（备选）：git clone https://gitee.com/eoctdm/nuxt3-chinese-examples.git  
进入工程：cd nuxt3-chinese-examples   
安装依赖：npm i   
运行项目：npm run dev   
浏览体验：http://localhost:3000   
## 配套示例源码许可证
MIT License