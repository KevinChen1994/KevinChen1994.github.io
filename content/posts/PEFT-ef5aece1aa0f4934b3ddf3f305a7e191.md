---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YCB5X64D%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T183158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGIaCXVzLXdlc3QtMiJGMEQCIFgvrENUKHlWCAxlLHWEAgPSTGb534PXeDcR2iZs9ImBAiAik6v\
  SsAHnP0iffE9nyB6p%2BP8hYRR4abVD6ZiIP%2FY08yr%2FAwh7EAAaDDYzNzQyMzE4MzgwNSIMZ5\
  7lzhd5W8ooroc1KtwDEDHZtSjKTv75Y%2BIvULrsAdv6xAgqKr3CdHSFwoRUSB2E9yB71jjblXXtb\
  %2BuJ44Ga6KFBw3R05Qk%2BHGSrLAmIBgZkWegJBwbXl0FzEDpbAAdirJMPEWRp2MhPi3GBJD730H\
  uNvzUvfRHn4fhE3uFO1L8So4I4jU71enIrA6WxTM%2FDCgYd1VKML%2FcAljI8zGgkdqjm2mv%2F3\
  X2E%2BwZZCdFu61rbEZff3ix1DyQ7MK7%2Bq%2ByPEjr28%2FcP7Xzut6lhnfQHFbfD1vkkeUdj5u\
  XUWICZ3VItamwG9FImRnNl01XYRyxuzjN9MBZetjxEmsKoHd2c3vBxgOvPBt0WAp8l%2FyzhxA1l%\
  2FcqdP5bcDjMPJhOzvKaCaPj%2Bkra3MK6%2FTETUQfR3rKnb%2B8ff%2BOnTiVpiPkvJ%2FWrz8Z\
  uJHUFqkkH3aIwZ%2FvXRbHi2Kjq9jDxWtk4ErH9z9OMyaVBcBNdslJ9a5uJMaqmFVD49I8nXWnSuO\
  4im5uwwT7uwvy6ESH7%2F2ElGcEo9GojwVyUo5w4s6gDXnR1ykLQ%2FWGcb9ggcrzdfijp2UY61yJ\
  sPMAALmpnZWvblnEk76bf91T%2FhI9bSzKhRy%2F%2BGdL%2B7cq%2B0B8kBqYbrM6nG3va7mL9Jp\
  DguRLdR3OowsJqZvQY6pgGiD3N93pMbNo%2BhrQ2rKhrWQ2zCemJk4iMZsYXcNQv4P3n0imtG76%2\
  Fjei3TsDczqlTozus13ajRo5jF%2FOm%2BRAEg5QZXmH7B2lOuCzuBrFuHZ0MHNZQ%2BxoHJDfDZk\
  JefRA7NJz3B6NuUsutaIfHo2GCSyrUHcvMjSDkA%2BKd5Dok9h34ZUhr8yQ1xiIcsCZmxcJAb3s6k\
  qtW1ouQQYxRY7xcixs3iAm0q&X-Amz-Signature=615ee5218bf6393fe92287b44bf5f6d56625\
  2f2dd470f0351b9feb17c20650b8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Y5GIESQH%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T183030Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQC3um7mPyCfA2cSDeiQEy2duCZR82I\
        iUQp9GyKh8mBWYQIhAPrK%2Fm5KF3uNcBX4xMlQimgaT3gUcbooN2wttBN69PcWKv8DCHsQ\
        ABoMNjM3NDIzMTgzODA1IgzDa5TB5nOE5MLpSrQq3AOGlqvzv9sIVbYjzyG6kG15lwiaPI1\
        NnszT7iqg2zzVMCwvRki%2Bh6lrkAhTybH6rCQ3TjgsbEL6U3RoLf%2FIOu9n7hBfdjVomv\
        lhqqlrVy%2FKhXnmD3dD1miTPSfCInKafbwLAP5VktlejpDDr2%2By2UYM7vbZOnV5qf7w6\
        d4%2F2lOcmh86YmuYLsrSiUcZsJoWTqdKtQ8xZzqQ0kqx7XYzTttE%2FjMyvS40XoE6l%2F\
        JhTsLXcDW%2BlNRXmxfmpH5OC%2Fpur0PWv5sqWqZgffesaU8SifXSxUFCb%2BVP9MfFnpy\
        wKLfTgfxvo31fUwF0qK9qm6UTdS0kgOdoE4wXnUEM1My7O9%2BV1RcIBiAIPW65V2COoKue\
        FtyQMIai0rGGO0pC9umuAHkaKlfYmtl3Qt%2BwxP0ojOgXOwQD2KLgJcG9%2BUXzSsUZ5%2\
        Fivu5kfvnRxXsETs1WYWJlA5bxqcVILNz1gevVmsoUNolw6qVYW5pGVA9rTF6R3MzOvLRIw\
        2E8D3HnXqgPLqE0LjNPA78%2F6Lv%2BwmFHmgbkMo2eJnsiawspeKuskoRznwd4ERwW38bI\
        a6%2Bdq3GYnRtq0Sbo%2BmY0PSH1o2H2XDRmLSysXpV%2BsQwNPsM6mWAw0CgJgnVruCeqO\
        VyvJqjCSm5m9BjqkAZMERGxgql65%2FTe88Q8DNcTZSf%2FqwfTU%2F6ca5eDGYJxLiiAh%\
        2F0nLv8d1XEedMmAdUvGh%2FO6XDkIoOZJxBW0YkcTdrk67ItnQe2XQTMZ4K0k4HjCRryGX\
        NEGscJjmh%2FtOgutOR6TbwENSCmxcA19MnecdlPZ4iHIRdUAXDYVbnXUanuGP7uzxNDQu2\
        XVDYR0yeHOJfeBvqln3PNSQUbeQ0ljUTZR6&X-Amz-Signature=f9ca0ddc3df36259995\
        fb597afa4d10bff7c60dab2795dd888fc3140af9882fb&X-Amz-SignedHeaders=host&\
        x-id=GetObject"
      expiry_time: "2025-02-07T19:30:30.846Z"
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
UPDATE_TIME: "2025-02-07T18:32:04.963Z"
EXPIRY_TIME: "2025-02-07T19:31:56.864Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=959bf70f76f8e29c32dd62f4a579ffcd287964749de3fc119c0a068ae33f87ed&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=8b698b4d6e9a0fbdb37b606618b942311919206642c7037e37fe9b5f717743cc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=7f20783f9e1f82c6eb52f00a3d1d2cb61e3294a8e02ce5e77a135a1d61835b30&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=f48493dbc542f9c44816bc4bb593eb4f72b101f034b66fe1f5a5b744be050504&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=03e9e4738edfdec0dc61acb086d448e8cb253dd7f4d1a0a346ab526cf5907e34&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RH7W4HJH%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQCzNBvkVj2m80%2FMZ%2FWJnxxgJ6u102v9BbQBt4AZjfGdwgIhANxxuXPafYF2hDUur1OyDzM7E2OhsYHpF9v0ifdnM%2B1FKv8DCHsQABoMNjM3NDIzMTgzODA1IgwGmNE5lFVUPVXu7Q4q3AOT7vp6TwQrqDBAKliJmCCouIhJfw9KYNu4UohexDxQLheoOlyN2mpqw5yOouSb1Fi5mXjbyL087C3qFWbQ9lgy1S%2FksSpHiI32R%2FALdA1v%2B8gq0JLc7JIGpvZ8nWiGZIBTr19ngWpPGLeP9Sph1vONRrwrsmUYhdecqmdNNQbjeaasQiEECyWoDAbZWmyLfkh8GfRr5Hrf8FvFUdyJsNkRkz62DPk5dSXdFp63i5KA0tMTCE2O5PUwtp9XFjZCw9%2FG12gt01UKuxF6wOju30I6C1A36ywWDM8j4Z1M4mUFYUp83trWC%2BramH1%2FgGYlBeAlvLKn4qGcQN67nGASBzO5B3N2JPzQl7d1O0%2FETzAAMSZQXuJHQLE9j6VWEX5sp2zh%2FGrensRzWktl6%2BRcrmV2MtFwSyvmNcLtBTwFez1vG2gwXyBUOfVuSKb5BrhcZWCi63u2oubnOgs3y7PMPXDDxJ7iSdD5gHJ2dt1XH15pbjZB6TQ0Llog6DkdFV9IEe5lXtLwW6b0d4dXHTg64BHSCw6Q%2FpZAApB%2BHiqUuqdZ1CVWYNGCQN7RGfA0u6GX%2FW5AIexVGV%2B8ps7OGwfFD64McedfiTuxY84duik%2FyS%2FXNHzz66bfdz%2FwS2LfPDC4mpm9BjqkAfb6iTgjHDPQoY7bjlwMy5O1gaF5SUa914KTJ5DXhvYSCxbMxJqnxu5iQxC8%2FK5ur%2FsHP6APn95N3ePHRpqSE3A9N%2F53bsWrmeZTDuSaA5vwyv3QtLSwuthjHbBIqujYOEEP%2FXqJVT6ZIJjpPh5utWFo1CZyBNoji1eBrkTVwDiJRUnBqcLrfLkjB62Jx1%2BHifo6sbtpiQDaLgt1OmIOQ1WotktA&X-Amz-Signature=25ab235cfa2cf81dd691e7ffef55651541d451da7ef3fa5a44d35cbc87215ad7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QFFKKC3H%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQCqmnl%2FTI3uanaj2h68FlM6J8NGpswg7WQUu9CBOFqeAwIhAIRmBj6cHQEJHv76k8YTR%2F1j7g%2B3jHWu2gR6%2B4iSdIyOKv8DCHsQABoMNjM3NDIzMTgzODA1IgxHojZ%2FEpZqnzlAuC8q3APbOHcMj3%2BBbzApfF82q6zqzhOskiU7i71EZ5WoJcP63JCiJuFym1aMKQcjxH%2F1JvsihvrgkEU78xNN1q8Kmx%2BuVIsRFuSFlST%2FZjnxkBxX4fVPO%2FO2pF%2B0W5t81x9Hhspg3dqmFyyTqNitFIkLlA4ZM6R3MkID6gma3fgOXXsbWFotpj5gJjbYuWnm0DEJXNVFh74SMka%2F4DFHcZRN66X4CPdjJQdvWR6hdGPD1y7SR07KJqz1qqOkwgMaiRtQbOc0mJn6rghzOkgyXdkMw7p8QueciA86TkWuv7KK8osg%2FPTtcfesw8xrtaWd58QeOx5qcvi35ax1VPDYg1w9jalMaTw9R6VzN%2BllSPVN7plr4zfihtlH9wYRiZ9uxBKtqRfe5Gk8nprn9r6uWwiYYLSTEOZnvEDO8TCU3nm%2BXYmznB97vzDM0z%2B1xVdsxYTV2Yv6ql2wVsM%2Fd1lQe1gzHPNOlXgdKqf9T3j1U%2BdUGgyUHYwfYP9ylgJ%2FPRHUE8OqL0opd2BjvNMPFkmL50vOAI3721F9WNfE612uSwsQ4czOSVZB%2BG%2BL7Ff7kI%2BSbCv%2F1NRNH%2BGByoEPy7ArXEvJoOcg41zUuQA3SyuvDZW57a4PZnZFK%2F4Hb7xV3YIvfTC9mpm9BjqkAX%2F6dWXZmtoe%2Fv%2BGUxZjehAUzf6b%2FVWS1RaISdw01qRNFYjiycp9inYYBzicYCEVjdWm5rnQpFXK9kre9CX1UP8mJqadwR1iXBOH275s9SfyDj7BfzjN0Xh%2FJw%2FQw7KxvYNaI1S%2F9isVjbSlqg%2B%2Fm%2BlqofGx6uj5vTvDoxcJP1MwhN%2F64rEz7ebI%2FdXRUelR6CAJNKzyBRyoac0r61xoqHUTysmf&X-Amz-Signature=9207470b596f4551d6cb401ec15280fb5b41ead323bdb6deb2ecb96a149134b0&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=069e62a3c431fb5c424329a528a5b2ca089a27a5c136a03b41cd0d3fc3634ba9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=7043eae9afdee83513e5b8acf9b9c73115e185c81c874252e316bda467f83ce3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LUXUPUJ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T183157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGIaCXVzLXdlc3QtMiJIMEYCIQDvvsupHJQfvp%2BNZvChrPyezSV5G15wigxpvh3mj1HZTgIhAJTXwaoqyvpFYArPUQYehZw%2B%2BN0et2ceyD%2BJc6odanjjKv8DCHsQABoMNjM3NDIzMTgzODA1IgweZJooSkus41N1mA4q3AODCSwmb6mKRRTOM5%2F0dvf%2FcrdUwLPtlqOaBNxlbDj2%2BV07l7bIyjK%2B%2BN%2F0fl3l6nQ8Es%2BoFTDojdqVLIVH17iAUG5l6rpoFm4PHNbn8JYhpb1jV2sDaRnfmdp8dMzjA7OZ5kxSGqycy2UciyepTWilShrsh0Xn8c7bojl0YONWQuhd4iQdYCOAyrq5OdmgmszZ8L%2FADNLRQZa1nH40zdVOnweLhMXNpmFgA9i46iZRi9dLC%2ByodBWhU7bJE0%2F1kxYoBGTs9Qx9IFeEexQnoYClPkRGeXrPx8bwmVjp6ljCYnTbxlqOIgrUxgcQxuJUR2acKQGw%2BGnHWPO2QVJsEj1gn08Oik03WieXvk321M9Q2J8o1KCK2nUBoYbI9m3pfOpUrQjZPsKdv7FiT0pGFtVMhqvfm7K3w%2F2MMUaJlBD43%2FD4KAzOe2fSEyJVlvNNEYUe6TrDQ8azSeJdjy9Q%2FFJ4jkflDQ4sURb2JF0QaVmLUze0mhzcDbq5QpP4gIfJ0JnGrMom3Sg%2F3k0WoLu6tLquQLZH2xFrFxFbTgF%2F9e%2BKVeQ0hq9zPv23ziXSj5f4F9XJhmILHC6oh242ngljY%2FVj8D5iDkIfG1DQDkwwgFMYxidg%2FPT5AD7OLD2adDD6mpm9BjqkAV%2BVM00Pnw8bb3gdFhmCJ%2B6ipEueJ5wTCKNHvlWkUtsgOIPFMikGIfEwWv59pcDbi95AMmhXgIWdGeAwQbZlGzf2Osqv8MjPTh5JzywfumwPahR%2B5jifaOL5UawS%2BbklGXViNbrhs6qMJ6Vo%2F3X%2F650Y6l2qo4BrrC%2BCKv5BJqoakA7RM6MaNNMakHctjJRw19OKcpyD8h0KA%2BhhPi6Ldu9899IM&X-Amz-Signature=40e40bc0b0adfc5949612c4291b0eec39c19ddd5ebddcf9734815e04954c3b6f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

