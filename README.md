# Django Blog - 简洁高效的博客系统

![Django](https://img.shields.io/badge/Django-3.2%2B-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

## 项目概述

一个基于Django框架开发的轻量级博客系统，包含完整的文章发布、评论管理和后台管理功能，采用模块化设计便于扩展。

## 项目结构




```text
Django_blog/
├── blog/               # 核心博客功能
│   ├── models.py       # 数据模型定义
│   ├── views.py        # 视图逻辑
│   ├── templatetags/   # 自定义模板标签
│   └── static/         # 静态资源
├── comments/           # 评论系统模块
├── blogproject/        # 项目配置
└── templates/          # 前端模板系统
```


## 核心功能

### 博客功能
- 文章创建与发布
- 文章分类展示
- 后台内容管理
- 自定义模板标签系统

### 评论系统
- 用户评论功能
- 评论表单验证
- 评论管理界面

## 技术栈

- **后端框架**: Django 3.2+
- **数据库**: SQLite (支持切换其他数据库)
- **依赖管理**: Pipenv
- **前端模板**: Django Template Language

## 快速开始

### 环境要求
- Python 3.8+
- Pipenv (或直接使用requirements.txt)

### 安装步骤
bash
git clone https://github.com/your-repo/Django_blog.git
cd Django_blog
pipenv install  # 或 pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver


## 配置说明

1. 数据库配置: 修改`blogproject/settings.py`中的DATABASES设置
2. 时区语言: 可调整`TIME_ZONE`和`LANGUAGE_CODE`
3. 静态文件: 生产环境需配置STATIC_ROOT

## 扩展建议

1. 用户认证系统
2. 文章标签分类功能
3. 全文搜索功能
4. 富文本编辑器集成
5. 文章互动功能(点赞/收藏)
6. 阅读量统计系统

## 贡献指南

欢迎通过Pull Request贡献代码，请遵循以下规范：
1. 新功能开发请创建feature分支
2. Bug修复请创建hotfix分支
3. 提交信息采用约定式提交规范
4. 确保代码通过PEP8检查

## 许可证

MIT License

## 特别说明

本项目适合作为Django学习项目，包含了Django开发的典型模式和实践：
- 应用模块化设计
- 模板继承体系
- 表单验证处理
- 后台管理定制
 

提示：实际使用时建议补充以下内容：

1. 项目截图或演示GIF

2. 更详细的功能文档

3. API接口文档(如实现RESTful接口)

4. 部署指南(如Docker配置)

5. 测试覆盖率报告
