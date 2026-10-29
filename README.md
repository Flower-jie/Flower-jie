# 你好，我是花俊杰 · Flower Jie

**把想法，写成可以运行的作品。**

专注 Java 后端、微服务与 AI 应用的学习实践。从业务系统到知识库问答，持续补齐功能、验证问题、整理经验。

[访问项目首页](https://flower-jie.github.io/portfolio/) · [GitHub](https://github.com/Flower-jie) · [Gitee](https://gitee.com/Sunflower-hua)

网站源码同样开源：[GitHub](https://github.com/Flower-jie/portfolio) · [Gitee](https://gitee.com/Sunflower-hua/portfolio)

## 按方向发现项目

| 方向 | 项目 | 主要内容 | 源码 |
| --- | --- | --- | --- |
| AI 与知识库 | **知行 LearnHub AI** | 独立学习助手；资料导入、分块索引、可选 RAG、来源引用、会话与笔记 | [GitHub](https://github.com/Flower-jie/learnhub-ai) · [Gitee](https://gitee.com/Sunflower-hua/learnhub-ai) |
| 在线教育 · AI | **天机学堂 AI** | 课程、交易、学习进度与 Spring AI 流式聊天的微服务实践 | [GitHub](https://github.com/Flower-jie/tjxt-ai) · [Gitee](https://gitee.com/Sunflower-hua/tjxt-ai-public) |
| 本地生活 | **黑马点评** | 登录会话、商铺缓存、社交互动与 Redis 优惠券秒杀 | [GitHub](https://github.com/Flower-jie/dark-horse-review) · [Gitee](https://gitee.com/Sunflower-hua/dark-horse-review-public) |
| 电商与外卖 | **苍穹外卖** | 菜品、购物车、订单、支付退款与营业状态管理 | [GitHub](https://github.com/Flower-jie/sky-take-out) · [Gitee](https://gitee.com/Sunflower-hua/sky-take-out-public) |
| 开发者工具 | **个人项目首页** | 响应式作品集；项目搜索、分类筛选与数据驱动的项目卡片 | [GitHub](https://github.com/Flower-jie/portfolio) · [Gitee](https://gitee.com/Sunflower-hua/portfolio) |

## 正在实践的技术

`Java` · `Spring Boot` · `Spring Cloud` · `MySQL` · `Redis` · `MyBatis` · `Spring AI` · `RAG` · `HTML / CSS / JavaScript`

### 从资料到可追溯的回答

**导入资料 → 文本分块 → 建立索引 → 检索证据 → 可选模型生成 → 来源引用 → 学习笔记**

知行默认使用无需 API 的本地词项哈希检索，**不将其冒充语义向量或模型回答**。配置后端 OpenAI 兼容服务后，可以启用语义向量与生成式问答；密钥不进入网页或代码。没有足够证据时，不编造答案。

## 项目说明

- 天机学堂、黑马点评、苍穹外卖来自课程学习实践，保留原有项目标识，在公开脱敏版本上继续改进，并非全部从零原创。
- 项目首页是静态网站；业务后端和 AI 助手需要在自己的环境中启动，不等同于已部署的在线业务服务。
- 公开源码不包含真实密钥。运行时需自行提供环境变量及所需数据库、中间件或模型服务。
- 首页的项目与类别由 [`projects.json`](https://github.com/Flower-jie/portfolio/blob/master/projects.json) 管理，新增项目无需复制页面组件。此个人主页的分类表可以同步补充。

---

**Build thoughtfully. Learn continuously. Share honestly.**
