# MEMORY.md — 长期记忆

## 项目约定
_全局约定（部署流程等）见 `~/.workbuddy/USER.md`_

## 用户偏好
_全局偏好见 `~/.workbuddy/USER.md`_

## 当前项目：心理健康日活动

- **内容**：5·25 心理健康宣传月 AI 海报参赛 + 自爱测试网页
- **受众**：初中生 / 家长
- **视觉风格**：莫兰迪色系（黄绿蓝粉），Claymorphism
- **输出文件**：`poster.html`（海报）、`quiz.html`（自爱测试）
- **GitHub**：`https://github.com/roby18/mental-health-selflove`
- **EdgeOne Pages**：`https://mental-health-selflove-prcpgq59.edgeone.cool?eo_token=4af35829c4b579407b5118b4cda6a2a9&eo_time=1779630962`
  - ⚠️ URL 必须带 `?eo_token=...&eo_time=...` 才能访问，裸 URL 返回 401
  - 海报 QR 码用 `window.location.href` 动态生成，部署后自动跟随无需手动更新 URL
