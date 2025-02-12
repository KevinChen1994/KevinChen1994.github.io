---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SQHI5KEU%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T222253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCTsH9BglswlC9kwdY\
  4TDUYVA7Z%2FqDQx7WSV5gELQLLzgIgPtJjISih156qhhj4rTHAmdqG%2BQwmwMcPJvfxydCLD18q\
  iAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGTvRcPgepI5QdM\
  50ircA889qU5FWFRTUVf%2FbrPKdCe%2FfFuGA1bD2AI899BRMQIObk54FDhdK3NVFWEVk20SJneb\
  LCskjDogDtubIgJcoNzY%2Fba%2BBqT6Jz0PIdWLEKMH4ulWK6a8QWE%2BOb%2B97lhrg6sOiECrm\
  %2BaTka%2FX2W%2FlxkWE7s9GJEbc0O7mJqRjcALB2vc9F6mHlx%2BF7Pvv2QJKpNQCQCsPKTYSGB\
  bMmI2pdeodvt%2BBs5dexsTPCS8V0eFTkWXLlb1n9AjfMQDoPcd18zokFARUT0GAv6gjKiBTBX6Ac\
  uhONTxGFQO8%2B1Mavkic0OTWPXFbUWTkgff5e6WlFYkcgbXDiNy2JcwVBs7tSNsVZnsy2XEnlmqy\
  9%2B26HPxc6AGs3K3bsyBUlLzpvRzq2wgJ5Gydn%2FezElz2ZUvSBbub%2B0LyY6B57EFQjlpbZ9L\
  YurMOz4dx%2FeGAL%2BB8RZB0FuJNDFmkkPAMP9nWrMIaTouVP0g1rZxhFSrBrr2zeUp1%2F0vkaT\
  gxVjC7Gnm2nL6IwxK0iZ62jRsK6DzRwebbxEi7uH31DOiZWTFKCYqqKsr0SIAI3SvDj4OmRjGzUYU\
  8vwmn%2FQ1SDHQgmX7JSP5%2BRu7veGobYeYgKMIhTQ7Y7BA2D7Sl5ojr2t%2FLV1YsMOeptL0GOq\
  UBvcVAkLSOw78%2BT5eyUs44SGg8crdQyAm%2FYnCjuz23vYt%2FFd8iVTPDFVoIZdxk%2BvoaUrC\
  rOZTKoTOvjfHfakVnWXqv4YY4eY7160db%2BQyXl7qKAWI6S%2Bi%2Ftbso0FNDPbA3oQMoTOUne0\
  RhWcHc9PFLyNddCrY2rc6NLoyfYOUcWNzTofe4DMCmIJKfX7S4%2BYmpzIN6fUrq4aspkkEiZYxGG\
  fgfDurx&X-Amz-Signature=21f922ecb80f52df4f63627211caa354a7e949f7c88dde5315154\
  6d0b4487a6e&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WNYLTMSR%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T222110Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCtr9Ex1qJPy%2BMyEdmEQOQW2X7GGIFOxv7o0BhsPs7KJAIgIa1Edb8xQ2s0DGwNmRPQ\
        6WgSTtPCdQMnlm7fOjJtBtkqiAQI9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDOMJHzv5zmjNXatM1SrcA6WiCFpqnQO5Y48JaohNBlT7t7%2BVSmHvbA\
        uxCyQzrIYNhlRmQteI%2BWkXsKpxiS8Gjci%2Fbi1JsW7Z1gzhiD1rKWpR35eNL2g3y5T8O\
        %2Faj5ZldLAeD148o4JaocidO9TjpgH0%2FZuIUIIb%2FsjrXnS34sJBQEQNSurk4CAoApg\
        5Tn3F6dlfa1%2BpY9MGP1KoMlU13Hs9xvYHG8neJuOmyfGM06EWU96Tg8LiGsfNFog6PB7t\
        %2FFKL5zU2H0RSA6mzb%2BJExDpqlVTU5uSNloB20Ul9cQSfO%2FJCvegnleml66EZ9NTDC\
        gZ%2FlEGomwjlTIwyu6hVuc3q00rImhG1Cpzjzg12vKBbup3muatnd6LFnsbiJNNANsasbD\
        yZmIiDftYSmSyujsH9xjbtMY5T8yAF4zTYL%2BI7iLil8uMqOtci0MRclaX3pkdsoXfcVQV\
        O0YDIC%2BNmVqy36g8EYtiy6lr%2FfQNdGnxwyFei8kj4VZgntRVHlTBCzqqMJQht1ro5fe\
        laRBySrwF6qAIdxCa%2FA%2BM%2FggdIiJiZ%2B3LosOSsdLQofaw3S4DfUkc73aOvVvYNx\
        Jh87ScFEYrUjNmE9AC4xVEXS9ixLih5zFeGKi2AJE2s4kgvykSCjxJVvSt%2F6qTECnGAEM\
        MKptL0GOqUBhqt1Ja4BVAorJIr%2BZsEFLahSOhMZvWrGrEyUULiaVFDPv0yYZtle99dkzq\
        BS9aCpsoKAI0wNDL5JTdi4g5ueCcNChRwUtgl442tZ57uQaxHdy1WuzHWyxR5iA0MmYEPpK\
        n21%2Fq6OrZyNOE13YIk07aLVQrFVhIl2p2L23ZXmXiS7q52cn%2BmRNnTt%2B9JBG5ug5c\
        0%2FmBKH5TBKbsR%2BTVu6Xh1ewDcZ&X-Amz-Signature=602d30a3e6247a71e5114e6e\
        d088eaa0ce5abcc351783f1bb8bbcf26f103d94d&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-12T23:21:10.707Z"
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
UPDATE_TIME: "2025-02-12T22:23:03.252Z"
EXPIRY_TIME: "2025-02-12T23:22:50.938Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=3faed1050ceb3248ee7c319ce5439c41971d20d737bfdb73aae2a5e83e005608&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=7a3e58348978db4e8f86fe7c02f151394f59cb4ce0879f8b48ba2fdf22234dfc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=0b14bb17a1755f2cb277b9225ea3d239512bf139360e198e7a7c8bfdf5626698&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=a8682699254e22fc4a2a3cad97458c1a1d5299cdf80c6209cda04d2d7295195f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=f596d84066202ed20da77fc46f85be9c90b73d88a268aeba25e5115a371d95eb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664YZLRO4S%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu8gyC%2BiJ%2FO9efzVeLXT0lAVCfnIRFpmLEW32qLApp5QIhAMeI%2FW%2FPpCQ3M%2BB8l7jdqGbpvxT7Oh%2BtRt6JBkSezDIyKogECPf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzIS87CAgEQSvrMj%2Boq3ANIUPVDn%2FNsNIZRFTMvxDipO8onqmlY4IiwdBDnTmoa4h9TkamwsWBpy4SOrFbFh8d6Cq7zIpWm9ZziNNN8emkOFgx5HGJ%2BnOl4Dzp4Qbsvs9NJe5L7xIxQKKsF7SgcTkaXyY9YSeoMaJiBQXgn0FYtUh1mUkIRiyUFFHxr6lHKTJRGs0%2BPIVFm%2F6tWg3LqTW%2F34rrgAHo%2FVs0sNXhdOgKw28BbkwGxr%2F7aTx3aQF8KGvIZDn6a0p%2F%2BGLTTX38UYl61hlr3LjJPZZ0TG36ZW6g1HkEcxjs0GGf6oUAn1CtxvID5TZsybw7FF0SeOb9EA7AatY4VlWnXoOczRs6OJ9jEXel5V0DGY0RjVGN9WRAZEWMMzJlNysSkpwoYKMyqQnBhcCT6G574UfWXaR0ddOwq%2BBqzV%2Bt25sZo36ba6fqF%2FZ62e1zMKhDDwEZ9P0MbYdfYyqqztrCmiB929XAaT1o9T%2BputTqxmbB9wxSSh4%2FyniPsXPLUFNW1QVejh8IVR70i6GkQVETj9WGbZwHgtZ53GilTr9wPQ78kuCgJ8IGOyhC%2BFyg8LU38BhA0%2BOo8hHqUOk7L9UXixZtZYnkpgREYGGRVNTQivODZSRk77uZWv80Ybf0YoLtP%2F%2BhBDjDjqLS9BjqkAXZ5KKm6VrXKSVJadq7IM2XTdCjUuS8Z0OJfX94a2zXi%2BhTZTjon%2BKnnCYAN4dhFdm0rmebohmT52GJwTb5YmA9DxeLgwpnkKD6eGy9kYnRcBmKLAWGELz4J9OF5K%2B%2BfRboK5091jtky0LeDL6d6%2FGLjpR0HAqHBSE%2FDOTxXx41e5a%2F7ZfBK%2FBUym7ZZQsOLkTCDPqGZQMGN30PKvV7mKIMWSRh5&X-Amz-Signature=913e35e18bdb5ce7856a0d32cf5ef1d1222d6d475f3e4522d2aaa7ea39f0d989&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SLYUMKMM%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEJlgWHa5sY5c6U%2BDVQ%2F0eaJZxVE6bQhctDq3Z6aZaKhAiBgeI98MUHmKr5xNEncbWf%2BRGPE%2Bxe%2BHJck%2BvhfJO072CqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMR1xNQWPu3kMsDOo8KtwDLUN4HSThkI4WxRZESl3JTQit87nWzo6SOz53GOx2yjDuXGhugXYNqs1qSGpnxo7Yp2SGWlcaR%2BN9UErw7%2FeTCcrZYJc23Ny%2FwpNMORVGpHMQfsYp6h4ATldPIt6CTRmcwEZ%2BCjAbc4Lvq34zwsZ1f00XlncwH%2BWi8hEEqWW6JrKZWoENOew04iDvlWDio%2Bk%2FTMCDzHoWp9jDLNoPkDiP1i5C2W%2B2enp%2B6CqVq8Mf040pyybOCspgrMxaHIotGFv8U%2BgHo8do%2By8H7JjmRl7fBXIubmuCun7dz0ZSdOkjR6KuwOBU5Z3BG93WhiESRtyuIB%2F%2B%2BLv7aO3Kfz%2BK1dMWz1dEXkxp%2Fi17Kfl2XTvYZxFUiM1UhCDmXxfPRJ2iuSOUHdekp518vWmIv7rPTETAgGze%2BkGp6g%2BW0xJItwdvWVUtk5CT6yhD6Gpt84TQvza7QnpEmcCJ5iCK8%2B3BJkhv94rkM9mNrna1kcT8TV2pXkACUyhTq5tncwl3qugh6ffPxKCNdLf9jmjYP%2FEQ01StDl1Jk1mhbFXltGD92AKD%2BhXoEvaSDhcCO4IoTusupxogtyMibcoNVYptgyTYaYWHUqm1M5R8AI7ngmkfyElb1i8zYdZg8Nw%2Fl9Te3n4wx6i0vQY6pgHzfRAyJq8Oq%2BrG2T8f8uInDhmgQxLjd2RoXrP4hZ1P9rzFj5acVZirKS1MbfJT%2FNzE2pY6ivhtdJf9QE4afgJcWcBUv58WH0bmJEwdYTp2MJlAxmOiq3A7EYg2wNItrug4Mceub9JOjgesQ9hsV2SGHAo6lIYp%2BIxyezgjmjYIPklczfOKjAZReix5IjKzOabaghufdTc4j3UVqcS4qzRuAaB9qaAM&X-Amz-Signature=975f96c19fcf15016e8cf5364ed4621ecaa6e1ae0f6e7125648d2abc0165f353&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=ed6c3f411af72bd182f848bdbbe1da01f832e25a65adab48c12b730c45828834&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=c9a8f1b212a83120dff6f9f3604733740a95be809da3540a3a4746886a69c501&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YTLKGN7U%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T222251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFpSg1J4x%2F%2FTqnCFfyI3wTcfuI2dlhLw%2FXsZhL3BFq3TAiAEeD0L4bEmOqT%2BDPHdK0UXrS2vs8dQsC3Q87LHQ4CENiqIBAj3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQcPsA5qucUvFQ8C3KtwDObJag5%2BUpfxJUuYhJtf7RzML5qC2jaU3k6BCenp0cL3M%2B15amOJcVUi%2Fg2GFJuZGkovgEtNqr60GuvxmnrDtdAVz98bmD9FSghRcDReMxSMj%2BW6zm13qM1GITqfnX5fdWlDU4mt5mp4VqB3Owfokjq135%2F9y3C7tBnZ%2BJd8YmGzHbGUPrD97NoluGwIaWBIHcVYSJKvbiGNpb41%2FJPlwAANoGjdz2hs6Wkp%2F%2B26reNhMubKspes4ZeaOCMVWD637qjCOcN0CD76NWuoc0oYUOVTMqA6QlRunFpNvC%2BcfKQzE4e3hPWxECRQfjthhgbS%2Fy9D47%2Bpa7ih3dzCb%2BiIV9eYCT6wckMAZ9df0VjnYvp2ncmb1Tzl2D7c1FmlztVhuJT3AQ7BPMK%2BH2xC6kGipTweot7PPS1IM7zwBuPXPMFFNSXVmX6JitLC3LgV9WWzcHlYv3LI96NkJlUtr5kvaUCKzusyGn%2BAWctEi5i%2FtfucaqbKgIelE%2FtrH1Y1aIo7sVnEVODBh76y5a7uj2xMd0BNeIt683u6M6246BDOmhVxCoIctzEUTkE2eUgRI9tiHYZaHwSByS28Tqd6VEiOfgN1x1RxtENtxIoM0%2Fz3Ee36dDnXgDM3uztz4XdMwxqi0vQY6pgEOnZbfvCqAU0DJLzK5cjYzaWDh2WCcdlt%2Fk%2ByrZHNL2V7JLHY8ryRKTgV1m4s6ZPdDG%2BQO3nl5FUFWOV4H4UcTGhy6jtydG5groACqXuZyBiAC5UNDlfWFzXAtdRYgyvLtF6y%2BqtrbYsDB6KssTPA%2FxH7qF1FZKKvXEyoVYFmD2J%2BU0JDcfTX4U0Wf8tNFKf202OseYWhHpS6sG6a9YyLQmA8Pm4jD&X-Amz-Signature=1848ae735c7f5fea329f1805cc8e75f8ef052ae79b91660de42928420d4b8365&X-Amz-SignedHeaders=host&x-id=GetObject)


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

