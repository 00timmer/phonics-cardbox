# Luca 的卡盒（phonics card box）

单文件网页 App：按遗忘曲线复习的 5 格卡盒、夹心法学新词、四关（认得 → 说出来 → 用出来 → 教别人）、流利度表计时。
记录存在本机浏览器 localStorage，无后端、无账号；换设备用「说明 → 备份 / 换设备」。

**在线使用：** https://00timmer.github.io/phonics-cardbox/ （手机浏览器打开 → 添加到主屏幕）

## 不要直接改这里的文件

源文件在 `~/Downloads/apps/phonics/tools/app_template.html`，数据来自 `tools/build_pack.py`。改完运行：

```bash
cd ~/Downloads/apps/phonics && python3 tools/build_app.py
cd ~/Downloads/apps/phonics-web && git add -A && git commit -m "Update" && git push
```

`build_app.py` 同时生成 claude.ai 版（`phonics/Luca-卡盒.html`）、这个网页版和安卓 APK 的 `www/index.html`。
