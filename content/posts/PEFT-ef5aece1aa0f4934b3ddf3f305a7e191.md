---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YE3AJGRY%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T032618Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICEUBNJ9MXcuDgmKayY\
  Mxtd5V%2FkepLD7gktEss6o%2FPQkAiAkDOGTRaKBb93Xf8Z%2FSAm2EHk3Sl3Y7SkOl%2B%2FVJd\
  dyUCqIBAic%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMKw0B5IJdiiM\
  dMHNYKtwDfTfMxyyfXKItpuB2ZPQquoI8kHP8d1DWQvDBNFVM8573pxTljBUep8iXnqNwpSPaRdDn\
  %2B5RHokxc2FLrIGwqJnMh%2FMwh0WT%2BKhmN4pK2%2F%2BKhJS08p0cCD4AYN%2FgW9mepAvB%2\
  B6tF7CVi8GOi0TJhzS%2FAIFgzMdkJMnmdXE6lT1UEn9GNBUx9PyE9Ofac4DtXLIpBsN724Zkt%2F\
  ESmvCIAjGBiFkeNlsykA76qyGvwmD0nva0x7DhwmpzhAJRaRU7044A3sEAyrvh0RQ%2FLsaPtqJHI\
  U6cE2Dmacg7fRokmqBwTj7oQ9iAkGL4KwebBeUYRgvC9aTlIS1vn3o808oiKoC%2BgL47lGAH5%2B\
  IoOIxpV6EPYcmB%2Fo6VNkk2AYdj6%2Bp8Rw4D%2Fpodw%2BVUhxbby4Rw2sDZaw1JyLeqIUhQi%2\
  F6bpmQzJX1O7ZpDR36Uhewn25V%2B2QJNbXkEnPesyCQP2C%2BH7ScZqnpCVbNsKcNyCZ2W2jXUkZ\
  M0okEDuNZo0xWmzWkPqx1Fn5I1wfsisfgFsavVOMM9RIg7Y1LGZglCyD9DBVFfc9LGFlUZJXYa9Cu\
  NEL7CsF5vKq0iRmJalq%2B%2BF%2Fz5GPGG%2FfdiIn7J4bLQf1uBcYEmlaKj%2Bj6sqCEYkVuMww\
  38%2FrvAY6pgHQyfmG4i%2BTmMVh%2BYP1NwevelzhIYglZaczK6PyB7mTsLNIy%2BQdNRWTKWywq\
  8O7dYc5t77IXbLj6fK9g7cTDKjvzI2OsIOUqbYq7R77MBweiUEVXYGMfxVvSBwZBIFF3Wty%2B%2B\
  B1oJYeig6cgpwyUGxqVNvOEeOVkOUkBtIWHVRqGU915GhpA31h1SwWimuzGuCjPQhZAgllxgRiIHQ\
  K32jqNf2FieTW&X-Amz-Signature=c265bbff41ad5f9275d95bc47b043f1a91096247debe699\
  7ce20fb7e73b8564a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466V6Y7O54I%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T032455Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDLhitiGKuClFywB7BAXVe%2FM1evhk3uNxeioPI6Tc4Y%2BgIgU3ALL%2BDjt1k4OY9I\
        pfaBN7ytOPP2OkIR5MuS38KhWJ4qiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDP6MzQ1pdgAXndjjBCrcAxzNq0KA9OL8G0er6ICNk%2FsDf4JawxJm\
        aX7EUJu6f24OqwW9Z5C7HwJZ9BqLzRgYT84stIx8ZdROq0Spnb%2BgJkLs9vtDfEfoEZx0N\
        vJNe07cNgoJ5O1hrOB%2BgQIwZy5p2tY7RLgdbGcxJg%2BoecgWdV0pJk9eiedkzFaMmVnx\
        mk5ooFYa9tiOJTItQNq%2FY2kcKEu%2Ftp3fBR6Sz3QZKtn%2BzL4HP%2B8Gys2q4yQa%2B\
        SP6LdBvBp1t5ShLWhvr%2Bvq2R2Jty6KfZZ4qF6khJUjpWRl%2FSjw%2FUvpSi%2BmNV%2B\
        w33vHJKnfaFQ8MEzSrWLUsIjRkVMgBq4noNXhwDx3IX%2BcodGipb0LTEWfInKzzqbJsVpp\
        GqqkcpMuF3uZ690pSSArPZRgKTMojYN8CX0PaRUDjW1NgS%2B7Amd5vS5oYrhynmNQqiJJM\
        tDBywVBT8LJK%2Foby%2Fzqqgh4bDtRnRQNUapAtkQ%2FQxYtZ4Ed4v7IPaziLi9psE%2Fn\
        g5TUAqi4YOKMar7WiTcUr03FQvJfryZRGsuesA8aLtUVNDff6E92uI87bTP2wrm7K88dX6L\
        sXxz%2F%2FwvIK%2FC%2BNzg1RGiBWW1%2BZ%2BurUFSXw%2BacBwGm8uEUK6d5UOGGVUtl\
        %2B41VMhjDEQiJ2OL1cMNvP67wGOqUBonwGKjLSxWBFzySgp5CXFDjZklFwFmS%2FXIoW9T\
        ibd7aEknh%2Fcf3wnT3LO5Phu0BdgOTdtF3IfVDnEeJlEv6yTRcGgntrYrtwCV6fiZ1epA8\
        %2FmDVC2WKAkMMN7FBvCwFbz958B%2B%2BI1r7nTLvuas5uEKfnXaHSTuq%2BmnPNFhdLXH\
        TpgJgf1RctooXuSRGvdFh0X1a3gNRoCbuRCZsoqDDHXRNwnDJy&X-Amz-Signature=3e36\
        84a3d7305adbf274c920dea6ff26a512f6957395410913901a0fcce41089&X-Amz-Sign\
        edHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-30T04:24:55.616Z"
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
UPDATE_TIME: "2025-01-30T03:26:28.383Z"
EXPIRY_TIME: "2025-01-30T04:26:13.491Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=64cba627eace5e028b169d778a92e36c0f9c8c680323fd8c8249c04b78c38f15&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=17269b3e5abc161b4d079c8f579dbb6389a20c2e2948ca1a26482de5bb55f23e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=ebc9e0ef65d4a42a8d67ee58551fd4ad5e9d7d9fdcd7e5db447de367becfd999&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=5e50bc0a9c5d91d73ba4cc7b7699c189736378ffdf297a08b986e28d3b6f42eb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=59199c7b05f3b9042dc81324c1f6cb4c9f2ca8e5de876276f6125883362ac8be&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZC2DKR4A%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032614Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDZCvrTJTn1tZeIGf2tD1CZDZK%2F5Qo77f%2BNMmBunpinzAiBsoEN0CA2wD%2FEmGkzV%2B00qVp38ViyVz%2F0mts7nieaXtiqIBAic%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMZkezAiHs%2FrMDHg7RKtwD4fqzDg%2BccC2TDxADE8v%2BsTgZ4VJCeNo9bTXhODHGmYaeAOjDDmmmutip6xkasnuCPqwTU8lnUsyb2Na%2BAin%2BV%2B6qsnMMpbwrrqQCWRPpHTNVgWDciU9dq0L8sCPSx1F8Used7mU4JPMJDGCNEq%2FovCXjRimkFaRWdpI884QRV0uzxo%2FIhHawnv03tuvOeB%2FOA8uQzbBxeo8SYiGB6iuAe4%2FtMdpnGTr7jS9UkBNkuRY3BO2dzODaQZDLrF9oJvvQlP5nSCIlHO7GNU4PdXjEjzsvSVnQSs7QGEh3pAHWRkT0Qng4kYmhT9osK7CIlORZCbVkd3QwbXdo9dA8sldlYHa3eNHgWHsgiLFcLf1oCprMffvzxytkBjw66FXEfo%2BAa93WziA%2BE0SKZPgCbS6o7mni6ui0h54CLCiTJWPm%2BtFJxvXuEIjV2f8VZGuJZcfjNudwOkd03u%2ByLkXaes%2F2MtnZkGnc7Z4ziaRgheeir2KVgeJJcTgOpPx8eT7gwCGXNCpRV9CkQkWGrl%2BYYfu1vmo88NrBFL%2B3BapTScWpD869Evxd2fua5Z53H7NyHe9bvNttzp%2BKMn2YAyPzDC3GL%2B8wLiH7WpOH7SSjVeCxU6rENKidw5mn8CSj7Nkwqs%2FrvAY6pgFvQVYVbqMfAejUtP8MNUCTWDbPlJHDsz1SdWSE936%2FKCAsZSRoBXBGnzfTuGHFPs0ArcMSegJypavVMaEGRZWPa5WvFI3LmCWkaHtY1hQbFNGgyCF2c%2FI3gDurFAKDIjhQYZ7f7OTmrWYjU%2FPK2QJGCOdQR39Lr%2BA3Jp8wped1t5jmXasMcMgs1LpzlK7%2FOwFRcdTcBeiMEKf%2FLxitXA6UFb5rvJ1q&X-Amz-Signature=2a320dbadf05773b03bd4050c45821b29ef00f8ec3aaf06638ecfa8131b7937d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TSCH7PXR%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032616Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDLHrvV4lhH8p1XwiBZw%2BZSezfbGFfO6xnpejqISuAOVwIgfSd%2BLRNeyDDAU6PJwMlHNH2g%2FDS9tDbiz%2FulVpsqL2AqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPUP%2F3e9txfsUfAvEyrcA27HPNZdzsT4YF6YyiRWgj%2BokpYXWHnkbFfu%2FF7B0YBC8UdcMR4Wj2IaZRL6gJXRdZzf1negn0jAGLV8U8IQbFkGkm9bGl%2BTP8YO%2Bu4lT3BwrapJXk3zY5eq4Z%2BfrY%2FymoYRGQ6xN9v%2FrI5eqA3mH9%2Bo4g6M0IuP67A4Kz%2BlW8ozA6NdkSDDOs6KJv8ttBiMfZ9Ebs02frf9GCtxwDhmrOED9sDEbn%2Fs5KKW5vbukOhqE8ZmAcFV9RsW1Y8pTb%2F1jGrSkaSXK%2FHhpWkUOm9mhFpPkj0IM2Jh2Ar63MuZTbhTqtR%2FvzAGriQPfCkiD4LeypoUt5IM%2FPboNxr7RNIpP48x2mT4pkQpwrtKwfVMbHemw3ihE%2FsjpbG46nyPPvCpt3lNX3m3z9cw91PuauffPv4Fe%2Fv7X%2FNeVhSXtPQonbUOcNrPnX0kkV2zlPKc%2BQt2BNDRtongaKZhnFdiy5z5VGxRaezMCzCGsxqZtX%2F%2BgRoN4VpFYP%2B9rd48gsFLyr4oSLrMhzFD5xoRMv%2FXWuAMrbCh86bovNJqSdw3valOQer17oQiqc7LKVetuwMPMfql26RBz%2FRnb1a%2B9%2FbIitiTCI5iEKqAHkTVsk%2BZnze%2BcyyYwR4nbZLNuJJrQDwuMKfP67wGOqUBmhIJVvuCYN%2B%2BBMK%2BJkvL0Fi6OtPpQBwIXWT3hmpzXARwWuzLClZKBW%2B%2FVV6l32mulCSaVdg5J7Uy%2B9L31bekhlZHwTblwkxMecGkjDDv62rq9f5rsmc%2ByPzTlcIaMbSNMQ9D7ZoaYUO6WI8%2Fa%2FuerfUlLNXAFo10RWFJOePjvh4yDkn%2BHIlWMcB522x9A67zWUomDiaNjGyozUdVElIrKXCoI6va&X-Amz-Signature=a8aa43e3f428c7f85076d364585a6b676e239910b8f816c59c15a2eac7df41d5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=9469a9c34ada638ca07b295dc8e30723e93ebfb51098eb4206de90f7c4bdd1f9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=85e02ccba59fc51245d64d8647b25948adc051af93ecf370bfd7792613be84cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XYRLTNW%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T032613Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfc6GrHR8GN6%2BvSp5JN2M2hdFE5kd3NOXOj8rGSyh9sAIgFnGBqhvW%2F9rPmTGwptDJHHEWKfqiTtvWk79usSJDGuoqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMRcMi7fDDOZeT0yYircAzpKUaNUZi5f5EGlLPMsaljYWSB71gheEkwrVfmp6jFR9ZAGPcR4GMgzsW65J5Jmk6vlNEMjx9CCURon5W64n41ZPDq9tMGQzcMy14V83TQBTS3vqyh89iF1kkHwK6DVZ2g5i%2FiRzUIKJF8dcRKXuXN5vRWDyayz7bGpw1wNyrartsLqG6QISLcyS7ZzoJDQ5lhJ1IVcLfaTKCA43JN5d79YcwdFZplxVuEcrbJIJQd90TVrQKB4GOXIqy7M%2FdjABa6f7cG38W%2BSSid7mTg%2BaEy8YvQaQhtbQedL%2FsSYRIKuneqxXww4srOI3le9Lh4EYUbN5Wtk4KDqgFHFmfKe%2BYBNjQA7NmreAG3t8boEhP%2BmW34BaS5kLGnGi2BJzWeG3Y0EbEncMWvZxtl99R2WcfS2n9IkwtUMXpMjkNeTLKIOXbLWWSn63JDZK4mXYZHMJRXvZU8rRUcVRBYFh8pFgJSgZsFep3GCNiVHFAFTekG7a471EGxzFXOApTlfxGHOx%2Bbe50m4IKteioV4baeeyFpbnxmhLH7HQO0I6KiUgxaoonPhiCoaGXcPaXRFT7gKRYMhgUg5h5V3qi4JtBD4EOikzlnU%2Fzt0j4fTjl8PCc%2BwQOVcEHsBS%2FhsHVcRMK%2FT67wGOqUB7GXxPl%2BHh5E5MAWZ6B2%2F3JmERYNSXwKlg9%2BGHgDFOGApPmTSy0Wu207TWy5dCrPiv8TISaNOq%2B%2F5a5UrZuF7tfQ4gUu%2FAXUPlWf3K8W9qmhRL4fW98APoCYA0vVzJsH74lRfd9zL67%2FVgYg9tU2z1Ba9Q2pwfYJlLzN0NT%2BfxRiys7fKhNjraRYoOEkdN0Su2MWM3%2Bn2ImvhTPxDsbNMKY7KdnV4&X-Amz-Signature=76eebd72020541cfb60d6017ab8f0350014ab824de78564bafed254adc482075&X-Amz-SignedHeaders=host&x-id=GetObject)


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

