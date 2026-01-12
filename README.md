# project - FastAPI 全要素模板

本项目基于 FastAPI，整合数据库（SQLAlchemy/sqlite）、中间件、状态管理、Swagger/Redoc 接口文档等。

## 快速开始

### 安装依赖

```bash
pip install -r requirements.txt
```

### 启动服务

```bash
uvicorn project.main:app --reload --app-dir src
```

- 访问接口文档: [http://localhost:8000/swagger](http://localhost:8000/swagger)

### 数据库

- 初次运行自动创建 sqlite 数据库 `test.db` 并建好表

### 测试

```bash
pytest
```

## 目录结构

请见项目根目录结构
