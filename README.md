# 基于 Vue3 + Vite + Admin 打造通用后台框架

## 项目脚本
- pnpm start 执行脚本后，浏览器打开 http://127.0.0.1:5173/ 即可启动项目
- pnpm build 项目打包
- pnpm preview 预览打包后的项目

## 目录结构
后续补上

## 代码规范
- eslint 检查
- prettier 修改代码规范（建议 Vscode 配置保存自动修复）
- commit 前进行代码规范检测（TODO）
- commit 信息检测（TODO）

## 特性
- vite 构建项目，毫秒级启动速度
- 页面路由自动引入，只需在 pages 目录创建页面组件即可，无需 import
- 支持暗黑模式与切换
- pinia 管理项目
- 自动引入 vue、vue-router、自定义hooks 相关api
- 自定义组件自动引入，只需在 components 目录创建即可，无需 import
- 路由切换时，路由进度条自动化
- 图片自动压缩，修改压缩程度可在 vite.config.ts 修改
- svg组件的支持，通过<svg-icon name="xxx">的形状引入，svg资源放置 src/assets/svgs 内
- 国际化语言引入与切换功能，语言配置文件放置 locales 内，则可自动导入

## 业务清单（待做）
- 登录模块
- 权限模块
- 菜单模块
- 页面结构
- 表格封装
- 表单模块
- 弹窗模块
- 个人中心模块
- 面包屑模块
- Excel 导入、导出
- 富文本
- 列表排序