# RespView — JMeter 实时响应查看器

JMeter 监听器插件：运行时自动弹出悬浮窗、接口响应实时流式输出、JSON 自动格式化，无需手动点击查看。

---

## 安装

1. 下载 `auto-format-response-viewer.jar`（仓库根目录直接点文件 → Download）
2. 复制到 `<JMeter 安装目录>\lib\ext\`
3. **彻底关闭并重启 JMeter**（⚠️ 必须重启，否则旧类在内存里）

## 使用

1. 右键线程组 → **添加 → 监听器 → RespView**
2. 勾选「运行时弹出悬浮窗」
3. 运行测试 → 悬浮窗自动打开，实时显示所有接口响应

## 兼容性

- JMeter 5.3 / 5.4 / 5.5
- JDK 8+
- 悬浮窗只压在 JMeter 上，切出 JMeter 会被覆盖


