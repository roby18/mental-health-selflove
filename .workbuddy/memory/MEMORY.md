# MEMORY.md — 长期记忆

## 项目约定

### 网页部署流程（长期约定）
- **GitHub**：所有开发的网页/前端项目，完成之后自动推送到 GitHub
  - 账号：roby18
  - Token 存储在 `.workbuddy/.env`（已通过 `.gitignore` 排除）
  - **仓库命名**：必须根据项目内容取有意义的名字（全小写英文+连字符），禁止用工作空间目录名做仓库名。例如 `mental-health-selflove`、`mahjong-rhythm-game`
- **EdgeOne Pages**：需要部署上线时，使用 EdgeOne Pages 部署
  - API Token 存储在 `.workbuddy/.env`
- **凭证读取**：所有凭证从 `.workbuddy/.env` 读取，不硬编码
- **凭证路径**：项目级 `.workbuddy/.env`（非 `~/.workbuddy/.env`）
- **创建日期**：2026-05-24

## 用户偏好

- 简洁的视觉总结，习惯用带 emoji 的表格呈现信息
- 需求表达结构化，常用编号列表明确要求
- 迭代节奏快，同一消息中会提出多个修改需求
- 对输出质量和响应速度要求较高
