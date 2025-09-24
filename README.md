# AnnLab - 学术实验室网站模板

这是一个简洁、专业的学术研究实验室网站模板。模板采用纯HTML、CSS和JavaScript编写，无需服务器端语言支持，可以轻松部署在GitHub Pages等静态网站托管服务上。

## 特点

- 响应式设计，适配各种屏幕尺寸
- 清晰的学术信息展示架构
- 简洁、专业的视觉设计
- 易于自定义和扩展
- 无需数据库和后端支持

## 网站结构

- **首页 (index.html)**: 包含实验室简介和最新动态
- **团队成员 (people.html)**: 展示教师、学生和毕业生信息
- **发表论文 (publications.html)**: 按年份和类型展示研究成果
- **学术活动 (activity.html)**: 展示即将举行和过去的学术活动
- **加入我们 (join.html)**: 提供实验室招生和联系信息

## 如何使用

### 1. 下载模板

克隆或下载本仓库到本地：

```
git clone https://github.com/Ericismyself/AnnLab.git
```

### 2. 定制内容

- 编辑各个HTML文件中的内容，替换为你的实验室信息
- 在`images`文件夹中添加你的实验室相关图片
- 根据需要修改`css/style.css`文件自定义样式

主要需要修改的内容包括：

- 实验室名称和简介
- 团队成员信息和照片
- 研究方向和项目介绍
- 论文发表记录
- 学术活动信息
- 联系方式

### 3. 部署网站

#### GitHub Pages部署（免费）

1. 在GitHub上创建一个仓库
2. 将修改好的网站文件上传到该仓库
3. 在仓库设置中开启GitHub Pages功能
4. 选择主分支(main或master)作为发布来源
5. 网站将自动发布在`https://ericismyself.github.io/AnnLab`

#### 其他部署选项

- **Netlify**: 支持拖放部署，免费提供SSL证书
- **Vercel**: 针对静态网站的现代化托管平台
- **任何静态网站托管服务**: 直接上传文件即可

## 目录结构

```
annlab-template/
├── index.html            # 首页
├── people.html           # 团队成员页面
├── publications.html     # 发表论文页面
├── activity.html         # 学术活动页面
├── join.html             # 加入我们页面
├── css/
│   └── style.css         # 样式表
├── js/
│   └── main.js           # JavaScript功能
├── images/               # 图片文件夹
│   ├── professor1.jpg    # 示例图片（需要替换）
│   ├── professor2.jpg    # 示例图片（需要替换）
│   ├── event1.jpg        # 示例图片（需要替换）
│   ├── event2.jpg        # 示例图片（需要替换）
│   ├── event3.jpg        # 示例图片（需要替换）
│   └── event4.jpg        # 示例图片（需要替换）
└── README.md             # 说明文档
```

## 注意事项

- 请替换所有示例内容（教授、学生、论文、活动等）为你实验室的真实信息
- 上传图片前请确保图片大小适当，以提高网站加载速度
- 请替换联系信息为你实验室的真实联系方式

## git上传代码

- git status
- git add .
- git commit -m "添加团队成员头像和相关样式优化"
- git push -u origin main

## 兼容性

网站模板兼容所有现代浏览器，包括：

- Chrome, Firefox, Safari, Edge (最新版本)
- 移动端浏览器

## 许可

本模板采用MIT许可证发布，可自由使用于个人和商业项目。 