# 四川大学中文简历模板

本项目基于北京师范大学、西北工业大学和武汉大学中文简历模板进行修改和优化，提供了专为 **四川大学** 定制的 LaTeX 简历模板。该模板支持个性化定制，包括个人信息、教育背景、工作经历、荣誉等内容，帮助用户快速生成格式化且专业的简历。

<p align="center">
  <img src="https://leafalice-image.oss-cn-hangzhou.aliyuncs.com/img/c86e1906c81439c602ee6dde67e99b5.jpg" alt="SCU-CV-1" width="45%" />
  <img src="https://leafalice-image.oss-cn-hangzhou.aliyuncs.com/img/909bb73dddebedc368621499224c57d.jpg" alt="SCU-CV-2" width="45%" />
</p>

## 主要功能

- **自动排版**：利用 LaTeX 自动生成专业化简历格式。
- **个性化定制**：支持自定义个人信息、教育背景、工作经历、科研成果、荣誉等模块。
- **灵活调整**：页眉、页脚及联系方式等细节可轻松定制。
- **多样化排版选项**：提供多种段落和表格样式，适应不同用户的需求。

## 项目结构

```
├── README.md             # 项目说明文件
├── main.tex              # 主 LaTeX 文件，包含简历正文内容
├── settings.tex          # LaTeX 设置文件，包含样式和格式定义
├── LICENSE               # 许可证文件，使用 MIT 许可证
├── images                # 存放简历中使用的图片文件
│   ├── header.png        # 页眉图片
│   ├── footer.png        # 页脚图片
│   ├── logo_1.png        # 校名 logo
│   ├── logo_2.png        # 校徽 logo
│   └── avatar.jpeg       # 个人头像
```

## 使用说明

1. **克隆项目**

   首先将该项目克隆到本地：

   ```bash
   git clone https://github.com/LeafEvans/SCU-CV.git
   ```

2. **编辑简历内容**

   打开 `main.tex` 文件，填入个人信息、教育背景、工作经历、荣誉等内容。通过编辑 LaTeX 源文件实现简历内容的修改和个性化定制。

3. **编译简历**

   使用 XeLaTeX 或其他 LaTeX 工具编译 `main.tex`，生成 PDF 格式的简历：

   ```bash
   xelatex main.tex
   ```

## 模板修改说明

- **品牌定制**：校名与校徽已更换为四川大学官方标识。
- **主题色调整**：使用四川大学官方颜色进行模板设计。

## 鸣谢

特别感谢以下项目提供的设计灵感：
- [北京师范大学中文简历模板](https://github.com/LeyuDame/BNUCV)
- [西北工业大学中文简历模板](https://github.com/CSW33/NPU-CV)
- [武汉大学中文简历模板](https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd)

本模板为四川大学的学生及校友提供了一个便捷、高度定制化的简历生成工具。
