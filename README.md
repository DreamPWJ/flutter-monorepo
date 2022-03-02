## 基于Melos管理的Flutter多端统一的MonoRepo单体式仓库 单仓多包

### 项目代号: athena(雅典娜 智慧女神) 愿景: 使项目更易于复用迭代维护扩展、分离关注点并避免代码重复

### monorepo 最主要的好处是统一的工作流和共享代码, 兼顾通用性和独立性之间的最佳平衡点, 统一最佳实战只需搭建一套脚手架, 统一管理(规范、配置、开发、联调、构建、测试、发布等)多个包

### 目录结构

- packages: 可复用的基础通用包
- projects-*: 多端项目业务包 如projects-app、 projects-web、 projects-desktop等
- templates: 自定义灵活高效的代码生成器
- scripts: 自定义脚本 管理复杂多项目
- docs: 项目文档
- examples: 示例代码 常用代码模板和代码块提炼
- tests: 测试模块