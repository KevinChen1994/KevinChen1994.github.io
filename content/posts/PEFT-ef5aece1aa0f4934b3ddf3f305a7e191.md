---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SYVDLHWY%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T142316Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDqlgEgc%2Bj9VMiYV\
  6XYy3%2BYw6T0V%2Btk%2F58GrJ0Sl9WmfQIgLmERv6be6Tnj4mSPpJ5eVuk2LLlTdmywR729Teca\
  k%2FYqiAQI7v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPebiYxy8hR\
  QzIQXDircAxG2soXkBRrPoQQckMEov0MbADgsX10qupfbsKouDtz1KoNK%2F0qcHXWIna%2B0tjuT\
  Lo2ysgzZ94KB6Jj0XcZQH2xn%2BJBU37qkw76%2BBlhkT9DbujO4TZvEAn07Rf%2BJj64Uad7KXCf\
  tJ70w2YopmBSHeOAkaCbzycclklYIlbL1akFtoy7I2UWSOzgsouIaYHhaxmNl8ZihNp3%2BRdVqNc\
  %2FkUfxqT8ecaoDGloMTAc5q5T0eGTX3R043Yjhai0VSFriS%2F5JJJgjV8HYjfqPteMihc%2BhJs\
  %2Fa3HvUXV5%2BKPpAgwEAF8YkWegA3GzZtW1CoIhW1Ut7XVj1rhPyo8vol9fF4%2B3x%2FCmhq4U\
  KMtLV2bsGmJAck55oA7NU4lQ4JEik4W%2FJH1r849yROTKRG%2FnuIcKur6REHBoCWvbr0AcUfliu\
  6O%2FRtPTLLIK6uwz8qQOl1tsK2AuTFgoWEZHW7tjfBP%2F3ki%2BBH2YZtsoL5Xe%2Blmqu3nXNK\
  6gdJQWE3qzF9pb%2BEx%2FANE7xpTqGaPCn%2FTB7smDp9JtTJ%2FPccHhYsbk0t5DS%2FGE7SIN8\
  vpMtJE5mm7G%2FDQKcQK31LU6r8ltPAPm7Rr40fT6vDdYMNe3dRsMCSiO3lWmFd3XeGw9D5tKp7Qp\
  WiMI6ssr0GOqUBSGus5rs7SDMDgX1D6QuKOjDM6o%2BHW9bLLZNJ7ntwoEDlqMlCxVd3Dg1MyItRb\
  u4JGcw5XFfTSCgjPLD0lSZan1R%2FgeE3AEwseZ98ZdgU5IAZM%2BuqVlbApne%2BMVadaUC7o7dY\
  WUw4S%2BrmDrbutneYrln2Xyulr%2F52v1IQqh8qMdZ3AGaXniBfpqw%2FnyJgU3beN2ZRiSeEhoz\
  FZj3S3OCccODlB1YW&X-Amz-Signature=13f1735128d659c255f4f9cf2772a11c479cba29152\
  1fe070c3bdb5518eaf101&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UX7MV5GA%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T142139Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJFMEM\
        CIDTPD7XRxPdFPQWcuNWzrgHGnaApt0ItlatrdwxDLHi9Ah9ciatZQeOXVaKBAhUl6UMvxG\
        aMD28gA9qJy%2FzzbABQKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDI\
        zMTgzODA1IgzR5xAslXdUYq5GHbMq3ANZY6WCxCSegP6XKyRZGg6cw8JmY4KitxdlOxUUUu\
        5ehJxYFPnfk9%2FuKPVI14iSyTKZDzmI%2BXomaDoreJRlXGZYBPpq45xkjQcz4jBhryIy2\
        7yHI0M9nYmmD5U0JsFR5Pq5PJ%2BgvRIEG%2Bm831Z%2BqSOlPYjT790Cb1Y2fndYR1Gfab\
        ax9aLiQNc%2FZvWx0h2H%2Fr22QAbFbuLHmksifV%2FGsVn74gc4lm3OHcJMAkWQoThvtSk\
        8oMbEc5n8hFNN7xOwmHI1dkQ1QML0%2F9dXX4GBoctQn6CWoCypm0%2FGSPNVMHSU3TlyW0\
        Jj9CyF3TE8r5udO2hJUnjmxK7Ymw5eGgi%2FIq%2Bco7CSvxQXGHwbxPFVWHLMsZ8unyBmV\
        axdKRwbaaLc3sa8bcsvJN8z%2Fwy4ElBM2Avvj8cguqPNQ5zNMhlmUj1FBoIQbshLh45%2B\
        qMCqq7oHiBycyPCeb%2BsGJD2CQIsVIUlC7EpBmY9qf64POPK9O%2BEDA3s7wPeXX9cj1x4\
        6u%2FOOx8HvsUeNKvGCmiBuqRboR%2FPnp8gpf9h8pniDitUXPO39WNJEsKz83gIrfyliEw\
        mMZn2UiIPXYz7a6W4ZVSm41fdwtkyFIt8voUEcmSWWkVN8b396efdOcbhG%2FDQZXjCVobK\
        9BjqnAQWqcO0DQcdcgG3WMzROfqrHcT3FnsMiLsGbCeDiIJy%2FJRvYFRUVh2rdiCbiD53%\
        2F9EXI%2BYgg4albqbOPPnsFKFw6SNHdmShfj0lL7A6QwCpDFA6uO02lQ5e5dXIOq9KE94J\
        0QjUkLVAmEOhZiDBNDTz4NoGwrPd%2B0zX%2BQraRf7U4EYKsmL2jFmIvlsid%2FiRzyxRu\
        6xQLGcA61Z7XZRiyTjw2rVXxZKAj&X-Amz-Signature=96343a8cbfa7819879cd64f5ff\
        d713179a5b9c5261988e0c185b11121cc1af93&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-12T15:21:39.740Z"
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
UPDATE_TIME: "2025-02-12T14:23:26.521Z"
EXPIRY_TIME: "2025-02-12T15:23:12.680Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=6ffb06ee06bcf01814a5d0fe56a72e0ee5626904adeff498797c968876674061&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=865f5d3515e56db0fb197bbff0f90fcbf80577b319081236a355ad30dccaea2c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=f7e3840fc48b22f267f479498974a69d02a45fab1b5f9f9ebb769de6b413e0e9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=195a280134f18c71374a63f591e546120fb2d2e57cb239ad123469b84f930f4b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=3d5c8ed37c3a9d587171da01a3d850bec85448dd5625b46c72f2e9a3ef39fefe&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SO5EH7N4%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD3v9RuuoEwjsqvDZGls8IU%2FRxebgeBK4DFhlpsBQrn2QIgNQmk9EU9H%2FE87332lYRGl3%2BxX%2B6Y3unhCao01ylpNewqiAQI7v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJzlMWTKCbaNtTvG%2ByrcA%2FgxtYPM0rYStkn1ZZmLM%2FUoJ0PF2Lqmlh54WKvZufCFA2YBb7SeXNZiaR%2BB%2FuocMyrjC6BORc8SgetgE5u5uTPMJpNcRX6q1ZvesfeeDM4qcoY7EnmfNcHT3CLAbBD9B9h4ByXcC9IdCKaxaMB93ZIzquFxD%2FG2pEMhxpfoqbQm3lV5hGeHYn2T0pXH2CA%2Bi2WMQDOx%2FF8FWIe29OSL3iedOwjoX8T6OAZwA2sZgDnYVaZtptfQ6eNe3%2BlFP2JNE9HJzTQYxyeYX4ivBNDdrM8wGufeodP7Wa%2BXLoyB3tfHsJ2pI4V3itMpEnGWaGjn%2BxD0w%2BA1NQSBEsbn9bCJ3lSS6ZP%2BDOc0Z4ZUPPI%2B7RrbAEvdeujGDwmJDXbpoViHqRQZJG0Ot3Ndit4E6k300RdMKWPRHL63d1htDep9rCtt0uCHn%2Fn4EGEs4E7w%2BUb%2FEW1GOwc8PmyFRFzyR7MUarO8DKlqQpkTQrXCKdEp0LLJ2Js6CSH5rcBdUU8FmMlptOmEFvluN0k8dhmqJ4dNKvpaxgy7EK%2FwZpH%2Fq1jPhDaRKm5S1tjxc1yQvYt1ZkMjiyPsbx1cqGB6Z1PXuYMUkmwVdYfor%2Bu0yyJTF6G6kl6ELv6fobwAjsWUH2SEMKapsr0GOqUBUZdau2x256CATLqoRYeJTpund3gqAmy%2B1dDLCdQuzSVHDzwEYhplLRMNdc1r4K2KvqWXFRlPWA2qR0ER1aj8h1xwX%2FkPXCfMR5AyTok0lCHeXPNle%2BfyvETAEv2XS1gyuktNdCF4hmkGq5tootjhqRfsQekWaaXC%2F5ZRnP5n272Ecjh%2BlT9yziWNDA3md7ZloTsmvnQq4XA%2FW4ipbo5jfh9hruPq&X-Amz-Signature=690d38da6b0b35d858b8401292e4a88de1ef7f5482cec1387ce8a3542a56fe3b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SKM3IUWH%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142315Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDCXFqdZNqfhX3F4nfRiPyjyYQQCPREaZr3IkCv8bRYFAiBGiWzgm8QYlT230OinCHXVAZ4yGrbCbECU%2FHiU0usbLCqIBAju%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzsnl7vdSAIHWTNOAKtwD3%2FHu1PIxA9GR8tLrqDRlNYCnK6uwtrEkMGBO3imZczivgJCaX3NuDTVItgWRrbwgKaq3KhaGMwAAgDQ0XduBhe3Xg2kpvU3VY8ocv5%2FvprXBBpFsMZE95CebtC4Lg5mAN3AacL%2BIeO%2FMB6WmL1KGwJY7wld7cE%2B7Tzy2v8JP4%2BTuUKynXSJxLjRuMbnTRsy53W0zgd7aDjS%2F%2Fd64STiParNHWltb6sJ9tOomGHvBdzGmnXYwcsyKKOozU9Aj0O6kRRGFhpasOKrCCEGGoP0X4Fn4T8rkgAYUt%2Bn8DlErtw5B13wIHZmsQ%2BanzYL759HyPDmCFGMN9uFjtoGqsU6s7Ljm%2BdQ2FXEd2jx7Ihkn9%2BdH0fC590wwPRnw7KfgdIuq4jq5HER15Sy4tWlXUh6u%2F9vRBzuXJ10GGRgbrfR%2FDojca8obodMCZcifozgBaHndj86PISP6A95TRPC0S%2Fj2vKogg84fHHFnrxpTPNhG839dhqXzNdm%2BjefJ0X63B0nUDljrmXfn74PrBF9sO4Bs%2B5QK0Dk5v3YxgdqVXQ1G738WDOlPYyZ99Ng3HYNgToQdhWS4ctGZBFzrkC16LbYrePLR4owgc5yDKU1rNNi81al3nTJEybgAWh2wr9cw86iyvQY6pgHqKQSuQWY7cezxHbF%2BzwKE1zQINqD%2F3DvImm3o9PZLENnHopBOYiosgU%2Bi%2BmjA7%2B9fkwWFrhDSm38KgvIit59DVoZwdNnnW%2F9Y6TpfB3IPseba9HcGJZfZfrS7Qcd2%2Be6xqCm7tFhGXhF%2Bsg%2FBmbsnnolawO4DN%2BNIn%2BSorv9L8Di%2FvWzcOf9Tcq7vOL3h8G2LFivJauojsoB7mqGLF5IGjmFKSjej&X-Amz-Signature=a4b3ae7fa7be24a1f9b7fd4ddd08f551a5c81273948c5232bdf2d835c4d5836d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=0dc1e32c1fef3b91453092e67413c2dc2d8c4c1af925541f2a0d06aac0b850fd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=90ed1e0ac63723d0b09f3ce33e4a7783415aeba71bde6ea0fe2179e06a40d9a1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNLGHRFQ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T142313Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCs%2F0%2BWyTtzCwkYE54SQ5ml%2Fz5YSXdPVIn%2FoG6NZcDBrAIhAK%2FQ2PzyvqHZc98T1wAxfIX4xYp6HV6OqbDS13vkEzvSKogECO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzApepfIpeQidAnSWsq3AMShkX76f1tRL%2B3CFG3uL7OEia%2BZUa0ki8ukRP55j5uhzJHWh9KSNHa3ynGmTTfCynLb81Pa3oMJZDQI8XbIsg10FSqfGPOylGA2ZjTHClPlQUnvlQ%2BUBkRzqTXaTJGklmdMeXx7yO%2BNiFlKeNp1LBeoL%2B%2Bsv81cxpqbQZSCGTjmjb%2F1O0bwOk4%2F2jFJtN8QcTCh7on6oW4qN5Hm85qHitZMMS3N1r%2BWYypd2KfpDEk2wozUFC10o1hwr%2FpuUj964CloVg5RTf6%2F%2Bo6mn%2F1SCAEEVxdw25eRlhVlNkZYMa5U6egzkRvBH%2FZILl0zj5YZ0xGI3T%2BalHy7MNlIvOx9FLb7U70TmlWvAsimL8URkeQjDstKCBiDOVI3lopn%2BjioYvgeOeJ0oalAptHbRtnPSyUvgtwoiSqxDi4MmkAPlmr4TzWD%2FcRJw%2FgFtdgHYXKQImtrgA3Y6q9drQk%2FKvPIE9Nv7FE%2FN3wRS08QneGKF0MdLVNb%2FI7zA1os3maQEjCJEf6eqEv1TwwBDCggzotRPQF1vKRdD8zaJUiPPjjdn0C8zbhsjYeAe5N1DCerwx5T%2FLIg0qRYGQ7VubAIEnswVrEjyn3KBf2KyAbSQVdQvl7DR6ygQGogxqHQDSMwTDbobK9BjqkAZYAGxwIIbp%2FRtkfBdnwSONppImFop7er8UvFeyuUoqybQBQ0Ww%2BfrDnMN2fK7dC7WweUwysoEicz4nP3tFaC%2BH1cEFF%2BNfvwuUjCki%2F01eEZ2Slo66p3JicM%2FYV8SW7JlLp9Xpw%2B8JlxhCNz1cXN11BojGw20H4XPJu4J8y4sULZKd5UBefwXlk3EhkirnrD4djt8SfSzu6YlzKSe2ZW9XsomQP&X-Amz-Signature=73430b5962dfc34fc9f1bb5d0e9c30cb04648528f71ec944731da7c22a2cfcfe&X-Amz-SignedHeaders=host&x-id=GetObject)


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

