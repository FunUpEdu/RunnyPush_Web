# RunnyPush Web

RunnyPush 的简单前端实现，用于悦动金职。

这是一个基于 Vue.js 的现代化 Web 应用程序，提供运动数据展示、排名统计等功能。

## 技术栈

- **前端框架**: Vue 3
- **构建工具**: Vite
- **UI 组件库**: Element Plus
- **状态管理**: Pinia
- **路由管理**: Vue Router
- **HTTP 客户端**: Axios

## 项目结构

```
src/
├── assets/          # 静态资源文件
├── components/      # 组件
│   └── icons/      # 图标组件
├── router/         # 路由配置
├── stores/         # 状态管理
├── views/          # 页面视图
│   ├── HomeView.vue
│   ├── Login.vue
│   ├── Rankings.vue
│   └── ToDay.vue
├── App.vue         # 根组件
└── main.js         # 入口文件
```

## 安装依赖

```bash
pnpm install
```

## 开发环境运行

```bash
pnpm dev
```

## 构建生产版本

```bash
pnpm build
```

## 预览生产版本

```bash
pnpm preview
```

## 许可证

本项目采用 Apache License 2.0 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。
