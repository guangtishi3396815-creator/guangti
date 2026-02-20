# 🎬 Seedance 2.0 电影级提示词智能体

一个专业的 AI 视频生成提示词工程工具，专为 Seedance 2.0 设计。帮助用户快速生成电影级质量的提示词，支持多种风格模板、镜头语言、光影效果和色彩风格。

## ✨ 功能特点

- 🎨 **12种风格模板**：科幻史诗、赛博朋克、纪录片、MV舞蹈、浪漫剧情、恐怖惊悚、动作场面、年代剧、水下世界、太空漫游、奇幻魔法、黑色侦探
- 🎥 **镜头语言**：全景、特写、跟踪、推轨、摇臂、斯坦尼康、手持、航拍等
- 💡 **光影效果**：电影光、黄金时刻、霓虹光、体积光、轮廓光、自然光等
- 🎨 **色彩风格**：青橙色调、胶片颗粒、高对比、低饱和、暖色调、冷色调等
- 📝 **中英双语提示词**：同时生成英文提示词和中文解释
- 🎬 **自动分镜脚本**：根据时长自动生成镜头分解

## 🚀 快速开始

### 方式一：直接使用（推荐）

访问在线版本：
- GitHub Pages: https://guangtishi3396815-creator.github.io/guangti/
- Vercel: https://seedance-cinema-agent.vercel.app/

### 方式二：本地部署

```bash
# 克隆仓库
git clone https://github.com/guangtishi3396815-creator/guangti.git
cd guangti/web

# 本地预览
python3 -m http.server 8080
# 或
npx serve .

# 打开浏览器访问 http://localhost:8080
```

### 方式三：部署到自己的服务器

```bash
# 复制文件到 web 服务器目录
cp -r web/* /var/www/html/

# 或使用 Vercel 一键部署
vercel --prod
```

## 📖 使用说明

1. **选择模板**：点击顶部风格模板快速填充场景描述
2. **自定义描述**：在文本框中输入你的创意场景
3. **选择参数**：设置视频时长、画面比例、情绪氛围
4. **选择标签**：点击镜头、光影、色彩标签组合效果
5. **生成提示词**：点击生成按钮，获取专业级提示词
6. **复制使用**：复制生成的提示词到 Kimi/Seedance 使用

## 🛠️ 技术栈

- 纯 HTML/CSS/JavaScript，无需后端
- 响应式设计，支持移动端
- 本地存储，保护隐私

## 📄 开源协议

MIT License - 可自由使用、修改、分发

## 🤝 贡献

欢迎提交 Issue 和 PR！

---

Made with ❤️ for AI Video Creators
