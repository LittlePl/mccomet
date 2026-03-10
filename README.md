生存大陆服务器网站说明文档
作者： EVILZIXIE---子邪
文件结构说明
生存大陆网站/
│
├── index.html              # 主HTML文件
├── assets/                 # 资源文件夹
│   ├── images/             # 图片资源
│   │   ├── server-logo.png # 服务器图标
│   │   ├── logo.png        # 网站图标
│   │   └── qr-code.png     # QQ群二维码
│   │   
│   │
│   └── fonts/              # 字体文件
│       ├── Minecraft.ttf   # Minecraft正版字体
│       └── MinecraftTen.ttf # Minecraft Ten字体
│   
│   
│   
│
└── README.md               # 本说明文档

注意：当前版本中CSS和JavaScript代码直接嵌入在index.html文件中，未分离。

可自定义内容指南
1. 基本信息修改
以下是您可以在index.html中修改的主要信息：

网站标题：修改<title>标签
服务器名称：搜索"生存大陆"并替换
服务器描述：修改hero区域和各个介绍部分的文本
服务器地址：修改join-server-host和相关加入链接
服务器端口：修改join-server-port和相关加入链接
联系方式：

服主QQ：2990621753
微信：IIlIIlIIllIlIlII




2. 图片资源替换
以下是需要准备和替换的主要图片资源：
服务器Logo

路径：assets/images/server-logo.png
尺寸：建议 48px × 48px
格式：PNG（透明背景）
用途：显示在导航栏和页脚

网站图标

路径：assets/images/logo.png
尺寸：建议 32px × 32px
格式：PNG（透明背景）
用途：浏览器标签页图标

QQ群二维码

路径：assets/images/qr-code.png
尺寸：建议 200px × 200px
格式：PNG/JPG
用途：显示在"加入我们"区域

背景图片
网站使用占位图，您需要替换成自己的图片：



3. 配置信息修改
服务器配置信息可在specifications部分修改：

CPU：AMD 7500F
内存：32GB 6000MHz
存储：SSD 7000MB/s
网络：50MB

4. 团队信息修改
修改server-team部分的团队成员信息，包括名称、角色、描述和联系方式。
样式定制
网站使用变量控制样式，您可以在CSS的:root选择器部分修改主题颜色：
css:root {
    --primary: #5ABD3C; /* 主色调 */
    --primary-light: #78E852; /* 亮版主色调 */
    --primary-dark: #3A8A2A; /* 暗版主色调 */
    --accent: #FFDF5E; /* 强调色 */
    /* 其他颜色变量... */
}
修改这些变量可以快速更换网站主题配色方案。
功能说明
网站包含以下主要功能：

服务器状态查询：自动连接到Minecraft服务器API获取实时状态
响应式设计：在PC、平板和手机等不同设备上自适应显示
联系方式一键复制：点击社交图标可自动复制联系信息
平滑滚动：点击导航链接平滑滚动到对应区域
视频播放：嵌入B站视频播放器
动画效果：多种精美动画效果增强用户体验
通知系统：操作反馈通知


持与联系方式
如有任何问题或需要定制开发，请联系：

作者：EVILZIXIE子邪
QQ：2990621753

版权声明
本网站代码版权归EVILZIXIE子邪所有，仅授权生存大陆服务器使用。未经许可，不得用于商业用途。

感谢您使用本网站模板，祝您的Minecraft服务器运营顺利！