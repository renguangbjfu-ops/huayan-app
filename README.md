# 花颜 AI 美化

花颜 AI 美化是一款基于 Electron 的桌面照片美化工具。

## 功能

- 上传 JPG / PNG 照片
- 支持拖拽上传和剪贴板粘贴
- 填写 AILabTools API Key
- 选择清新自然、甜美少女、学院精致、高级质感等预设
- 调节美白、磨皮、瘦脸、大眼强度
- 查看原图和 AI 美化结果对比
- 下载处理后的图片
- 查看最近处理记录

## 本地运行

```bash
npm install
npm start
```

## 打包

```bash
npm run build:win
npm run build:mac
```

## GitHub 自动打包

上传到 GitHub 后，可以在 Actions 页面手动运行 `Build desktop app`。

也可以创建版本标签或发布 Release，GitHub 会自动生成安装包。
