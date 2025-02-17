---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664F5JADKH%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T133015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEE0aCXVzLXdlc3QtMiJHMEUCIQD3gmIFcYxk6IPcfhSO9SohP0wY%2FDbqWsiRBB5e7m2kPAIgG\
  XTuS4R%2Bh6xttQ3XBKn4zCLUODGYF32%2BHOn4B75BAm0q%2FwMIdhAAGgw2Mzc0MjMxODM4MDUi\
  DDqArcFzohZfiQHqtircAxvI%2F26VpuZM%2FhmxFbtqB%2FOeHhqmAOwGAVNPdT6kHdy2bMAwG%2\
  Bkr3wxqn%2BppHmVuvw8LZCkWpQCOT%2FPP1pRduXYTCjU7XJWTIk5z21dvMXoQnazUWGxOAgCI5A\
  2lG6NkDFezWQTh7YSUdF0CTZx5r8cu3xMrJsBABPONJ9NdC%2B0rLyQDwjrpMfxADsoe%2BM%2FZr\
  BsMVCub8mHFKA8Ngi%2Bt5tTguf5piX3haDfS0HAnfaoyKlX5eT1g3hCVdsB1vk5kfdyj6QNblLxd\
  fgHjXWHsLAQQjS0fUaL7XivR%2FyHWsZPHistSHNAswmGzDryQRxr1pL9xuGiieF0RQKZdh9hWDiZ\
  Dbzhw4VK%2BA%2BkSi%2Bk37bMJBr32stIHR2Wc8DYQ5aO4SmoNtnVFc0gyYshBa83EEmzSWtrd%2\
  Fa7iMmtk1O7gG7PILKTH3twr00eF91bmLo8xECigIuoV2esCyeiPPTv9r2HWtKjz2F48oncXXSyU5\
  8NwJlB%2FfWuVY7AeNcdo5iA%2FIj8rr9AWh3I7X0LaZiWMK195PcDyWjNLoBQIAWYXVpyOlW2U2d\
  TWh%2BHiry1w6ccZFzITDFN8PHptaa4kM%2BeNbdsUPhWehO80kAtwng57MNxM4dKNYIKiOuUV9bY\
  GMI3bzL0GOqUBJBHeqSB76%2BjCMuvHI3Cdtv6hU7mzznfgIbf6k1MpoVkdKExcpGZV3%2B9Uk8Z5\
  2HGHud4C7DmVomKRWNvjL1xdPNXlH5XHkK95AdLGAUB90snd6LoDyJIPL3Yc0Kz9tMl7dy%2FQfHf\
  HgT1iDS%2BgIhCTb1TpBg5zBTZcvYPsqhyBREkBqc6zAL3ZndDzx18Er6hRVoesYvzg9Moc9Hb2zC\
  WSIS%2BucQdS&X-Amz-Signature=856578ce9bf6c728e90bf0a882965c4c41c83a1e3825efc0\
  3807461aabc9a185&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466V6NKXZWD%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T132854Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJIMEYCIQCld%2F7owzv7TEO0kDDDnfzJFrov6\
        CUxa4SbaMomnETN%2FgIhAJh31w5%2BXzrW1KrxurUmOc79M7cvrYHgEEQbIL9d4NklKv8D\
        CHYQABoMNjM3NDIzMTgzODA1IgzYRoJMwVUTdkuv3bQq3AMKUNUCWWxF7Q3ulCK7%2Bkzbs\
        ccBs4ps4Bm2OmC0XqZV3W%2FdPj26ufiuJhlf1A6t9qIONLWnsJq%2B9uXWwXmp7ZjEAh9f\
        DBFlJnnyFcU8ffQ0SFs11Z0eJKnN%2BYBChMcBmmhhs0slUFH%2BtITEhk8lgRU6Xof%2Fg\
        dvJGZqFn1h9PAQSl269qQf4S0zgfmGDjudIsXj1zkpLyPwKvi5IA7NYf3xCUg7PchtUs27W\
        YlOiN9vY8pbojVh0GHX7ny%2B3DLfkO4gnzmMgYMCgC4dA8z69JjctofkoY6Mu7viWmgyTg\
        IhSrl3s9d9wzuodgzT%2B2vnHTEe9TiH64kBOJNiWdLNA48aaFXVxf7KNwqekfRqcnbHOtq\
        JEfBZT9z4mKNUnV3y6LLxyPS28WKcHzjohH%2B7EJfvv0BskS5TcodJr5QdpZnHuOPNwzvg\
        MbUS5rhAVcefVeKcHX2br%2BNSyXjCP3vKL2Td6MgRleTiZzzbuHtA2a2PpQns2fv4AxjVT\
        xJGfjGguNvGqEyp%2FyuyYBz%2BTIcB9tUIgocVyC%2FIpUGP4VpkIcdvXP0n10PGCud486\
        uc1OTEFvdG55PstCDpAy01WDaKitUDobQx4oYRQi6LevnZ4K9ZCBIjkK0RWloLI7W0XiDCZ\
        3My9BjqkAeiF8L4VT5U1C1DY9kIsKuEcc9Wur1SGtHbeERlLmtQ386DQOmxwabeZN1qKYNU\
        Ag2G3cEd9SUogII5vJqIUsx37SG3R7OhucxNvDnrLu%2FkMw01irDveppvAaLYELtJJcADQ\
        0MU30oox3pIbrLiWikqK6GyEJQvSuGo5vYB00OQbRnRlTfYOSQgNZZqmw0Xamgw4wSwpFmW\
        HeJIOV9506fBA7MT%2B&X-Amz-Signature=011297e95da1f9bf14fa5e657878c9a5902\
        84c99b020d0e01c584b5990efd9be&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T14:28:54.635Z"
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
UPDATE_TIME: "2025-02-17T13:30:24.084Z"
EXPIRY_TIME: "2025-02-17T14:30:12.100Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=dc76f191a44c4890a95247508deee6be92c4948f1a2b28ba9cb9b0371cb3b8e0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=6a2a5e9f81ded50aee55e7baeb877e9a3f1a3220170cb777cc14df57cbe50470&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=7a33836886d1f0c156932fa2826da066757612d705683060eb0a5fe53549ab57&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=bf8c3662dce7b44e59f2b21bf48d923a676ac4447e6ac93a953e08b924496969&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=a63d53963b6b859ba0e2cf75c7d69c694f64ebada2c41ed823a6153940779678&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WMGRXGVQ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133014Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJHMEUCIQC4R0xrL3BK73pIJf67UWewNumxH7rTxCuzHyVEHs6sVwIgfLPYXC%2F6CaX9hDtO8AwXooFrbdE6nDadcSwbULtCdl4q%2FwMIdhAAGgw2Mzc0MjMxODM4MDUiDNuUdSG4DIC2%2BMqxvSrcA7nDre7J8Vj%2Bf7kL3rf1dbviRyqFAS95mh8NI9I5QTFXbU00zJSsXHJPin5u58OzkgMQUAFpP%2B6oBNw%2FksSnNimTE4L%2BuLQVEy3RA%2BV1Xt0sRcEykmuKEKjEWDdrcOP%2FhMo%2FFrm3p0JnD5ncNOujRKrN65unY%2FAGyry3y5djxOw0tNGLlhP1pApnXAhVK5%2BMbNk4D1SYPm0DJ4wtudibactSRdW%2Fu%2BWQUH8cGUu9HEfRKFHvyJ%2BooPquhgjFLErSsDBOaZj2VFYQLjVqSkWy1j7hQ3iVRrrH26oYbDyu355UU%2FCdjShFMo1LihXnaRfUslYnThSnvETd2ZXo0xieAHMvVcN08by35%2F7P70JbRXr7lSt4qYjTXpyD%2FnCzxlnj18iw0LZJYD4ltsPzPdv%2Bxah%2FMNY5DUIGLkhPvOx1scnDuCx%2BF50OywCVpj3RqXCHsSzlNy2oYlHSmT%2B1sUfnGmoADRP0Sp2KYef9KW4jdabIOv%2FxiU7eCshltXfG1JgQPMwx3BzZ1hP9K%2FZNBcIqyqrlGpLFZpUWh%2B6yz6euX6Afn4yDQ9vgdogVD9WkdYHbw%2F3vEtUuJiJi67%2BVAl5qPpRsWmpzCxObuVMeog7w94Hj%2B5lX3j7xLrCrpELNMK7bzL0GOqUBV1LKSB1WTc9jLMzEvBaetJRYVaUznKlAIwcT3%2BSuxd7rHngmMVnU%2BOti0IR%2BrJvl0Zn97%2Bz2SaT7bhi9aRKI7DKcTu07T8O5BewQ0fFaQuWMGdf%2FWVp4KVFJOzfbV2RVA3OSCgUv7xYZYfvM%2FHNjAWXpVuDGEwklkdp8vtLHZNqWP4eZfDdXiAFh9phazpTHOkEGo3Zc5NH%2B%2BDecOw18ru670Xrx&X-Amz-Signature=50d8ff6f44555c5e7e40f89177bd1c85c5df76fe17af1d521ae9c8cd8318e251&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46645P4XO34%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJHMEUCIQDAdjmTXdmkIqHhZ39iWjsBBSAF7ID%2B%2Bs0%2BQTTs3Jox4AIgIv3TOR%2Bx5on9QrTqZ7pVWRKOAMVTQv9%2FA%2Bqrccovybsq%2FwMIdhAAGgw2Mzc0MjMxODM4MDUiDPNci50KolJQkv%2Fo8CrcA9Nk0R3vA5xneLzmMBT%2F1zm%2FGreH1pIlYcJ98eJHiJcywh4t98EIAplmlHy%2BXXF3FQSPQz1vowurdG4roFyNrSS679Qp1YwgQStRPsqdst6eqGtZ7GLdTS0axvdE1Rq6i8jqVogddbhFhsVGclrMavW1r4Ss84GZr%2FF8HyXANNAjlaB7mtkcolxM3MSDrHzOfoEPEFUHGRs31r3xLDfG%2BbCAlh3T3%2B5cioLaKUWPp8%2B%2BXAVsVV%2BZl3xWxQT%2FBsSjNtlCYNtSJYIi8yUNIIzQvxIK%2BFCwZVpYhkAUmduhx8bFebFwT2qkFmz6yIS2jlDElyRsJgib3i38xiS8hLDmE%2Bt%2BQHKSAR0g2%2FQv2OIFFFx%2B5l2lO2SBzfNxRevl4sONwDKngU%2FkRmtuZGcKg7ZUSEFb52z8ZSWCGf6CVifOwJ681DfgThbmCUsals9MdjmLda6OhfjyhCO%2BVPjpr4Q8Wbq938zzHk63ZK9mph0xnKFc8awqAH8AsNZRyifxPBTM542%2FP3JSz705rL6x1W0CzVmBEN9KpELTTYyYxjGYLi2TikQ3O3tHDMXcQ6oAlZjP511U14F3TGTEa12ZLJ4VogLEQ3NgmJwHEsAm5AVuO6KZDAym6csRoPq4DxWNMPXbzL0GOqUBOAZun1SPr8ZDXtkBoNH2HjlmqxwfavGTL6Nd3hVU4coNaHeoKcDdGCRECRa2ZnagMdDNMgaCqPs5cfSjzFQPTBhrJU2lyKeW78XWLwcHRP3yc7nf8AK6nOeLvLRWHnM7dlqxTEMB%2FKLgZzidekpO5H%2FtwOVogNKeFfaUhKOYSTqo5WyAXleaDb%2Fs%2F7Pq2FUvfoRR%2Box%2BYryeK%2BhVcoOfQhv5eqLK&X-Amz-Signature=05c3a6428d94ab0a24ffda8a3842b4e0fe5aa235eba7afcfdd162550dfe8e507&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=eb1270bc02eb1064058b3ad25110b81c2f8d812856cc30ba17099aca08b1dc32&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=298bab90005b45bd93f159f5bd7597e7494516e9e7cc55314e70f418b1367561&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667B2EVCJJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T133013Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE0aCXVzLXdlc3QtMiJGMEQCIBmbYPUUgUojVc%2FCV5oziDg7SfGWlgjwb%2Be09lT8t6DYAiAlFu9l0criZyCw1YjXMB8mBLj5oUnqQ2f%2BHhBK1pu%2Bjir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMJ0lB9Kq8KUX%2B61AXKtwDttyf%2F2NHlnQhj2TRHDdsKd9D%2B394LJkz%2BCrBuT5ZP2OJCGtexaoUcaLe9nv5SACPrO1xJxisdBz89hMU0UNOW3hEzl%2BmlQta91tHuvGJ1lJAgj78RtGTNLiMDf0TBM9AeHNdIlXvMgiho5xiLQAXpF0Ng%2F%2F7lULscBXH1%2BP96dxvBjEd56b9yUXBUqEanSY2eAKP%2B3RpTl%2F7rTUXI%2BM9%2BKiZf7SvZrnmVg1e4j3gsGfT9kWq9iGKNFLqTJzpUr8n2lutJtH4kukdOg8TkntyeY3O%2BHQwG2sZXF%2Fbg30PGZsLyEj%2FasIN4rVNx%2BfM4u2J6Dgpcb2R8v8fC8jjO3XbAku2Z3v%2FBFRNRaxD4aw0jhlWp9xZl8iK0kUNpn7wB%2FzD6qZfM96lz4PjvWhbUmdbgVNsFC914%2FKGu%2BfgRQyeoyuLhBAPd0LhwN%2FJ01wGwmX1Ran2ac2TaPuoxPWFQdfKPrwk6T45fttXOUy%2FAdRAk1FoKbEWHHcnem%2Bl4TIeb84lkotgMu7Xxf44%2FPB7TWhMS7IAPs4Dj5WWMp8S%2F8oCZaTRtwmlyurCZI1Ihkhmdmk%2BB4614akUMKTlppE4Z7HvzLNe8G0fLF43fir4s1tVBfKxeiiPHEhhy5ClDYEwmtvMvQY6pgG1zhgb%2BYTwwTSh5X4ie7VQna8fh649JbjSvN7KG9s6ncpxO9thZJDLreuaOVeOrek4NlvbWpT3Jd3Bl%2Bpsu6%2FJUpHJlQUgiV84pjr3b4Igb%2BzhC8jHs2QfSaRrLGeAluoGiuNid37mOQtWOzmiIn9Vgn%2FviInKAIIIhG4%2BGgmEnLjUpbjS%2FIsCyAiu4TEzo5gRQU2L%2FHBWm9eOZQM0B9peprlwtyVw&X-Amz-Signature=2592590f32a234f971ec25359afd184e79b3b634de23f57e7638cd48dcaf6b53&X-Amz-SignedHeaders=host&x-id=GetObject)


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

