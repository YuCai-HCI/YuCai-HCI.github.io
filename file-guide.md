# YuCai-HCI.github.io 文件整理指南

## 目录结构

```
YuCai-HCI.github.io/
│
├── index.html                  ← 主页（将 academic-homepage.html 改名）
│
├── doc/
│   └── cv.pdf                  ← 个人简历
│
└── img/
    ├── photo.jpg               ← 侧边栏个人照片（建议 400×400px，正方形）
    ├── sidebar-bg.png          ← 侧边栏底部背景图（宽 720px，PNG 带透明渐变）
    │
    ├── research/               ← 研究方向卡片背景图（建议 800×500px）
    │   ├── hri.jpg             ← 人-机器人交互
    │   ├── vr.jpg              ← 虚拟现实
    │   └── design.jpg          ← 智能设计
    │
    ├── pub/                    ← 论文配图
    │   ├── science-robotics.jpg        ← Science Robotics 展开大图（建议 800~1200px 宽）
    │   ├── science-robotics-thumb.jpg  ← Science Robotics 缩略图（建议 200×200px）
    │   ├── tvcg-airflow.jpg
    │   ├── tvcg-airflow-thumb.jpg
    │   ├── vr-text-entry.jpg
    │   ├── vr-text-entry-thumb.jpg
    │   ├── ijhcs-robot.jpg
    │   ├── ijhcs-robot-thumb.jpg
    │   ├── idetc-shopping.jpg
    │   └── idetc-shopping-thumb.jpg
    │
    └── logo/                   ← 项目机构 logo（PNG 透明背景，高度 ~56px）
        ├── most.png            ← 科技部
        ├── nsfc.png            ← 国家自然科学基金委
        ├── zjnsf.png           ← 浙江省自然科学基金
        ├── alibaba.png         ← 阿里巴巴
        └── huawei.png          ← 华为
```

## 图片尺寸建议

| 用途 | 文件 | 建议尺寸 | 格式 | 说明 |
|------|------|----------|------|------|
| 个人照片 | photo.jpg | 400×400px | JPG | 正方形，CSS 会裁切为圆形 |
| 侧边栏背景 | sidebar-bg.png | 720px 宽 | PNG | 顶部透明渐变，底部为校园图 |
| 研究方向背景 | research/*.jpg | 800×500px | JPG | 会被裁切铺满卡片 |
| 论文大图 | pub/*.jpg | 800~1200px 宽 | JPG | 悬停展开时显示 |
| 论文缩略图 | pub/*-thumb.jpg | 200×200px | JPG | 右上角圆形角标 |
| 机构 logo | logo/*.png | 高度 56px 左右 | PNG | 透明背景，宽度自适应 |
| 简历 | cv.pdf | — | PDF | — |

## 命名规则

- 全部使用 **小写英文 + 连字符**，如 `science-robotics.jpg`
- 不要用中文、空格、大写字母
- 缩略图统一加 `-thumb` 后缀

## 上传步骤

1. 在本地按上述结构整理好所有文件
2. 将 `academic-homepage.html` 重命名为 `index.html`
3. 进入 GitHub 仓库 → Add file → Upload files
4. 将整个文件夹结构拖入上传（或使用 Git 命令行推送）
5. 等待 2~3 分钟，访问 https://YuCai-HCI.github.io 查看效果
