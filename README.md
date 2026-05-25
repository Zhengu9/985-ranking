# 985 CS/AI 夏令营排名

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-brightgreen)](https://zhengu9.github.io/985-ranking/)
[![Update Status](https://img.shields.io/badge/update-daily-blue)](https://github.com/Zhengu9/985-ranking/actions)

中国 **39 所 985 大学** 计算机 / 人工智能 / 软件方向研究生推免夏令营信息汇总，每日自动更新。

**在线访问：https://zhengu9.github.io/985-ranking/**

---

## 功能

| 视图 | 说明 |
|------|------|
| **综合排名** | 39所985完整排名、学科评估、AI/CS优势、夏令营时间、报名网站 |
| **报名状态** | 按"正在报名 / 即将开始 / 待发布"分类，含截止时间进度条 |

## 排名依据

综合以下维度：

- 教育部第四轮学科评估（计算机科学与技术）
- CSRankings 2026 全球AI/CS科研产出
- ABC中国大学人工智能专业排名
- 行业认可度与大厂校招表现
- 综合名校声誉与考研难度

## 本地运行

```bash
# 任意静态文件服务器即可
python -m http.server 8080
# 浏览器打开 http://localhost:8080
```

纯静态 HTML，无需构建，无需依赖。

## 自动更新

通过 Claude Code 每日定时任务自动搜索各校官网夏令营信息并更新页面，推送到 GitHub Pages 自动部署。

## 免责声明

夏令营时间以各校官网最新通知为准。本页信息仅供参考，请务必在报名前确认官方通知。

## License

MIT
