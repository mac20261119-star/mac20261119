# douyin-demo

抖音类短视频项目的工作区。

- `app/`：zyronon/douyin 的静态演示版（GPL-3.0，原作者声明不得商用，仅供学习）
- `docs/`：项目资料与提问记录
- `CLAUDE.md`：给 Claude Code 的项目说明，在 Claude Code 里打开这个仓库时会自动读取

## 本地运行

```bash
cd douyin-demo/app
python3 -m http.server 8080
```

然后在浏览器打开 http://localhost:8080（需要联网加载 Vue 等 CDN 资源）。
