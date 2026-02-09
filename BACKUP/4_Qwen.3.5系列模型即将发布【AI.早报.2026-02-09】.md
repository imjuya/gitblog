# [Qwen 3.5系列模型即将发布【AI 早报 2026-02-09】](https://github.com/imjuya/gitblog/issues/4)

![](http://testtttt.oss-cn-guangzhou.aliyuncs.com/imagehub/20260209/20260209084949647072fdba_cover_95db.jpg)

# AI 早报 2026-02-09

## 概览
### 精选
- Qwen 3.5系列模型即将发布 `#1`
### 模型发布
- xAI上线Grok Imagine Image Pro 模型 API `#2`
### 产品应用
- CodeBuddy团队发布AI桌面工作台WorkBuddy `#3`
### 前瞻与传闻
- 字节即将推出Seedream 5.0预览版 `#4`
- Meta AI 已在官网测试最新模型 Avocado `#5`

---

## Qwen 3.5系列模型即将发布 `#1`
> **千问团队**正在推进 **Qwen 3.5** 系列模型的发布，其已向 `Transformers` 代码库提交相关支持 `PR`。该系列模型采用混合架构，结合 `Gated DeltaNet` 与混合注意力机制，原生支持多模态输入。

千问团队正在推进 **Qwen 3.5** 系列模型的发布，其 **已向 Hugging Face Transformers 代码库提交相关支持 PR**。该系列采用混合架构，结合 `Gated DeltaNet` 与 `混合注意力机制`，原生支持文本、图像及视频处理。代码 PR 确认了至少两个版本的模型存在：`Qwen3.5-9B-Instruct` 和 `Qwen3.5-35B-A3B-Instruct`。

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/aidaily/95db0821-8e25-40a2-8645-bfffdc0798d4/24a0f928-1269-40e2-9c2e-055d3b21daa1/m001.png)

```
https://github.com/huggingface/transformers/pull/43830/
```

---

## xAI上线Grok Imagine Image Pro 模型 API `#2`
> xAI 近日正式宣布推出名为 **Grok Imagine Image Pro** 与 **Grok Imagine** 的图像生成模型，支持文本生图、图像编辑、风格迁移及批量生成。用户可通过 API 调用这两款模型。

xAI 正式宣布推出名为 **Grok Imagine Image Pro** 与 **Grok Imagine Image** 的两款图像生成模型。模型支持 **文本生成**、**自然语言编辑**、**多轮迭代**、**风格迁移** 以及 **批量生成**，用户可通过 `API` 访问。`API` 调用定价为 **Pro 版 $0.07/图**，**标准版 $0.02/图**。

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/aidaily/95db0821-8e25-40a2-8645-bfffdc0798d4/80399f4c-0d03-4bbf-8f50-9a1de16e9ba5/m001.png)

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/aidaily/95db0821-8e25-40a2-8645-bfffdc0798d4/80399f4c-0d03-4bbf-8f50-9a1de16e9ba5/m002.png)

```
https://docs.x.ai/developers/model-capabilities/images/generation
https://x.com/xai/status/2020313728802242673
```

---

## CodeBuddy团队发布AI桌面工作台WorkBuddy `#3`
> **腾讯云CodeBuddy团队**发布`WorkBuddy`，支持自然语言指令执行多模态任务。产品已开放内测，适用于文件处理、PPT生成、海报设计、知识库构建等场景。

**腾讯云 CodeBuddy** 团队近日发布了 `WorkBuddy`，一款定位为全场景职场 AI 智能体的桌面工作台，目前已开放内测申请。该产品支持通过自然语言下达任务，可在本地电脑自主规划并执行多模态复杂任务，核心功能包括对经授权的本地文件进行批量处理、生成文档/表格/PPT、开展数据分析及行业调研。

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/aidaily/95db0821-8e25-40a2-8645-bfffdc0798d4/31b0c065-fbc6-424d-b846-cf0b6c9b6e01/m001.png)

```
https://mp.weixin.qq.com/s/jepj-IFv3UR9LpZlt-h82w
https://www.codebuddy.cn/work
```

---

## 字节即将推出Seedream 5.0预览版 `#4`
> 字节即将推出 **Seedream 5.0** 预览版，相关文档已发布，该模型支持联网检索、精准编辑与智能推理，首发 `2k`/`4k` 高清生图且限时免费。

**字节跳动**的图像生成模型 `Seedream（即梦）` 即将推出 `5.0-Preview` 版本，提供**联网实时检索**、**编辑精准可控**及**智能逻辑推理**三大核心功能，并首发**限免2k与4k清晰度**。但官方文档称该预览版在真实感与美感上存在效果劣化，建议对生成效果有严苛需求的用户使用 `4.5` 版本或等待**年后**发布的 `5.0` 正式版。

`5.0-Preview` 首次支持**检索生图**功能，旨在将创作与热门资讯深度融合。检索开关为条件性触发，时效词或长尾词可高概率激活。在**编辑精准可控**方面，新版本提升了生成图像与输入文本的契合度。**智能逻辑推理**功能则涵盖复杂逻辑推演、物理世界知识与垂类行业知识。模型不仅能对花朵按品种分类构图，还能理解物理规律和参考 `CAD` 设计图生成真实建筑。

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/20260209/20260209082129_6a016a2537.png)

```
https://bytedance.larkoffice.com/wiki/TQyJwfRFiiVMUdkFY84cCb7CncI
```

---

## Meta AI 已在官网测试最新模型 Avocado `#5`
> 有用户发现，**Meta AI** 更新了其网站与移动应用，正在测试包括新模型 `Avocado` 在内的多项功能与集成。

Meta AI 更新了其网站与移动应用，并正在测试包括新模型 `Avocado` 在内的多项功能与集成。Meta 的内部测试模式包括 `Avocado`、`Avocado Thinking` 和代表 browser agent 的 `Sierra` 模型。`Avocado` 是继 `Llama 4` 之后 Meta 准备发布的模型的代号。另一个内部概念为“Big Brain”，其思路是让多个模型 agents 并行运行，并从中选择最佳输出作为最终响应。

目前，`Avocado`、voice agent、`browser agent`（`Sierra`）和“Tasks”等模型和功能尚在测试或开发中，尚未完成最终部署。

![](https://cdn.jsdelivr.net/gh/imjuya/picx-images-hosting@master/imagehub/aidaily/95db0821-8e25-40a2-8645-bfffdc0798d4/7b128843-d679-4af6-826d-5c2ab7936564/m001.gif)

```
https://www.testingcatalog.com/meta-ai-redies-avacado-manus-agent-and-openclaw-integration/
```

---

**提示**：内容由AI辅助创作，可能存在**幻觉**和**错误**。

作者`橘鸦Juya`，视频版在同名**哔哩哔哩**。欢迎**点赞、关注、分享**。
