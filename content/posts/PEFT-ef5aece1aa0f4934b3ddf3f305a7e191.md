---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466X4AOJEZ3%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T152533Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEE8aCXVzLXdlc3QtMiJGMEQCIB6NIaShWVmQUpUWvZmi4wiSilMK%2FQVD57aLe3iLkhSgAiAsP\
  rfysCGtbEUKrkKQqz0iqbszpCIkZIe4wHIlB4Tfiyr%2FAwh4EAAaDDYzNzQyMzE4MzgwNSIMePVr\
  W%2BFkxgQcy2TBKtwD2jFjfJyaiQNFBQ8%2FY2idRUThrnCViOujs6%2FrUZnHvUTF9u5r%2BjAqa\
  LcGmYeUF2gCTHIO%2BRZxfStpHWHtzWWWpu0Hx%2BrPW%2B6%2FE9SdR%2Ff06FMOAJz6QOx1qQqN\
  LXd4MY1UlJlyyYQU%2B%2FJG%2FSiLEqCHEPTtq5Ia2%2F8PjfBEqORZXxSVupmLQAIsi%2BplPqr\
  loRFtHkp19JjzEJhuauFDAQTMUPqvsxHkDU7gIsbIcFhc3Z%2FfZ2rW3ImPWVlVcTvmFm%2BlqTwF\
  nVe%2BWFNgVYwon%2BJybnI6MKhlW4fYBUWzGW79aXvsgGvKrOgWoCC1WSIuUc4rB5nGGbidAfYCo\
  w2NOONca1%2BuDNsvFhGruBM5HIRR3liJWlhjNsQHf5ZevPCOIuLkzIpE0VK%2B%2FmFFLI674kJi\
  hh7fp4afwNZ3LwYUC3b07pOckcrsPhX%2Fbu8SzZZFIa4UpYyP9Bboo83Vlhdqn75td%2B5Lmfas%\
  2FBaYtFe6eqgZ0v3335JLFeVI0oLEG%2FA%2FLZ%2BocHK6rvJtRPtPOpuwJGaKaPE85F%2BKiDwy\
  bphWAipO6EoKfPMRYfUXikh0TA1b5C3J2XfrBS9KsQgVv0FZuJCaFXTRYxcGnaiLglVKJrONc8Q1I\
  9DL5hMoCGParCYwqZbNvQY6pgEx9k%2BvSA%2FJhGd4Nnkm4wqk%2B3NjWbWGjd%2FV9eXvPpDLEN\
  ehGsS9iBuD22oQUnl7yrWninA%2FIU8bWC8l5hMu7NaOFhamjQOG%2FHbdsvwvmHkLyFwA2Vn%2FQ\
  xzCf2ylojoXHG1p5qM5VvVZXhC6B4oTneNlqc%2FQ97grrTUcOxZoQDKG6wr3lDfOygao6NvrPTzq\
  Y9FqXzPGDKJgmMY0JeU2%2BqScPt6%2BFYFD&X-Amz-Signature=bc6c154baff641653b8a71ed\
  292abc3766f9b361f51657d2a7e4cc1fde57547c&X-Amz-SignedHeaders=host&x-id=GetObj\
  ect"
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
        redential=ASIAZI2LB4666YY7JI4J%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T152342Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCMHctkCb58bQkset%2Bun0xLx3aAa\
        jq9JafmuGV6Mht3HQIhAIAeIf%2FtlCtmCxQ%2FQLCsBTpfvcDoZ2RKuLTHYDstxnPRKv8D\
        CHgQABoMNjM3NDIzMTgzODA1IgzZ3W6%2FwhKWlpyvhkUq3ANhXnux01Q%2F8wF%2F1ME5W\
        EEVc8BDdeHhARPYPPSvrrHe%2FUQ7w49m8HG8B%2B978r%2BeoIMmhd3gn7soGkd62fl00N\
        AzG7RkBsmQYEB%2F5XN0ou%2BDFAHAa2DLeC7P%2BTSqBZeAsenVK2QvK%2FGzZQ893JcqX\
        LA%2FjyOAlTxsYKNmUvWUo6G2OW%2B8xn25GyGOrXWn%2FufuQ3NXc8265ynXgzNPNegh%2\
        BAQYONbqbkaTdGjkdti83ExvYvY%2BBCQH5PJhnbZlNhLmh%2Fgr0PXEYC0%2BErOpEX3O7\
        G0R%2B8EL6tQbKBmHsc49R145XkrsyGxSZp3W4zrUTzputKtqHTWYJqvyQK%2B%2B7tQCCO\
        8L%2BuJTc1XjyZ3rcZISt%2Bgr38fxIfNCCWCIP1yq5RqMQqhQMQ04GrxBe8sfvrXKZ5l4d\
        y2buQ7tBvl6eOSVB8iE21kgfY29FR7no5De7pDQuujFvs5hwfORiHflUQ%2F1Oq2Q27MOy0\
        P059Jhd4ojBL4ZSiA7TuGDHeHx6oCFYPl0dFZDuWVRT8X77B62lfuUuYMk03vX8j1ifPA4I\
        PebF4gRDj%2Bwv2oIlpuAFsxPWz2zN9tPFllilnICw6uzu0WFKxaLTGHg0NLmqTZiCY9Bv4\
        55Y2tBNOqdvK4FIuGDKTDvls29BjqkAX83TbcVTf%2Bt7zv%2FvlkotyoPEvRILwGsFemYF\
        3Kb%2B3yNHUszogCg2RMHWgTV2YhEdRHK1tF5AFusmG73OZen%2Fmn5ulFfGkDmiA4lTt3l\
        oAMANBUpcvFrZPw3Zb12Nlson920i7TULoww94zKr7Nqia0emPJyXnWCc9Saofl2AQs9yLk\
        d6eytotdRBH3HGXTxmxcJ%2Fu9TvYG5n8rNnLTUi4%2Fr4RQQ&X-Amz-Signature=ef99d\
        56099d68bef3e4425a02fe8a60da2c1b5555153d2c1ed6b3774009e56d5&X-Amz-Signe\
        dHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-17T16:23:42.213Z"
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
UPDATE_TIME: "2025-02-17T15:25:38.336Z"
EXPIRY_TIME: "2025-02-17T16:25:30.223Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=17a05bea2ee10d1f41822622c16f28675a3230d58511fd008e92360a47afb33b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=12981441e6c150aa2bfb542f2b96a80950718b8970eb3085fdb417d61ec8d845&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=ff62c6b14e102053e329cdcfbe748d16a0e789a2e4486dda678a2a494e56a63d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=60a1889e2aadfbdea0132571ad41caff3c76dceda34cc5728aed98bff9c2ebbd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=78a9bd50911405d2660f135f38301d4f9d6ddf6ea48915876abdab73f5773734&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663DOCIWFJ%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152531Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJHMEUCIQD%2FzJtOOr6TRbQVgstBIcSyBU8EogZ%2FL%2BCF9ei%2FcQISjAIgOTf3fpXlp0rw9xAr6FU9lAcQ%2F7UVBQ%2B5EcPSnWAeZW4q%2FwMIeBAAGgw2Mzc0MjMxODM4MDUiDIKiGKSmV%2BqAKdXZBCrcA5LO9kAYG8rhmuIku%2FIbIjPHFnCPiM8%2B%2FFC%2F3oxoDvJF4LIkO50gd8A08s%2BzLr3eGYaKTixbHoJkTTzH2HjWVlMDhVaK7RqB4bqKkzZ1Vfvn8lZ5KWApiTSbmeQQ%2BHOZ1KzpfNs8EeMuO1cHmjbIK94bH9B3ChoFZ7pLxOQm%2BuUMLFdmVq0A%2Frndjj%2FCusqSImyZI3SL8J6wgPKEJkWXrmfys0LU%2BwXobUzz6S6b1ysRW%2BAvfVW9qsDsiPalf8IiSupzWOCrp2HBvmR4iplOA846tUskyaczYFk18x1ysV5CnJmQOQPk0%2FLGUSHu6XHaeOGjJZA5z5KamRgRmNoGeRbQm7b7IMCkQk8gJNyIFZ1lBFba8nmeb7Q4BD0ngMeRA8g5%2BdpdUOvkvYaStjyv2kKksT9n%2BVTW%2FNuhaHWhQ83XaydoKGOgc7eYWFiSNz3mNIJ036qY9EoV3pzfZmwGwHJd%2FpMWPORQT4kSOR%2FV5jidawybWoy3kEkD0msLt0S97gg1aM6ClAIgTPShbnLGWXPmc8aw%2FETEQVhfxCE4nzdUo%2BmbD4twQVIAztiez7X37lPy39gTVrNbHIBHcJmMJyVdnysIsuZb%2Fl72pVzjhe0NlKReNB%2FwHGTyPNn1MJ6Wzb0GOqUBNZeLCfTrI537kDCeWSfVJfpuhOg3NABGaYjmpIGSRKfg3fsxTOE2rWPcyMiLQIWT8zg%2FDbNYK7sX4Rh7C5lRETZ7LHJsgZVOV2xKAX5jW8ztXk7hYinOTJKhO0kuxGcUzXFcgm%2B0zrjzB2ax4jSjE5TyTLfF64rU4pksgWmzPpJVHG50X8UTVI1L%2FvVoXX041GLQ6k7nazqq%2FZGZ5mg%2F0kpJcgnp&X-Amz-Signature=599c2f5d01a6db453585da972373619d6ddc34a2fb4f46d9cfc0f9ecd5069ed8&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667T2L7FFR%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152531Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJGMEQCIEwRLqkFD1X7hKnxLNNnkQZRPiZj0luc3cqaSGRGUl3hAiBcVFKwOjKzTRcr3n%2BW97oZP4aMtPkepuuNguu9ldx9Eyr%2FAwh4EAAaDDYzNzQyMzE4MzgwNSIMSOk4a3YcZYYeS6lnKtwDdiNz8dW65GwMDrtbAdM56RUgAk46ZIkhnWdrm2jfR6Mv6zdafqq5mD2JVnUrNe1R9Lp%2F%2BgkGFxL6M1J46Z49Ebpk4a32QZKDJ1TaPAjKxEGdcgaL2rW1VaS1m0dAPoDP%2FiZbJ%2BuEm8wpWaSkU%2Bwd2ZVU6nUsr3UO71EN5hw4pecI9BHYD%2Bjh%2FBFoOX8%2FiVYAZChHZzbHio1Idr4xxDbaCGWRCdq6GUUNqfJ9w70uvFsy0LXfwrYqEQ1jSVATScY4TtmeKswq%2BpMpQdz0OPHhyTurNB%2BbdU7v5U4GCaB8f6AdFxCjOyuliQKgOdZqaG7Yfb5JTE1kTaD32DF2dz2rZSpyqOmW3Xh2OmCObRYkiqvDD5yqwH9DP5pjUd%2BXcdqeWSAZS5iCibweVHjfMR%2B%2F9m4nWcSx50M6StTo6UuV2yehui3%2BQPzEP1PLqbuq2itTZLtxK7AEWBmQkoLrOuqPE3yS4Ml79Z5ZFVSXCnvIDXsFwoqP3A61bdM8jJTQl7%2Bb5XfJNdVKyV1o5LYuWWQjsz4B2ut4mndXKPdDm%2BS4V9XHyuRdd1iEvDIqWbDAb6uhOVveEH8YPalJ%2Fk7uvtwXyvw5IhHkCtp2wrOMJD1AFZfXeACYfeSOZWLfSoUwy5bNvQY6pgFYwSrMdr%2BefLAIdIjDXoVkgE%2BrEKr8ZwROaxl6zIj6TdeV4x4%2BnVKaT%2BHWfzTna23tvEK9TGGBLlIrj6wuKsRdUJ51L%2FZNE1LBTWFBKBK1uZHE4AsAICSXRL4CEDTjIqHiE%2BeRJP0Hn4TxoTxsGmhqCdh9ByMTenQbLyn4eTTujV8i4tDDdQm82RwrcTMMr63ArgtxyhLLeG9JpPTSRDA2xwYCE9Uu&X-Amz-Signature=f32d3f11f4e013638d96999a2ec53b924c027d59796bd277d27e031510d7a3f5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=67542fff2df3b4dfda93ed8998b98b4689c13b1a9214335aa05c8c75ae615afc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=dbba848ce4b54d7cb4e4da6a46f56c64c8e5f441cbbca21128f4df066632250e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q2VYLAI4%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T152530Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEE8aCXVzLXdlc3QtMiJIMEYCIQCA%2BZ40MO8TdkgsjA6o%2BYrAKAT3dyiMSYoDwLVQ5WOEagIhAOg4OPZxWUu6ojLa1nzT3MwHqzM3ze8xC4Eww3UqM1abKv8DCHgQABoMNjM3NDIzMTgzODA1IgxZ0brQn5TBONRSIRkq3AOVNCt2S4E52ohw4dmxFwRt8BJfiZQX2wMG0BbbA1ZU7t5qjf70tcfXLGHqGGXFs8KGOvu8txmm5u%2B1GdiT9XtlauvFTPtssuvTTBJfnOp1AXri0a6j%2F4PSljYpv5EWzXI15UcESCgvZqy4GdOfEUUCbwyG9wKf3f5UWQxosT6%2FzAJyip5j3NUsg7pkFq68%2FBWJrbMPox1%2FQV0sJgYwIhjQTsiZtJ%2B%2BdZJ6Ep0sWl7AvPcLQ%2BW7YXKNWHKl5T1suslRvzKKl8txN8RHsJ6r4dQ7Pc0e5aItgtrFRL5ei3ld3k3RP157Qns2x5JHjKUDx01rlbKtoPij6DB7w8lWDP%2BM4PgTjtDHCQtPGIWDkbJbdq%2FxZbOwQNLjvPN603b61%2BYI7Y9qnet%2BgIfvBvyz%2B5wXhR3ObxfIZ%2Bv%2B7PzMGHS1hxhSgMMwAEUIUdcBT4UbyCwac0RGW64rmK3%2BAqHqzdoe%2FVn39OMTPdxgfV%2BjQMY%2Bzb6c8aElMS6Kf4ysy9DNjf3znotPMbdblNt1jlLlxXFeEBKQNQXjk2Io%2B%2FXUVCYwYcvfPPIxwpT%2F5o1q7Ou6nuwSeaemgMWK92hrlzsBzPuBFAA0QJfGvh7%2FikE7bm%2BBhgrh2tg%2B89juO6TrizCyls29BjqkAcRJm%2BGhgL9yf8HgBWYmIvU95f%2FiFsbh%2BSpzBMFrCYCMviyXpvXspYry1IWEB8crAHoWhXMr%2FaaAHxCpnSvyxLRCyWNT4Jdj3hcX4mxJr50G052YMAmTt%2B715QbTSXLymNPPFVkRbIryesu4Zo8v6t0mTw0pA9AXY58vK%2FhUd%2BqWTNWQ3M1QrE07LWxHvgkR0LIeQNhaxgHiCBD%2FFjyXnMywZ4Tu&X-Amz-Signature=4928c937e98ea4b8915522c9fa30c0ad055210dee472b5567537eac3dd911dc0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

