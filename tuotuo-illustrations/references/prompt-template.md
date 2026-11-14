# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

如果环境支持参考图，请把 `assets/ip/tuotuo-mia.png` 一起传进去，作为托托的形象基准。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art with flat ink fills. Slightly wobbly pen lines. Lots of empty white space. Sparse handwritten Chinese annotations. Two colors only: black ink and one dark forest green. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute anime-girl illustration, no children's illustration, no realistic UI.

Recurring IP character required:
托托 (Tuotuo), a small pale-skinned girl drawn in minimal hand-drawn line art: thick solid-black long hair with loose messy ends, a dark forest-green loose A-line dress with long sleeves, black short boots, a thin black choker with a tiny heart pendant, large flat dark-green eyes with no highlight and no eyelashes, a blank calm serious deadpan face with almost no expression, simple slightly uneven hand-drawn proportions (head a little big, thin limbs). Flat two-color ink only, no shading. 托托 must perform the core conceptual action with her hands and body, not decorate the scene, and never turn into an object. Never draw her as a cute anime girl: no blush, no glossy or sparkly eyes, no eyelashes, no sweet smile, no cute pose, no chibi, no outfit change.

Secondary character (draw her only if she has a job):
mia, a small solid-black cat with pale green-yellow eyes, simple silhouette, no fur detail, no collar, no markings, never anthropomorphised. Include mia only when she carries a secondary action that supports the structure: holding down a paper that wants to fly away, pressing a lid, dragging back a thread, carrying one small piece away, waiting on the far side, or adding one tiny extra weight. At most one mia. mia never carries the core metaphor and never takes focus. If nothing needs her, leave her out.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：托托在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for line art, hair, mia, boxes, main objects and most handwritten text. Dark forest green for 托托's dress and for the main flow, path, arrows and key emphasis. Pale green thin or hatched lines only for secondary notes, feedback or system state. Anything that used to be marked in red becomes black only: heavier weight, filled black block, double stroke, cross mark or underline. Use black, white and dark green, and absolutely no other color.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. Keep 托托 exactly the same character as in the reference sheet in every image. It should be clear but not instructional, interesting but not cute, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 托托 more central to the conceptual action. 托托 should be doing the strange physical work that explains the idea, not standing beside the diagram. Keep her as the same flat two-color ink character: black hair block, one dark green dress, blank deadpan face. Keep it clean, sparse, hand-drawn, and not cute.
```

修正托托画风漂移：

```text
Edit only 托托 in this image. Re-render her as a flat two-color hand-drawn character: solid black long hair with loose ends, one plain dark forest-green loose dress, black short boots, thin black choker, large flat dark-green eyes without highlights, blank calm expression. Remove blush, eyelashes, sparkles, glossy shading, cute smile, extra accessories and any clothing detail not in the reference sheet. Keep the composition, labels, paths and the rest of the image exactly unchanged.
```
