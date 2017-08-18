# amWiki 开发计划表

## v1.2.1

- 增加修改 web 端 library 目录路径的配置项 #47
- markdown 基础语法扩展，允许使用高亮标签对文字飘红
- 目录生成优化，识别标题是否已经带有序号 #33

## v1.2.2 _(under way)_

- 增加短链接模式 #53
- 增加数学公式渲染
- 增加 markdown 式脑图渲染
- 增加转义识别，允许使用 `\` 转义来阻止语法符解析 #71
- 增加扩展名识别，允许使用 `.markdown` 扩展名 #49

## v1.2.3

- markdown 新式语法设计，允许表格单元格合并
- 引入第三方评论系统
- 允许导航栏拖动大小和完全折叠 #63
- 导航栏目录增加悬停 title #63

## v1.3.0 

- 增加接口 Mock 模块，没有后端服务也有接口
    - 创建基于 WorkerService 的请求拦截与响应机制
    - 增加控制 Mock 增、改、删、暂停、继续的操作句柄
- 增加基于 fetch 请求的高级接口测试模式
    - fetch 与 $.ajax 协作封装，不支持 fetch 降级为 $.ajax
    - 增加 form-data 请求模式，允许上传文件
    - 增加 raw 请求模式，提供数种 Content-Type 以供选择
- 调整测试面板 UI 布局

## v1.3.1 

- 同一接口允许定义多个地址，可在测试面板上切换
- 更加友好的接口信息抓取和提示

## v1.3.2

- 全局参数单个开关
- 增加接口响应类型为 json 时的语法高亮
- 优化两处文字按钮为图标

## v1.4.0

- 增加 SEO 模块
    - 在 /pages 目录下结构扁平的输出所有文章纯静态 html
    - 文章 html 不带全库导航、不带 keywords、以 h1 为 title
    - index.html 优化，预置用于 SEO 的导航 html
    - 转换所有库内跳转的链接为 SEO 链接

## v1.4.1

- 增加 sitemap.xml 文件输出
- 文章 html 优化，增加移动的搜索匹配 meta
- index.html 优化，首页内容区预置最新文档链接

## v1.5.0

- 增加 Web 端插件模块

## v1.6.0

- 增加自定义主题模块

## v1.7.0

- 增加工作端扩展包模块

## v1.8.0

- 增加 Web 端、工作端两端即时协作模块

## v1.8.1

- 协作模块扩充，Atom 编辑器深度即时绑定
