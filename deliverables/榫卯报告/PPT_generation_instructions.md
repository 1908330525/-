PPT 自动生成说明（使用 python-pptx）

步骤示例（在本地环境执行）：
1. 准备环境
   - pip install python-pptx
2. 将 slides.md 与 images/ 目录放在同一文件夹
3. 运行示例脚本（示例：generate_ppt.py）

示例脚本（简化示例）：

```python
from pptx import Presentation
from pptx.util import Inches

prs = Presentation()
with open('榫卯技艺_专项研究报告_PPT_30页_slides.md','r',encoding='utf-8') as f:
    content = f.read()
# 解析 content（根据 "Slide N" 分段）并生成幻灯片
# 这是模板示例；你可以根据本项目需要调整版式与字体

# 保存
prs.save('榫卯技艺_专项研究报告_PPT_30页.pptx')
```

如需我代为在仓库中生成 .pptx 并提交（包含图像），请明确授权并提供是否要我使用 AI 服务生成图片。