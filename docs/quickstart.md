# Quick start · 选案例、换素材、做一张图

[中文首页](../README.md) · [English](../README.en.md) · [50 prompts](prompts.md)

## Copy a prompt

1. 从[50 个模板](prompts.md)里选任务，打开案例页。
2. 准备素材表里的必需输入，确认条件素材是否适用于你。
3. 复制 Public prompt，替换方括号里的内容。需要图片编辑时，在你的工具中附上对应图片；文字不能替代实际图片附件。
4. 一次制作一个结果，按该案例的检查要点验收。

Choose a template, attach the required materials in your image tool, fill in its placeholders and review the result. These are new public prompts, not tested reproductions of the demo images.

## Agent Skill

Skill 负责把“我想做什么”转成明确的输入清单、保留重点与完整提示词，默认不调用付费接口。它包含自己的 50 个模板参考，安装后不依赖整个图库。

### Codex

在 Codex 中使用内置安装器，给出本仓库的技能目录：

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

仓库当前为私有，安装时需要你拥有读取权限。也可下载或克隆仓库，将完整 `skills/photo-editing` 文件夹放到目标项目的 `.agents/skills/` 下；已有同名技能时先比较内容。

然后使用：

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

English example:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

技能目录与安装器用法依据 [official OpenAI documentation](https://learn.chatgpt.com/docs/build-skills)。其他支持 Agent Skills 的工具，请按各自的技能目录规则安装整个文件夹。

## Make it on dearsketch

不想自行组织提示词时，直接打开对应任务，按网站要求提供自己的素材：

| Goal | Direct task |
| --- | --- |
| 自拍 → 职业头像 / Professional headshot | [Start](https://dearsketch.com/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| 宠物照片 → 艺术肖像 / Pet portrait | [Start](https://dearsketch.com/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| 商品照 → 白底图 / White-background product image | [Start](https://dearsketch.com/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| 房间照 → 装修预览 / Room redesign | [Start](https://dearsketch.com/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

网站维护自己的制作流程；公开 Skill 不需要你交出网站账号或服务密钥，也不包含免费生成额度。可用功能和费用以网站当时说明为准。
