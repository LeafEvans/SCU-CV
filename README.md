# 四川大学中文简历模板

这是一个基于北师大、西北工业大学和武汉大学中文简历模板修改而来的 **四川大学简历模板**。该模板用于生成个人简历，支持个性化定制个人信息、教育背景、工作经历、荣誉等内容。

## 功能

- 使用 LaTeX 进行简历排版，自动生成格式化简历
- 支持自定义个人信息、教育背景、工作经历、科研成果、荣誉等
- 页眉、页脚和联系方式可轻松调整
- 提供段落和表格的多种排版选项，适应不同需求

## 文件结构

```
├── README.md             # 项目说明文件
├── main.tex              # 主 LaTeX 文件，包含简历内容
├── settings.tex          # LaTeX 设置文件，包含样式和格式
├── images                # 存放简历中使用的图片
│   ├── header.png        # 页眉图片
│   ├── footer.png        # 页脚图片
│   ├── logo_1.png        # 校名 logo
│   ├── logo_2.png        # 校徽 logo
│   └── avatar.jpeg       # 个人头像
```

## 使用方法

1. **克隆项目**

   使用 Git 将项目克隆到本地：

   ```bash
   git clone https://github.com/LeafEvans/SCU-CV.git
   ```

2. **编辑简历**

   在 `main.tex` 中根据个人信息编辑内容，如姓名、工作经历、荣誉等。通过修改 LaTeX 文件调整简历内容。

3. **编译简历**

   使用 LaTeX 工具编译 `main.tex` 生成 PDF 文件：

   ```bash
   xelatex main.tex
   ```

## 修改内容

- 校标和校名替换为四川大学
- 主题色调整为四川大学官方标识色

## 鸣谢

- [北师大中文 CV 模板](https://github.com/LeyuDame/BNUCV)
- [西北工业大学中文 CV 模板](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx)
- [武汉大学中文 CV 模板](https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd)