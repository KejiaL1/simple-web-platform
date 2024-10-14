### `README.md`

# 简易博客平台

## 项目简介
这是一个使用 Flask 框架构建的简易博客平台。用户可以创建、查看、编辑和删除博客帖子。本项目旨在帮助开发者学习如何使用 Flask 搭建一个基础的 Web 应用程序。

## 功能
- 查看所有博客帖子
- 创建新博客帖子
- 编辑现有博客帖子
- 删除博客帖子

## 安装与运行

### 1. 克隆项目
```bash
git clone https://github.com/your-github-username/simple-blog-platform.git
cd simple-blog-platform
```

### 2. 创建虚拟环境并安装依赖
```bash
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

### 3. 运行应用程序
```bash
python app.py
```

打开浏览器，访问 `http://127.0.0.1:5000/` 即可查看博客平台。

## 项目结构
```
simple-blog-platform/
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── create.html
│   ├── edit.html
└── static/
    └── styles.css
```

## 依赖
- Flask==1.1.2

## 贡献
欢迎任何形式的贡献。请 Fork 本项目并提交 Pull Request。

## 许可证
本项目使用 MIT 许可证。
