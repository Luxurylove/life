# 生命之歌 · SONG OF LIFE

AI 科幻短片独立展示页：改编自王晋康 1995 年科幻短篇《生命之歌》，
165 秒 / 33 镜 / 16:9，DeepSeek × 豆包 × agens × 剪映 全流程 AI 制作。

- 成片在线播放（`assets/life.mp4`，1080p，约 49MB）
- 故事与四幕结构
- AI 制作工具链（四步）
- 人物三视图、33 镜分镜板、乐谱墙参考图
- 完整分镜剧本（PDF）与制作复盘（PPTX）下载

## 本地预览

```powershell
python -m http.server 8080
```

浏览器打开 http://127.0.0.1:8080

## 部署到 GitHub Pages

把本目录里的全部文件上传到仓库 `Luxurylove/life` 的 `main` 分支根目录，
然后在仓库 Settings → Pages 里选择 `main` / `root`。
地址为：https://luxurylove.github.io/life/

（仓库名也可以换成其他名字，只要同步修改作品集里这件作品的跳转链接。）

## 文件

| 文件 | 说明 |
| --- | --- |
| `index.html` | 展示页（含播放器、故事、制作流程、参考资料） |
| `assets/life.mp4` | 网页版成片（1080p / 30fps / H.264） |
| `assets/cover.jpg` | 首屏与作品集共用的封面 |
| `assets/poster.jpg` | 播放器封面帧 |
| `assets/yuanyuan.jpg` | 元元三视图 |
| `assets/storyboard.jpg` | 33 镜分镜板 |
| `assets/score-wall.jpg` | 乐谱墙参考图 |
| `assets/life-song-storyboard.pdf` | 完整分镜剧本 |
| `assets/life-song-production.pptx` | 制作全流程复盘 |

原始 4K 母版（699MB）不随仓库上传，留在本地即可。
