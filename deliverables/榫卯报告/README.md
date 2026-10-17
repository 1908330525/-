# README — 榫卯技艺专项研究报告（交付包说明）

本交付包包含：
- PPT 逐页文案（slides.md） —— 可直接复制到 PPT 编辑器中或用于自动生成 PPT
- 完整讲稿（speaker_notes_full.md） —— 适合作为每页的 Speaker Notes
- AI 图片提示词（ai_prompts.csv） —— 50 条（中英对照），用于批量生成 16:9 高清图片
- fonts/README.txt —— 字体下载与嵌入说明
- PPT_generation_instructions.md —— 说明如何用脚本把 slides.md 转换为 .pptx

文件路径：/deliverables/榫卯报告/
生成分支：feature/sunmao-ppt

注意事项：
- 本次提交包含完整的 PPT 内容与图片占位说明，但不包含二进制字体文件与已生成图片。请根据 ai_prompts.csv 在你的图像生成器（Midjourney / StableDiffusion / DALL·E 等）生成图片并上传到 images/ 目录，或授权我代为生成并上传（需要额外配额）。
- 若你需要我继续把生成的图片嵌入并直接生成 .pptx 二进制文件，请回复授权，我将在分支上提交图片并生成 .pptx（注意：图片生成可能延长交付时间）。
