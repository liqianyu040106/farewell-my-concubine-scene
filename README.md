# 霸王别姬 · Farewell My Concubine — A Surreal Digital Stage

单文件 Three.js 互动场景，共五幕：

1. **雲上浮島 · Floating Isle**
2. **廳堂戲臺 · 楚漢一夜 · The Theater**
3. **後台化妝間 · 袁四爺贈冠 · The Dressing Room**
4. **妓院喜堂 · 小樓迎娶菊仙 · The Wedding Hall**
5. **夜徑 · 極光水袖與走不近的燈 · The Night Path**

## 运行
无需构建，任意静态服务器指向本目录即可，例如：

```bash
python3 -m http.server 8899
# 打开 http://127.0.0.1:8899/index.html
```

或直接使用 GitHub Pages 线上版本。

## 技术栈
- Three.js r160（CDN 引入，无构建工具）
- 单 HTML 文件 + 少量本地贴图（jpg/png）
- 所有模型/材质/动画均为程序化生成
