# 个人 IP 替换小黑：调整清单与 Prompt 模板

## 仓库定义位置

- `ian-xiaohei-illustrations/SKILL.md`：定义整体任务、工作流、生成约束与交付口径。
- `references/xiaohei-ip.md`：定义小黑 IP 的外形、性格、动作职责与禁忌。
- `references/style-dna.md`：定义白底、极简、手绘、留白、颜色与禁忌。
- `references/composition-patterns.md`：定义构图类型、原创隐喻方法、动作池与反复刻规则。
- `references/prompt-template.md`：定义单张生图 prompt 模板。
- `references/qa-checklist.md`：定义生成后的质量检查与迭代规则。
- `assets/examples/`：只用于风格密度校准，不应复刻构图。

## 替换清单

- 把“小黑必须出现”改为“个人男孩 IP + 比熊搭档必须一起出现”。
- 把“小黑承担核心动作”改为“男孩承担主动作，比熊承担辅助动作；两者都不能只是装饰”。
- 保留仓库风格 DNA：16:9、纯白背景、黑色手绘线稿、大量留白、少量红橙蓝批注、单图只讲一个核心意思。
- 保留构图逻辑：抽象概念要变成一个低科技物理动作，例如压、筛、塞、拉、接、称、修补、开门。
- 颜色需要新增人物识别色：蓝白运动 T 恤、橄榄/卡其短裤、白鞋浅黄色鞋底；其他颜色仍然克制。
- 新增固定运动符号：羽毛球拍，必要时加一个小羽毛球。
- 新增固定搭档符号：白色比熊，圆头、黑豆眼、黑鼻子、吐舌笑、卷尾巴。
- QA 中新增检查：人物是否像你的 IP；比熊是否固定出现；两者是否参与画面动作；是否过度可爱、商业化或日漫化。

## 个人 IP 关键词

- 成人东亚男性的卡通男孩化 IP，短黑发，略侧分，圆润亲和脸，温和微笑。
- 蓝白渐变运动 T 恤，斜向刷痕纹理，橄榄/卡其短裤，白袜，白色运动鞋，浅黄色鞋底点缀。
- 羽毛球拍作为个人识别符号，可加小羽毛球。
- 固定搭档：白色比熊，蓬松圆头，黑豆眼，小黑鼻，开心吐舌，卷尾巴。
- 手绘铅笔/彩铅质感，线条柔和随性，轻微草稿感，白纸/白板背景。
- 画面功能：用一个荒诞但成立的动作解释一个观点。

## 禁忌

- 不要小黑原形、不要红蝴蝶结、不要蓝色长发、不要女性化。
- 不要眼镜，除非用户明确要求。
- 不要写实、3D、精致矢量、日漫高光、儿童绘本海报。
- 不要复杂背景、阴影、渐变、米色纸纹、科技感 UI。
- 不要让人物或比熊只是站着摆拍。
- 不要多余人物、水印、过多文字、左上角大标题。

## 标准 Prompt 模板

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art with slight pencil/color-pencil texture. Soft wobbly pen lines, loose sketch feeling, lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations, at most 4-6 short labels. Clean absurd product-sketch feeling. No gradients, no shadows, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring personal IP characters required:
1. A friendly adult East Asian male turned into a simple hand-drawn cartoon boy IP. Short neat black hair with slight side part, round gentle face, warm calm smile, no glasses. Outfit: blue-white gradient sports T-shirt with diagonal brush-stroke stripe accents, olive/khaki shorts, white socks, white athletic shoes with small pale yellow sole accents. Badminton racket is his personal symbol.
2. A small white Bichon Frise companion, always paired with the boy. Fluffy rounded head, tiny black eyes, small black nose, open smiling mouth with little tongue, compact body, curled tail. Same loose pencil/color-pencil style.

Role rule:
The boy must perform the core conceptual action. The Bichon must actively help with a smaller supporting action. Neither character may be decorative.

Theme:
{正文配图主题}

Structure type:
{Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{男孩在哪里、正在做什么；比熊如何辅助；主要物件是什么；信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{短标注1} / {短标注2} / {短标注3} / {可选短标注4}

Color use:
Black for line art and labels. Blue/light blue only on the boy's sports shirt and optional secondary notes. Olive/khaki only on shorts. Orange only for the main path or arrows. Red only for one key warning/result. The Bichon is white with minimal light cream pencil shading.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, dense explainer, anime image, 3D render, or photorealistic illustration. No extra people, no watermark.
```
