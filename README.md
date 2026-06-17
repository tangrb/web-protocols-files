# web-protocols-files

[English](README.en.md)

应用协议文件托管仓库。本仓库用于集中存放各类应用协议文件，例如隐私政策、用户服务协议等。这些文件通过静态 HTML 页面对外提供，供 App Store、各大应用市场及审核流程引用与查验。

## 目录结构

```
web-protocols-files/
├── index.html                          # 协议文件索引页
├── JuZiShu/
│   └── iOS/
│       └── privacy-policy.html         # JZS EPager 隐私政策
├── README.md                           # 中文说明（本文件）
└── README.en.md                        # English documentation
```

## 协议文件

| 应用 | 平台 | 文件 | 说明 |
|------|------|------|------|
| JZS EPager | iOS | [JuZiShu/iOS/privacy-policy.html](JuZiShu/iOS/privacy-policy.html) | 隐私政策 |

部署后，可通过仓库根目录的 [index.html](index.html) 浏览所有协议文件的入口链接。

## 添加新协议

1. 在对应应用与平台目录下创建 HTML 文件，建议路径为 `{AppName}/{Platform}/{document-name}.html`。
2. 在 [index.html](index.html) 的协议列表中添加入口链接。
3. 更新本 README 与 [README.en.md](README.en.md) 中的协议文件表格。

## 许可证

本项目采用 [Apache License 2.0](LICENSE) 许可证。
