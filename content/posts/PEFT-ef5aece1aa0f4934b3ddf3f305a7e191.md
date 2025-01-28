---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667QPYAMI7%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250128T222142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHYaCXVzLXdlc3QtMiJHMEUCIDc5XohVlRQjOMTw9K1izwozUepFJtdfV1E8gociqpLuAiEAtR5\
  faY2YlGS98Gy%2FoiS43%2FA7YWdZm7fUciXYC3z3MpUq%2FwMIfxAAGgw2Mzc0MjMxODM4MDUiDI\
  hZR0ckn43rRAWxzircAxqKuhF2MTU4utJLKbc2XuQfbAp%2Fg%2B7qVs3gXNeeP1BhThhrT2oDX3F\
  z5LIuScfsPyUofgqTxz%2FnF7NlFCk86mPc2OrZGTu4D0ne6M0Xr6x0kLE%2BuPUE5I5ldFXFyY9Z\
  7NdPAORitCSQfZEetp4SDSeHYe1TZI6Csuu3%2BX24FT%2F3xAyRJT4QK58A9jp4OtZbl0YvFT1To\
  HVfQGd4120UcCQ90quCJZZ4PaqZi40xdX%2BU%2Fk5n1iemsK837wy%2BXqURADPJAJNMPas9Bvw%\
  2FhgLwJkgbdihbXJU7YvmmxC64c38CLGVLl9eHu5dYeIs529TBCZhXiaq0HR5pn9cuyE31ACTgJm%\
  2FbbOiAQ12q7RyMVTRY%2BBYScUAUsjg3zEADJsH276SY9noP%2BSWJAco3KxMi5zEDZQMVr7MXYB\
  wu5wSBEaCUa6Ks73rV0b0zi%2FzfXl6EoJTHd%2BfN%2FvsuhyRxV6PJRXIg8utLwAWOrWHxCD9H4\
  w%2F7ggsxcAgEJhGnPeIYP0jbo1SvaDiDauiWBKZQA%2FXI9%2FWvwZcKnIe6%2FxpmkjperIi38K\
  %2BBkNCbq6DHeW%2F3PxalaTpdgTcmwbaoRgvoDnKLz%2FYztxGEFzTOt8srjKi0SGPRKyz2CG67z\
  6Z6DLP0MOaV5bwGOqUBZIKlQaMdCud4%2F07cR1arcSEvu6noUtUKNGA3lBJ8pV4GThgtsSE4iyMU\
  nyTfewx7Xn9DFjJUa63DgEyhbaZ4It043NGawQOMTnx0CPvouKVJ66DR8mmRxL7xsbOILFP70pkYS\
  Bfo4PU3l%2B%2BuK0zCnCb2%2Be%2BPc5pL3KmmERGO3D9cVTQJ2pvN5KuQYnLOT8y%2B7IjQ0p2W\
  Rxol9aG3O%2FkC573mvIo7&X-Amz-Signature=c52da141b0d499d014244294994feb58be8977\
  9c557b08c2679ceea31ee5902b&X-Amz-SignedHeaders=host&x-id=GetObject"
series:
  - "Tech"
authors:
  - "陈猛"
tags:
  - "大模型微调"
categories:
  - "LLM"
summary: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的LLM。"
NOTION_METADATA:
  object: "page"
  id: "ef5aece1-aa0f-4934-b3dd-f3f305a7e191"
  created_time: "2023-08-25T08:02:00.000Z"
  last_edited_time: "2023-08-25T08:32:00.000Z"
  created_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  last_edited_by:
    object: "user"
    id: "cc08a802-cdc1-4040-b261-957206a41bd5"
  cover:
    type: "file"
    file:
      url: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-a\
        e1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-Amz-A\
        lgorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-C\
        redential=ASIAZI2LB4666AK4T6IX%2F20250128%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250128T222027Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIFk0FBZg1%2BWPMZ7cevBSIA%2BoWfE\
        23xj%2BxQ2eSH8pLTWmAiEA%2F9fKlXeIDx0smi77a9uWL4K8y2%2BTi3ykvozhWZjqVV4q\
        %2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDIdXTlhoBPFvXXxMdircA0cjzoGcra%2FwxdecrgP\
        VRhrjbncb7015i1R%2F2XrTYPTfY0Rhjr6k5fDvBy%2BSG2T04a17N0g9m6h4VipFb2hTAb\
        3AtaO4PnFUdnvgKxj9loU8%2F3dhvYj8%2Fp1i3bSnQFfdqr%2FHI6n5KD1pmiMRGnTvKAo\
        CGXg7mmVPQQpRvUWpelBvl62X%2B94ISpIHvfea3wuWJaHYUv8zcrkX%2FVOv%2B%2FQfmH\
        WAD8qUeDdAL%2BNmKx9YqwANLC7FYMGp5os7NKFmOhuPy%2F8w43prB46JujM3jXz3BFjJJ\
        xqk5EFsKdt5Hg7PNijo31OGAJhGDsq5Ne4F4jWCM70Td73OP2%2FBuQX09%2BC3gEtFzNmO\
        O6HMrH1vr7sJyeeaHSV56YDtlnTbaQ%2FRu99c%2BstreIbss1QZzbNJeLm%2FXrZ1jXF9P\
        2tRfHsmQSzLa8sYRGutnquyLEfnOM%2FpiQI1t4UkAudTPaZYgSwg%2BL08l5z91j40gPiO\
        4ldNlBO0fiNd2Uc0UsnsyqeBa%2FpMBrhw8xu34t5qAKTP7DWJNyMxXdVUbmp8ehm%2Bmoy\
        1EU2%2FqcTFswYAksQfvetByzbuTZR36zdVXRNZ76pVTRFyUADkpE9YGRTo6e6VZxENPtk7\
        17TJurrPuSyrLeqXZm0vMOWV5bwGOqUBQ%2FJUiBbfha%2BksYtItGGZJtQ6rgbhW1a2nX4\
        4h%2BNH6Jk%2BkGuLJxFxjKCVrfm4arUF004bpNQBIH4A7amOuxq7RLKGC%2B9ER6zQ1OAA\
        JF2kbJj4dn9DfqLh1fe0Bp7ErPdZiAdhnFDPFEsLldTf6e2VlW3uoP%2FoPdcRFpVvsNedV\
        dbEFvHYsDLLV%2F78uSk01EekWCVKslYk8MaUnLLJ%2Bpaqx91gThME&X-Amz-Signature\
        =5dce05630ecf3bc2ecb7d04e296f7826f590e077d68e47fc81a1834e459baa92&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-28T23:20:27.608Z"
  icon: null
  parent:
    type: "database_id"
    database_id: "8d6a6f9d-5a2c-433b-a560-b744eab9db1a"
  archived: false
  in_trash: false
  properties:
    series:
      id: "B%3C%3FS"
      type: "multi_select"
      multi_select:
        - id: "f6345faf-6e79-413e-847a-3fb764a61e06"
          name: "Tech"
          color: "green"
    draft:
      id: "JiWU"
      type: "checkbox"
      checkbox: false
    Created time:
      id: "UBQ%7B"
      type: "created_time"
      created_time: "2023-08-25T08:02:00.000Z"
    authors:
      id: "bK%3B%5B"
      type: "people"
      people:
        - object: "user"
          id: "cc08a802-cdc1-4040-b261-957206a41bd5"
          name: "陈猛"
          avatar_url: "https://s3-us-west-2.amazonaws.com/public.notion-static.com/775523\
            b7-57cf-4c98-8ad8-8777d898666f/notion-avatar-1678713535269.png"
          type: "person"
          person:
            email: "346521888@qq.com"
    custom-front-matter:
      id: "c~kA"
      type: "rich_text"
      rich_text: []
    tags:
      id: "jw%7CC"
      type: "multi_select"
      multi_select:
        - id: "1446ca36-aed8-4a52-ac2f-405939fd3168"
          name: "大模型微调"
          color: "red"
    categories:
      id: "nbY%3F"
      type: "multi_select"
      multi_select:
        - id: "e417d9a1-8454-498a-b9de-502d57e26681"
          name: "LLM"
          color: "gray"
    summary:
      id: "x%3AlD"
      type: "rich_text"
      rich_text:
        - type: "text"
          text:
            content: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的LLM\
              。"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "对于大模型微调起来不仅需要很多计算资源（GPU），还需要大量的训练时间，PEFT通过高效微调模型，使得我们可以使用单卡去训练比较大的\
            LLM。"
          href: null
    Date:
      id: "zYLY"
      type: "date"
      date: null
    Name:
      id: "title"
      type: "title"
      title:
        - type: "text"
          text:
            content: "PEFT"
            link: null
          annotations:
            bold: false
            italic: false
            strikethrough: false
            underline: false
            code: false
            color: "default"
          plain_text: "PEFT"
          href: null
  url: "https://www.notion.so/PEFT-ef5aece1aa0f4934b3ddf3f305a7e191"
  public_url: "https://kevinchen1994.notion.site/PEFT-ef5aece1aa0f4934b3ddf3f305a7e191"
UPDATE_TIME: "2025-01-28T22:21:47.567Z"
EXPIRY_TIME: "2025-01-28T23:21:40.071Z"

---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.2/dist/katex.min.css" integrity="sha384-bYdxxUwYipFNohQlHt0bjN/LCpueqWz13HufFEV1SUatKs1cm4L6fFgCi1jT643X" crossorigin="anonymous">


## Fine-Tuning


Pre-training后使用有标注的数据对模型进行微调，需要大量的有监督数据，预训练与微调之间存在gap，效果提升不够明显。代表模型EMLO、BERT、GPT1


## Prompt-Tuning系列


通过添加模版的方式，避免引入额外的参数，从而让语言模型能够在Zero-Shot，或者Few-Shot的场景下达到理想的效果。代表模型GPT3


### Discrete Prompt（离散Prompt）


离散Prompt是指将离散字符与在原始文本进拼接，且在训练中保持不变，这里保持不变是指这些离散字符的词向量（Word Embedding）在训练过程中保持不变。通常情况下，离散法不需要引入任何参数。


### Continuous Prompt（连续Prompt）


连续Prompt是指让模型在训练过程中，根据具体的上下文语义和任务目标对模板参数进行连续可调。因为在离散训练中，模板无法参与模型的训练环境，容易陷入局部最优，而如果将模版变为可以训练的参数，那么不同的样本可以在连续的向量空间中寻找合适的伪标记，同时也可以增强模型的泛化能力。因此，连续法需要引入少量的参数让模型在训练时进行参数更新。


### **Prefix Tuning （2021.01）**


_论文题目：Prefix-Tuning: Optimizing Continuous Prompts for Generation_


_论文地址：_[_https://arxiv.org/pdf/2101.00190.pdf _](https://arxiv.org/pdf/2101.00190.pdf)


_论文源码：_[_https://github.com/XiangLi1999/PrefixTuning_](https://github.com/XiangLi1999/PrefixTuning)


背景：1. 人工设计的离散Prompt模板成本高，并且模型对模板特别敏感，多一个字少一个字都可能造成较大的变化，并且效果可能不是最优的；2. 传统微调需要针对每一个下游任务单独保存一份模型的权重，训练成本太高。


基于此，Prefix Tuning提出了固定LM参数，为LM提供可训练的、特定任务的前缀，这样就可以针对不同的任务使用不同的前缀，并且也可以复用LM的参数了。其次，使用连续的Prompt，相比离散的Prompt效果更好。在实际使用中挑选任务相关的prefix与transformer进行组装，实现热插拔。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=097c2fe6fcb83ba8339f952fce5f0b1771a20ea01139ae16ae726f4ccd340a94&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=b176684214c85d7dd5f2911776429f2442012dd08b8cba42939f4b747847e892&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=3bbf619e120e827e42eda98a88573e66382cb57242e43de46822562b7722ddaf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=3d02d1c462ace035e09a4923371694ad0c0bef9d4e164009bb5db01cd343c070&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=1b6c9ad4d7f5f118f8664aadf6f8bb85ff1316222bcfcb73d3ea4cdf7773ace5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46675HU4ULH%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIDZfRJVsF5G9cujd2kCM1Yzn05ioG16vPMO2WhmFGiHHAiEAr1asVHocj0UPXBQcSREvJRyNzBNShMs17P6wWhNjDCIq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDOwAnJAcQn6ZdrINrircA9gXQgPEj7yRRMwOG9ljQpmU4kbElaNqBXP%2FcsZi1CAkX77pyV7jCdP%2B9kzaoG2h6HL2mWcQ43bngS%2FyP25aYGYWWVKhhZPiQ4rI6tkgiRz18JgScN26KudWp5Y7SMNdPtENJ5i3ZzmE%2F9KLAWB2DoFfTae0u%2BHs5NGgKghDV%2FQgsxq4PZmYhocUxp6fwMkTuVg75ywHH448HhG3W0B3Q%2Bi75WBcXLU%2Fb7R5T4cX1OA%2BVYnBudYFIcVQ76SMeWa8NkkWjZsQiKbknz5StXZErE0zt85rKLtSfMxRmjtLQ9K1uY%2BoeP6Siw0Ka6p01Uehb1Ip%2BgR8YENmhWTQHtyfbcoNeTFDpDFSiTQ1yI0wR7pOK3TLYpo77mtE4XszU91wdqSKZ2LeR3dlxLuvE1%2BzwC3VrxJGVWcXLgfliH3xQSTjvVS4%2FHsYkT05W4ihbdCJfj1Iwms%2BAqxRqpO4EK37IaRoxqB8XMRxtkiLdFx7bAALLCOCWCtUL9El0KA7ksGyZo2Nndl2jCmdQwvgnkq9C2NjZtYXAmlEjNfLFSptoRJFIhiNRvSoZklVbSLc6ZGAR%2FhX6WGAIUG0m5vr1mJ6PDW9Tfi1%2FIKexFCSWV%2FG2EiWuLedZEyuSmBx%2FK4nMNiV5bwGOqUBhjd23bSyrQJ1xWThRs0JDGIhmWXp6w2m4IJiyJHEZtwJQgcBaGJrqIrLGzP38Jhno%2Bqjqh0uN6oz0jbl67JYhXEH78FFjOgcZ6hNeljXihJ%2B51mCmx0SgYcQd3QopNrufT7VQqYV5TCbbgaQyLSFovIuIvgRJkWaZDpPHWNjSPN8G9GFZzWMlLZfIl78bSez1jjWmLjl1Er8uIOdeTAu%2BkQtM8sC&X-Amz-Signature=89740cbf523420abce9751585deaba7ec70bb7a3a5b64f72a222c79ceb151116&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VGQGHVGF%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222142Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIQDXzLC28gN2jBad%2FfHH87IxC2aXGUc7NJRfeBlfn0dikQIgeChsACvW9H1njwdHxaF0Iet7njqequebA5L%2FZR33tYQq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDLlsSTvMlQ9txhTFWCrcA6N%2F7tr4Hf8%2FmIIn4QtW6FCrvT67axoPnfULVfYf9DqhTVLV%2B%2B7W7%2Fs3VEWfy3i3YruVb%2FbLPGkEK326KmcbDuFCRAW8X9lk%2FgqUbDKuiX5aCcwMK2jZ7ajmsAUQqRxe%2FFUSnb3prvCRqKIAmF%2BJFz%2F3q5ewH61Pp0UAJb4FGa%2FV7ohh86%2B0YDv7kIRMtQaj7PIptQ21grqkIvyThthU8DdpHnedkHS0T%2BZieuPDXBQK9vAWMGOwSpl%2FrPZTuy1%2Bklm5cgTLUt6wWq%2F90sY2ZdAVVyYdLJJCtCE0wTW0%2F9ok1vWM8tFwugEC7D6pe9KJILdymB3kqvxhvqraTj9K35iKhVJ74FPQOwwEiWdoqOB%2F6PWxnLGybJgad9RzRMIr7eeN9GzT6SeR3%2BvYTdy6LKjCGTTBr%2BTuBPldknbwt5ASKpFS7BpHLKkSm0RO%2B5t9VLzeynNRivpbfW8LnjaZxvY6HnB%2BFEaNuB6EwKv0zFSS6YY4V7O9NJwZemYWLyEODxEMJ6xXe0WTWgQwoaSgWbgbQQDVVq20E2b9XngSyCPFt%2Fni%2BpsOd6WlmLRnUUjKdBGM2l5cUTLtYIhOFQV5qpB%2BOcJnCGoJrjsfUNJU%2FwhOyLl9gvQWyJ7O6oFZMLiW5bwGOqUBcYaoWkXye%2F4LwvkgoQjz7MzPfZ0oChjF2yfpeu5a%2B%2BL4L0zGMzx5qm2bfd78WSHu%2B8t%2BrWa5MGxoZ0FnjWaynJwm2fEv2uRnPBxEPt%2BCwf%2B9%2BOXEsMD2uvIRGEEoJWl9Ormst87F6i0CxJ%2B7kJHq%2FB7gYPR1ZhMskVm%2FdMZQ2%2FQd7Kpz%2F9yUurMaaDb28RsA2c5nOorVQ7G9%2FuwVCNvjgUD58bGU&X-Amz-Signature=24f7cf4e669e0c7a774ed0c6cd090eaa335aba52a075dee797ef08344cb1a697&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=49b9c63aec3343b4df7830f7cc84f857c10ba053c0edea64aed81fd2ff33717e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=f24c08aaf903d18351088c4fda2eec0753bfeec4b4a8e7d527b1e49b73ee765d&X-Amz-SignedHeaders=host&x-id=GetObject)


实验结果证明AdaLoRA效果好于LoRA，但是没好太多，个人认为方法是好方法，提升有限。


### QLoRA（2023.05）


论文题目：QLoRA: Efficient Finetuning of Quantized LLMs


论文源码：[https://github.com/artidoro/qlora](https://github.com/artidoro/qlora)


论文地址：[https://arxiv.org/pdf/2305.14314.pdf](https://arxiv.org/pdf/2305.14314.pdf)


背景：量化方法可以显著减少LLM的内存占用，然而只限于在推理阶段，基于此，QLoRA提出了在不降低性能的前提下，微调量化为4bit的LLM。


具体操作为将预训练模型量化到4bit，并且添加可以学习的低秩适配器权重，这些权重通过量化的反向传播梯度进行优化。QLoRA 有一种低精度存储数据类型（4 bit），还有一种计算数据类型（BFloat16）。实际上，这意味着无论何时使用 QLoRA 权重张量，我们都会将张量反量化为 BFloat16，然后执行 16 位矩阵乘法。QLoRA提出的一些新技术来实现了上述操作，具体为：

- **4bit NormalFloat(NF4)**：对于正态分布权重而言，一种信息理论上最优的新数据类型，该数据类型对正态分布数据产生比 4 bit整数和 4bit 浮点数更好的实证结果。
- **双量化**：对第一次量化后的那些常量再进行一次量化，减少存储空间。
- **分页优化器**：使用NVIDIA统一内存特性，该特性可以在在GPU偶尔OOM的情况下，进行CPU和GPU之间自动分页到分页的传输，以实现无错误的 GPU 处理。该功能的工作方式类似于 CPU 内存和磁盘之间的常规内存分页。使用此功能为优化器状态（Optimizer）分配分页内存，然后在 GPU 内存不足时将其自动卸载到 CPU 内存，并在优化器更新步骤需要时将其加载回 GPU 内存。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLJV4URC%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T222140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHYaCXVzLXdlc3QtMiJHMEUCIAx9NxCZXzUHrTriNqRwWiJFk9gF1qDqOubTGYJRAZFrAiEAuL%2FXNInBU6jmdBMSdtjmg50KIdXLvIt%2F8cVGeJhNUPsq%2FwMIfhAAGgw2Mzc0MjMxODM4MDUiDJokLluEOpBcLMO7HSrcA09uh38NkrdmT0CbEpizGDbcSZvV%2BgCqaR5Mve2q0uKOS%2F0ELAfAEMAsMIiauoOT9r0TBbggd7%2BogXEWbmZRm1acI3XcW4AtxBF%2BZsIkszwqWspePoSFOLulDc%2BU5F5CnPZDyg9L3iqe71eMNDfV%2FflRtnE%2F%2FjEIXCFLxn%2FQ8l%2F0YabEvWkZ9mdPS9mSfNu%2FPheaitn96REgQ9d%2BH%2B9qM45%2FD7IYfkavDAENY7V1f2iuqTPElqDKBQ0O3Ezx3uDF%2B3wLeIE%2BY9cbVGLVGfO75Pwrt6dKzwlvyfDdjojx1%2Bxhm2C6CfvAKh2tvV%2BxMBBN8IndMnj7GClkAzg4py%2F4LhGmkTCC0YMD07QKPKvM21qHLiQn4RNlWt09sUGCyvEq5bdBHJ%2BopIoC8bSWmGvxr0%2Bn%2F65btSM7DyROkbAlebPI6IZHHgGppVsFysZ%2FQ9fsVu4Nbc80ERWHWod5VUCeqhqmX1G1HXC86ITLM5zKQhxRDKbBO1MfHTNMnivFmq22csLcfOgVseW642fmgLdaR9ProtMKR0rPywysR6sZLY%2BLSOI%2F%2FTu9p3O2swdl8rddC0dbx3sOEODITONHXH9AwyRctH6O%2FjWd3fwgv17yAaRtPlsi9%2B7YQ8DJ6P2rMMuV5bwGOqUBTYYBMFkQwr5F%2FDIdyVHMlNDSD%2BmW%2BYcKdqzgcLM6yGLWXCDRYUMZUizMHMp9YuH71TgY1CSScD1mBe2GTb7%2FpSWohA0dbkHtu%2Btrp%2FMLeB4%2FTf2P%2BzpqMD%2F%2FQhezU9irCEjZQ6rt08NI2wT6e78xPglr2w7vnagz1Nk9yfT6bI4EteZvg6ncsHOEnhYYKyYcvgAhmLcnMj%2B8aqcZ6C76Hohkzxd8&X-Amz-Signature=011dce929497b1de75c907a8d8e02886280c236837c844c9a0c151c60545d065&X-Amz-SignedHeaders=host&x-id=GetObject)


## 总结


> 📌 P-tuning v1与Prompt tuning是比较类似的方法


P-tuning v1和Prompt tuning都是在**输入层**添加连续的虚拟token；


P-tuning v1插入虚拟token的位置可以是前缀，也可以插入到中间；


Prompt tuning是针对不同的任务设定不同的prompt，将prompt与特定任务的数据进行拼接作为输入；


P-tuning v1将prompt使用MLP+LSTM的方式对prompt进行embedding处理，这里起到的作用的加速训练，Prompt tuning不需要使用MLP进行向量化；


> 📌 P-tuning v2与Prefix tuning是比较类似的方法


Prefix tuning和P-tuning v2都是在**transformer的每一层**添加虚拟token；


Prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务;


Prefix tuning可以应用在decoder-only模型，也可以应用在encoder-decoder模型，P-tuning v2只能应用在decoder-only模型；


> 📌 LoRA系列


LoRA通过引入低秩的旁路网络（增量矩阵）可获得与全量微调相当的性能，且极大降低训练显存依赖（将GPT-3可调参数减少10000倍，GPU内存需求减少3倍）；LoRA需要预先设置相同增量矩阵的秩，忽略了不同权重参数的重要性差异，AdaLora对这一问题进行改进，通过引入SVD技术，达到对参数矩阵自适应分配秩的效果，从而获得了相较Lora更优的性能；与AdaLoRA思路不同，QLoRA在LoRA基础上，对大模型基座进行4-bit量化，同时引入双量化和分页优化，极大减少训练显存依赖，且效果与16-bit全量微调相当，QLoRA将65B Llama模型的显存需求从大于780G降低到小于48G，AdaLoRA和QLoRA可看作是对LoRA不同的两种改进方式。


## 参考文献


[https://mp.weixin.qq.com/s/E_0-skD3__w5jLGEJlDpoA](https://mp.weixin.qq.com/s/E_0-skD3__w5jLGEJlDpoA)


[https://mp.weixin.qq.com/s/webUB5j8nNQsthTFQNiqpA](https://mp.weixin.qq.com/s/webUB5j8nNQsthTFQNiqpA)


[https://mp.weixin.qq.com/s/8A7aLiknSDCBfMuUKg4eiw](https://mp.weixin.qq.com/s/8A7aLiknSDCBfMuUKg4eiw)


[https://zhuanlan.zhihu.com/p/636215898](https://zhuanlan.zhihu.com/p/636215898)

