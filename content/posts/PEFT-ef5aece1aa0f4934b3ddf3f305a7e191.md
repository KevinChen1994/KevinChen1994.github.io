---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46672WTPIZK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T025310Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFDyYALWsLEADbFZQZp\
  G%2BTMWAs%2BSl%2F2qy0F4IWawUM%2FDAiEA64MsGjFTxabbXgEHfuUaxBqx21vytU5Cv1HiY%2B\
  PTfw8qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDH7nORg\
  63Id6BJfxaCrcA7LK7O4gbMQZjRjPYpJx%2FygP08z5L3tywcrUYrmMgX1%2FQEd32ZU1OGzLxJPT\
  9kPU2hS8e%2Fo6IPel6dc2EsnAUfbkh98p2ffH8ZbDwSpO8bSiior0ueth5RHXWtnetN6sEJ4SXQW\
  Zuzrgz0thCUyMG2S28V4VYkE4k0BwiZqglwAs6FZAJVUJb8HfvqiZY2Zb%2BaFOCiBhxHvTRO7FGd\
  UNU2Jbt3SDBU7iP43E82u8byOgZ3hfDWnPYUUe%2F%2BA19pH2im%2BczzA1cO%2ByR%2Fkz%2B6e\
  TR7MRwkk3dR0p9T8L9wj2Wg0mzm9wRfrgsTtv0e2Y3sz61z%2FIRDwRzUmlzZ4B0c%2BZlpIB9g5t\
  de6nLqwyC%2BnJVf4CLS6BAexQOxbvMl%2FtXAw6cx71usJfVhhnQAgwwhkQjW3iMZK94WwInWFns\
  hCognnzYiABg5tSzTjwKU7GPsys%2FlC3%2FxoBXkpMpdmMN2LOlv6Vu7fOUVIG4iM5veL60Gtm%2\
  FXE7X6VmSm7wcoQ8QjLkOMDeNVicbZ8mLdsrduJnei60abqlZ96Gc5thdPEMtHnD4r9GAGDhxA4AL\
  4T8BWrqYmPPHe5gu2f2V19KZMYAvzA%2BVdHfnS7RLQfCFssSNxrKHdsWseEeNcv076VsMJ2Ytb0G\
  OqUB4d4bykNPG4u0qE1bYwpe2N4T2cF0w7HTBsKTU7fRDPy3DZgBKWd%2F%2BU23pLw4vYm4yefcy\
  Rg5XGm5mgm8QzHSLvzBfbMUkrs9s2slco17kS02gnasXccQ%2BBkAwcMM4beTJmQPo6IrOEWvyf3R\
  gmpLJ46afyers4iRkC7Y9Ot3vREjp7JD%2BfjeCNfVQ%2F5yoLmjfKkptkc%2B2hrQg%2BQ0rqr8g\
  LpyV2u1&X-Amz-Signature=e0c0b11a48b0c1d54b72186a972a9ccc20a77e265880e6958773c\
  655bc2ad1af&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665FBO4AYQ%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T025151Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQC1C5mNrldlTMh6RasOE2e8merWj1kGbF7zlvD5prXjVgIgEJCZxfM7sBWZcUL2UFo%2B\
        ZAmezBWJcQJtPSLIS7wvyQYqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDDuZ2RPL3HrBCkmaQircA2qmEMMIBZB2j5zFTAE05QEVObenOR0puy\
        LfxdbeO%2FReZoEJjsdd7qY3MzFwy5JMAG4HV04NCWXRNBxfaQIXYOJUGTAnYkx11VY92V0\
        3OqaL%2BgyE63DZ%2BshPLUteGP8lkykNBtNy0S29IuAA51KjbrMskT3OJKz83qjAGqqm%2\
        BgMpYg59cksDFR%2FI0OVJPBRwSO8FVP6u7wMqDMzXHOmrq4yqjnezeqviJFQ8loq4aFwLN\
        p9YIFygE4YEYiZXccS6zuod9zAzF8wQtivlcz4MJKtnA%2FIH89hXIPGYEiFqBJaUeaJRKj\
        iLHpLJR0b8KUDv%2FoCIX3u9OaF48KgM2UYIhJ1wllAxyoyRUe6uoqKk2jVcH7mQCXIOghL\
        GXzCcOjCd516jo5KguhF0Wr%2FZ%2BOLoXmkg5GuyfQa3Aem6wgKmmGX%2BHjPIt%2F4c7J\
        C58EzT6t05vweYudzyPZGrKkWPkibAcmZK2xMiXbXE%2B%2Flga0J%2FzSHeQK0FqLh0fEF\
        Puy5c8pfd9qHQwf%2BrWGjf7kwx67O3esrVszYhRtv3ScyfZNbv1XuFNs27s6xyBr631LT2\
        qY7ieXfb8tdIXQceC9FE5Z%2F1L10YdUOCg0XiM%2F7d8BAsn5qWwik4R58ZcDIrZrxbMPS\
        Ytb0GOqUBXzUEV7ijAMLHeH%2Bz0%2B5nH8E%2BTf2R1zU65S%2BwMSn%2BWJe%2BeuqvdP\
        NbU7aHocGL1As6HKoPd7j6N5gsTtYs7Bdpjf%2Bn3j2Hr9c63MOCBwIHtQzJn7fdBJKJrYr\
        DNkLQgtiCTb0g5p065ZJVYdfBfyP0pxTQ%2FyG8pl5J0GTx75izGPmnBXcTlmEuSO0BHXWT\
        1X%2F3zUErn5a70e0lJexvcY3d1twpg5T4&X-Amz-Signature=c89131b30a73d20c527b\
        f907c8f79fa0226774d86b8fdfd9f297245f30a78b16&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-02-13T03:51:50.996Z"
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
UPDATE_TIME: "2025-02-13T02:53:16.727Z"
EXPIRY_TIME: "2025-02-13T03:53:04.981Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=784a32748a05c2e522034a56800f8eaa4f826361bbcb0b789e55bf54a5546e69&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=040fae934f865886bffa31905c7676b3e3b45a75dadb13cfb42862827acc0f75&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=7c44ffb03fd49d3918e814cb83f702632dea735443ee978455a198b02f4d2b64&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=60f2d5563eddf656e53d6bb5a6bfb9370062a26a6d118e68a30b6de8dbdc3364&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=b94d29e5d52677292ab7f501c67ab022f1f97300271e32df3cdaf54bbbe733f4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VH6H4VDQ%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025309Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDwToXLn%2BisC3cWM7zbKYd0oO7Lj0VwXsbW9ovYL%2B%2BW1AiAovphZ4dUQXHrlSVxAYzoqD2Shl7tdF0N3b4Cdq%2BEqpCqIBAj7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMqqQBDiiKeeUmnHVZKtwDDNE145qH%2Fejs2BDm7t0OdWrEwzl5OA5REaJfpS%2BljaZIwcx%2FVn7MnOXumMkkESndw1iAJiHvqrwR88Q1d9z2dgpq%2BtzstJTpF07bECMId8%2Bc0CRy58s1%2FZU7V2vPjiA4%2FGCj%2BQy2OKjYwV4QxnZNVB0L7cLIN%2FG8L8s6QklzPhbwVa8ah03Bq8%2F29wJitXmOEHSt4g0RpxVXQCaW6CrOCpWtEN7CWZWSezTu%2Fg%2B8rYzTEPjDydcxuY4nCQzy3uY7lVJ8EMYT6qZ0XvPFC5q%2F5GDPxwjGvI83kWBmJBUPNCe4Q5uct80yM2nA7wrjp9QhY3III6M4D3tfA4W2vumHP3ZziQZstOcG%2Bk7vLGoYFRPN%2BBaX2HBWRoSDer9rFKmxHnD2sqmbZW4aN3ZD9i1KK2qM32tvRSgBSuj0TjjNEz3pyDuKf%2BD08pTaiWJYV3aVsfqVPv6gbktzu%2B52CLORtpYqz2XwGTJrmDpTf%2FszPasIRCBg0J1xFppxYF1C2ifD7wedIqdZUNkWIU5HLGJqCuecR2Ft5NwOGU8oZrhD3ieYd9gVQzRdG285TwDPTVvNF06Av4qt1M%2FAAoJqO%2FK%2FSUlgvs4Xh5L1NZGXzpW8zkPr7bWynbaFDlZMc6Ew95i1vQY6pgFTR%2FUFUrueSQr4uOYx9kh6ZgUaX4JqWu3%2B5HqXzs7tTYSgFFUkGB9INCPV8YHIeTc74cZcG5cT1No%2B%2BRw1kHRNmw3tdbnSFGR4rE5fbQttS%2BEF2p37N1tnLkJW4cFU5sg6fPKXV8XucnsoqdWMllcaooZQLH8p6d30q3XvTiHKiwFVFt%2BTUTalPKqi2I%2FPTDK08ySo3gpvIaGKYscShY2%2BK2blDkKO&X-Amz-Signature=db2cc4e2222c221b043827065d128d202d4ce81eb7b6dfac42f8ae2fda83f3ee&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662YRKP4IU%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025309Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDURkLBjS2CfxZrVxa70QiI2qq%2Fw%2BrFXlFj3IRXbF97sQIhALH8CXH2vqDn2AJV6dgrd43gMgTgs%2BTb5ZtEevhV9lLxKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyZrZMEr90XXZK157Iq3AO9PqzQypBhiMGSClOaAsE2Tz1ET6Bd%2B5QgZIrsjY3DTRhONPHyXlkzGjz6tafEu7T7MlPsMJSbbMga8Qe7BxHirwGvdD7HM%2F5WpqvvR5cpmp3KtMGK17G2yZ5%2FfAV6Sg%2FRWH2f1y8Ig3RBAgbt6U1047YikMB04cv8vDAnkvGRetNQ%2F5CCBE6pq6IlSq0hqh6S4lJtoFvE%2BQP4NqAfpvXzqOyuX2dAlVC2Hzr7KE4D8u8E3Waxkhux3N%2FNBCOikkYXcjTzq1h9lIMMx3jzCk8gWJA3OKgzNtflfEem8ddP4KwbDAQZ0uqbJ8cTwbZmUMTEzr%2F0z6OrGYP5PIGPU4AgEh5ZSxkVMxQbCwV8qKrMDlxEMVTz%2BTE14Aay5%2BZsnMCpkN6rz2GATNJAfdYqjK4xp5a5%2B7rd539wLyT5u0MsUwk07V50RyjD7GRmqv8WCF4099B7s4U6YNqzL3cydf4zKttjRMayr3sUQEhj7EHaVlPy%2BggDC6LzW4xZHeiGXTYov2HIaeFRufitAfGuH5ge%2F%2FHFS99Cjs4EaOfLZJRUAxKHm0NeCTkLhOKW6UIrRv%2BdCRBzGtQUv5WZdK3Fz5sbrTly9Le7OFZumzDUjw0z8XtEpDRFHHn0rMWe%2BzD%2FmLW9BjqkAczlHrA3aWjk5E5EUmo1p3ZLSf%2B27pySPgUU9pSV82jfCBlJ1ECxk5wozqfHxKSGZcCE5QofxD4NmJ%2BiY93oL82etooYeEhrGF6OCcc1iZ4XaNoSb746vIDxnCM4wdUaQGM58uA2DPHgXj9eNIxyHmlhvROp2ZkX6XmBLbvb%2FGH9snfLZgvVjiyylcpM6rvnFzY4Hrnq7VRXhIyZLQTk6VVErQ0s&X-Amz-Signature=15254314205200e0d47f02f32e6e7b9b81ef91ddbbd1ca6ed0e17786f88ff153&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=38c0e579b3a549a318ea5cd288832a4ea107c9f2d59fd1aae082a2bc9b8fba6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=e830ef80041d18bd21653e85acff54631ef30470660765c07b054210bff3fe48&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667BOWD5OK%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T025308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID9ScMlfMcpVMsuwLtpKbYuA8wjtcykX90rmccsGnqLsAiEA67GpM%2FmJPK7y1sJVEBrFBge%2Bh0Fbm1ATu0mlFZO2gDUqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPDq%2BWuiLTJZJNvAwSrcAzAEw1oTPsHaow52IGP0vaMH%2BlFp09Wa5RbVAkNzFpTSQT1OJPZO2q1yP32F80pt4zAooVhYS2Dl5x2J0jFiIyx8x9NIoz8iPavUOY6X4yOG44Mosz2WDWDD%2BTDr9j3dHgG9DkHCNZhH%2BXd8aVJeo9PXOndMCscTZ9M6ODWvDuuCiMQ8J0nqi8pRG99ggR6CcQNCyTdZHRcs2lKiwN4WZ%2FgBY0f%2FORfxY7gFWbSQN2GxRg%2BgjXiQ1TDISqhgNgcZvGa0JMFZL6egdD0YO0f5JBNe472BW%2B8Imu0lFu12FJ2R2chHvLk6DExBTsxfX%2F%2FpcZRlUYtvs90yPAeJFWhzB08l7jP2XDphpcEoppKOraBE0I%2B1Fg7UUuziChyE1lhnJs0O4mgzGkIyVxw5XQ1XWj8vBx%2FHZLajeLHjcVGToTuQbMbIUEQdAOWX5pEejvkCMkafe9Rb1Vz%2BWMcs0SXzkK6ALsm0AfPFb%2FEo%2BEIiYDoVAKDTu%2FrsFOftCU51wZ7GJkqdy%2Bk8cDCNuZlf5Q5xPfFdQwi3%2BZSwba5mZA2vzrAWmgjhhz9SkXtLT76uK8hA6DhCugOZ8wA4TK4ZKQYX3S3T7N59%2BN8mrypJorIrFAVgwPZqB6YT0gjnKByVMOiYtb0GOqUBneqyEL%2FhSsAr1hz7nYtE0AGYs%2FHRCDG1Uu%2FeEu0QmboUC1AEiQ2D1OqJ%2B2uLE0p5Tj4lgckz70qfHlaV8kymOXtB6HtztaKwPEOidAUhn%2F94EjBRX5lpmHbwFMeE5K4P9jc4otYsP15U2MQsRtqKRMfi35TYEyHbOSRBK8Z0PDmLPB0SPrJ%2B%2FueqSdYbcBMYgXMz7NCTAwSk7si%2FdwIAdOQTmgQ1&X-Amz-Signature=b1d3863de6487708dc4ec208d695361ce8518b5f2d44a5d94172e4f68a052546&X-Amz-SignedHeaders=host&x-id=GetObject)


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

