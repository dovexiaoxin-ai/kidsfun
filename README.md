🎈 奇趣乐园 (KidsFun)
一个专为3-12岁儿童设计的绚丽多彩、充满想象力的Django网站。

✨ 特色功能
🎮 互动游戏
数学挑战 - 有趣的数学题目，锻炼计算能力
单词拼图 - 看图片猜单词，学习英语
记忆卡片 - 配对游戏，训练记忆力
创意涂色 - 自由绘画，发挥想象力
📚 学习资源
数学乐园
科学探索
语言学习
艺术创作
👨‍👩‍👧‍👦 家长专区
儿童网络安全指南
屏幕时间管理建议
各年龄段教育标准
亲子活动推荐
🎨 设计特点
绚丽多彩的UI - 使用明亮活泼的色彩搭配
丰富的动画效果 - GSAP动画、浮动元素、粒子效果
响应式设计 - 完美适配手机、平板和电脑
儿童友好 - 大按钮、清晰图标、简单操作
🚀 快速开始
安装依赖
pip install django
数据库迁移
python manage.py makemigrations
python manage.py migrate
创建管理员账号
python manage.py createsuperuser
启动服务器
python manage.py runserver
访问 http://127.0.0.1:8000/ 即可看到网站

管理后台
访问 http://127.0.0.1:8000/admin/ 进入管理后台

默认账号: admin 默认密码: admin123

📁 项目结构
kidsfun/
├── kidsfun/              # 项目配置
│   ├── settings.py       # 设置文件
│   ├── urls.py           # URL路由
│   └── ...
├── main/                 # 主应用
│   ├── models.py         # 数据模型
│   ├── views.py          # 视图函数
│   ├── admin.py          # 后台管理
│   └── ...
├── templates/            # HTML模板
│   ├── base.html         # 基础模板
│   ├── main/             # 主页面模板
│   └── games/            # 游戏页面模板
├── static/               # 静态文件
│   ├── css/              # 样式文件
│   │   └── style.css     # 主样式
│   └── js/               # JavaScript文件
│       └── main.js       # 主脚本
└── manage.py             # 管理脚本
🎯 技术栈
后端: Django 5.x
前端: HTML5, CSS3, JavaScript
动画: GSAP (GreenSock Animation Platform)
样式: Tailwind CSS
字体: Fredoka, Open Sans
🌈 色彩方案
主色蓝: #3D5AFE
主色红: #FF5252
主色黄: #FFD600
主色绿: #69F0AE
主色橙: #FFAB40
主色青: #64FFDA
主色粉: #FF4081
主色紫: #E040FB
📝 模型说明
GameCategory
游戏分类模型，包含名称、描述、颜色等字段

Game
游戏模型，包含名称、分类、难度、年龄范围等字段

LearningCategory
学习分类模型

LearningResource
学习资源模型，包含类型（视频/文章/互动/游戏）

ParentResource
家长资源模型

GameScore
游戏分数记录

UserProgress
用户学习进度

🔧 自定义配置
添加新游戏
在 main/views.py 中创建新的游戏视图
在 main/urls.py 中添加URL路由
在 templates/games/ 中创建游戏模板
在 static/js/main.js 中实现游戏逻辑
修改主题颜色
编辑 static/css/style.css 中的CSS变量

🛡️ 安全说明
所有用户输入都经过验证
CSRF保护已启用
内容安全策略可配置
适合儿童的安全环境
📄 许可证
MIT License

🤝 贡献
欢迎提交Issue和Pull Request！

📧 联系方式
邮箱: hello@kidsfun.com
电话: 400-123-4567
🌟 让每个孩子都能快乐学习、健康成长！
