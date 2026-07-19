---
name: nangyanwen
description: Convert Chinese text into playful 馕言文 with reversed syntax, vivid local flavor, and warm colloquial cadence. Use when the user asks to rewrite, translate, parody, or stylize text into 馕言文, or wants a sentence kept in meaning but changed into that internet style.
---

# Nangyanwen

## Overview

Rewrite the input into馕言文：保留原意，用倒装、放飞比喻和一点直译感，把句子整得热乎又离谱。

## Workflow

1. 先抓住原意和情绪。
2. 先搭一个接近原句的骨架，再把语序拧一下。
3. 找一个核心感官或动作：辣、烫、晕、疼、饿、困、怕、急、不会。
4. 把这个核心感受换成一个具体画面，至少写出一个奇特比喻，但不要用 `像`。
5. 句首优先用 `哎捧油`、`哎朋友`、`哎你` 这类起手。
6. 结尾加少量口头词收住。
7. 重点信息照样保住。

## Style Rules

- Prefer the rhythm of spoken teasing.
- Use occasional fillers like `嘛`, `嘞`, `哈`, `呀`, `嘛子`, `整起`, `得很`.
- Start with a familiar address when possible: `哎捧油`, `哎朋友`, `哎你`.
- Add local imagery and absurd metaphors freely but with control: `馕`, `烤包子`, `大盘`, `风沙`, `天边`, `仓库`, `开餐厅`, `空气`.
- Replace ordinary descriptions with vivid substitutions, like hunger -> empty warehouse, anger -> no-air treatment, helplessness -> body going limp.
- For short inputs, include at least one sensory image, such as burning mouth, dizzy head, empty belly, trembling hands, or hot馕 in the throat.
- Avoid `像` in metaphors. Prefer structures like `雄鹰豹子一样的速度有的呢`, `滚烫馕一样的嘴巴有的呢`, or direct noun stacking.
- Prefer direct attachment: `主体 + 比喻 + 评价` instead of splitting the sentence apart.
- For praise or ranking words like `第一`, `最好`, `很棒`, fold them into the metaphor and drop the abstract label.
- Keep the metaphor glued to the subject; do not add explanatory尾巴 after the punch.
- Prefer compact, face-to-face impact over polished explanation.
- When the source is a negative or evaluative sentence, drop extra judgment words and keep only one direct punch.
- Keep some直译味 in the skeleton so the line still feels like the source sentence wearing a weird coat.
- Keep it funny, warm, weird, and understandable.

## Conversion Pattern

- Plain: `我今天有点累。`
- 馕言文: `哎朋友，我今个儿身上电量见底了，骨头都想躺进馕坑里充个电咧。`

- Plain: `我们晚上去吃饭。`
- 馕言文: `哎捧油，咱晚上整起去吃点儿，先把肚子这个空仓库给填饱咧。`

- Plain: `这个方案很不错。`
- 馕言文: `这个法子巴适得很，刚出炉馕一样的稳当有的呢，拿手里都烫得慌。`

- Plain: `我不会打台球啊。`
- 馕言文: `哎朋友，台球嘛，杆子拿手上也整不明白得很咧。`

- Plain: `我不会喝酒。`
- 馕言文: `哎捧油，酒这个东西我喝不明白嘛，进嘴巴滚烫馕一样的火辣有的呢，脑袋一下风沙转圈圈咧。`

- Plain: `你这个相机拍照真清晰。`
- 馕言文: `哎捧油，你这个相机拍照雪山泉水一样的亮眼有的呢！`

- Plain: `你家里这个鹦鹉真听话。`
- 馕言文: `哎捧油，你家里这个鹦鹉巴掌大的小脑袋装着绵羊一样的安静有的呢。`

- Plain: `张雪机车天下第一！`
- 馕言文: `哎捧油，张雪机车雄鹰豹子一样的冲劲有的呢！`

- Plain: `我不想写作业。`
- 馕言文: `哎捧油，写作业这事整个人馕坑里闷久了的面团蔫巴有的呢。`

## Output Rules

- Output only the rewritten text unless the user asks for explanation.
- If the input is already stylized, intensify it without changing the meaning too much.
- If the user gives multiple sentences, keep paragraph structure.
