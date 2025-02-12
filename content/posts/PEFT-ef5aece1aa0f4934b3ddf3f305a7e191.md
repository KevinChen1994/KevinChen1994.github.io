---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZKUTR2UB%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T083036Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDd9iaf0%2FiJvW6\
  rsJJx89LI%2BTE06FHzYwgAfdHN2av9YwIhAJpLez%2BaEE4I%2FlZZYHSi%2FA8D4YMArdj0CIhY\
  nT0o0zzVKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwvIxqwn\
  bcqzafr0BMq3AO%2BKqmP%2Fq9%2F5F70qeSHNXQgeHa2SghARyHs%2FhIssqFPpfGdQe%2BrSRhD\
  HvPfvgXYoI9E5IyBLzba7EesL9BUmJjJy24Eha77Bkfbojl1HJb5BmlkMsDYS44R01FaMJLxhhrF6\
  FPtWEO1viE6U7NQchgzvgf4vvKAti2hHCsLy2OC4nAMEmjkzT9VeLRhc2n2HIhb3ltSEEy%2FZaVe\
  1fcvxCFNV2zhH%2B5m1%2BLr4616XmqRDxObGF3%2B%2Fn0VkPE1piTYRkwnbnyCRhhOhf3RA1RZk\
  Bi9fdpSfaqgug7yXY7I8jKQxzx9RLyhquEoLRnatbGN3vRobLLf5H0KcH5lwVDy%2FshWF2PCSytb\
  aH8HMUbTVu%2BmxfL66v7g760cOtZNqfs%2B92SeegWHHoqxO7DmAEkTRu4zsZgbrJCGktRh4ykFN\
  kqIYfo4oATJlIE%2BIR8daxxX8%2BpjiYk%2FRNlX7m3LxafdIOBxmvcdMgf3GMPyRRyUpwWkBbpW\
  tUL3oD9OZ8coPA2j3sV3GejdeiZKQYvrtbAm9gTwdQKzAe22WWFUxPk1MxTqkWmglULdQJIbvF%2B\
  H6XX6We%2FKayoRwqvDJaFAsrlrtfRi8xHZfJ3h5cFbCTvgPyBAYpPuE%2Fn%2BYFYXMRzMJDCFiL\
  G9BjqkAXB7VbpuhWyJoNGfHhYPrytp47EEDtsdv7OUbu93vXnhfFZjPB245lqx6ZbeVbBOV8z0qtu\
  HKjiYcg%2FlipkNvGX2OZnOoDyOpl%2FxICUgDzNj31Pkbt4gjX1qa2v%2BFoTaQ7GxshRQidyL9K\
  9956d6UzyLotYi%2Ff1xI34gQJ6WmbTkRuy7PuA6xxBBQuN1BSUsUN%2FzcUEljTZ%2BktfLkGGgN\
  TYdddKI&X-Amz-Signature=7a2a19eaef64a079cc484a7506b0deaf7edd469de49938debb861\
  7d3e0888bde&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZVBBB44L%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T082902Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHM\
        EUCIQDG%2FeRLMELfwsxSn41r47I69ubLRuovtb1aa%2BFMUl6BWwIgTpt8k5YR7uE%2Fn%\
        2FV5cZtRdpDfffXbb%2BwlcnylYM3TYx4qiAQI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FA\
        RAAGgw2Mzc0MjMxODM4MDUiDDjqI1ESDdWHWq9cdyrcA1zcACtsimSmSfhQoc1IEfLW9Y21\
        4QRxlV9B87H1yeEE5FH3ME8jabZ0d4eYD2e1a%2BN7upQ80XAw8eYFlNFL3a6ijtxl6ngfA\
        Yqse6he292vzRDU3FcYYz8lt9mSmoPxHFKWcjrMkQWSitYdp5veIOxt6h2jGAFddHEN9MHX\
        jxfMH8cHc%2FCRcDa0o3i3LF9hzku7BlbwqsYz%2FuKku%2BfdZPbrb2ZF11STE1Ee0FbhQ\
        xZQsHvWICHmuqT0J0gaybCnXWi10jH%2FKEcX7f6aYmtgjcLCcLmiSwb62jb76VoSNpaN2A\
        3QaTJ%2F4ZehtgghJPqf%2Ft3CCczeIxC7VwaUQmU2%2Bi4dl2G3BfyM%2BpeeNDSRnlt10\
        oC2SBwzJODa417F%2B8X%2F9gWa0c3oeqdTP%2Fz1AD24SHj4GKvyD3Rys8cpyPwysTQYWt\
        Ahe9%2By5z5%2FScbdSvMujaMbd816LXdS2rExKiWk8VzP8wIiqtEJFBq2MX0yZjzyIQ2NE\
        p2wvfQe1vO4cUM93%2Fr5LDjeTMcKN3wLLrb0EOdD4W4OWUKwSE6XiL89bM3%2B%2B59wEu\
        PxtV6CFWf1qR6orND%2FBeZpdbne5djbXz8IAN32OK3kMCTin8e0JDr49tUUEpBa%2F0yA7\
        24tD4zsMNyRsb0GOqUBFynb27RegY3CDMfjG3YW5zX6FlXBSsPB%2B8eZFFfrI%2F26qWHa\
        mYk8DwSnxVXxg8FWfgtM8Oh0FqE7rZ0P3SLpzpal6tievHjg%2FzNJ7DvQ0W5VJRn2fzuR2\
        pxOTS6K3K5X3pdt0cqTFSjjt3YbE2fjoQm%2BrK%2BHzuJh3OlEywHL7CxaHEkU2lohteQ0\
        %2BofGwfAw%2FGtebu3fqNC1KmX7d2EBcma37Hcz&X-Amz-Signature=6930c8c9f0c1dd\
        57537b9666e41adf1de328476b154d5abf1645bced7ca7589f&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-12T09:29:02.299Z"
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
UPDATE_TIME: "2025-02-12T08:30:45.866Z"
EXPIRY_TIME: "2025-02-12T09:30:33.041Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=fd3e6a26a85b90b5d2bd1cf3cd0c7ddf05a3024c8e44e7047c06142786234ae3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=4335d0c19c9f527648a0035f3df3986d0c59f694b29f24dcfeda6eb0ead3c0be&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=7914f837a8d4930513eddb6bcb8a7f0bee167a163d99750fc3c904c3c950d417&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=33947a483d7fe08053ae8cb319a1280b2777c16e52295cd053d4071ef9884a6e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=8d0cd5196c6c1e76ab5e5c51728012f7c2a47cd1016b8f966941308eab719e57&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WZLHCTIJ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083034Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHnY4aGyjhPneR%2Bp2jrdP8rX5EtW7vucPvlxl1%2BVwacnAiANQfOMVTdLGZVcfeaA3Jf0iqyrN4TDXrdO%2BZ2TMkGsaiqIBAjo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM09rT7hMXQSHk1dDAKtwDovPTio7N6lK%2FcUe%2BXM0omtBKDtU18yh9dpXdSD1P%2B2JNrtXAOjO9Vg3ZO1qoJituLYtMaBZOBH9v8c%2BBkceVrKixiaMggqhbJyP4SPFuedi72gLrkeOSkhErUTBuVx%2FFAh%2FYM9KMb3eIo%2FkeO1MuOlKE%2FoY29xzzwvkPo%2FFDrPB5lAwMED1qIhI73zUlonGGFy3mvtF7vWzglktXf0nDsaqPnZBLygJSAl%2FGyaao0SbVEoBSm1vUf0z4iomeEKTuYmgNtFbLfcO%2FPbVFWspbrsfyBhveoQGSw4vO%2F3TaiNTCaKvCaVs%2FW3jNB7aFJSelPCT9L3cKay6KZ7NnQk064wbrmtfuSK6CgH1%2BbcppCwPZbuj53GTJlEIbfLclRQ6q3Eds439rysRV5q7A2Sr2Dt5FXNZxx%2BS1pix%2Ba6jCJOuaky68WtPalztpXt18%2BjwZsUttQIxL5P1jwhUH%2B5qaFW7ic7uBkxTvI85S8Z2A5DStCPVi3NVfhSm3x3PZ33JHHkCfokP6IJ5ZEO4oUF2IMuZzdYDPntd8Jf5YsawW%2Bdip3JkfgdXctVbFtX4aeMcOkg7MW0VzUobE1%2FOSIcFFwE4UzLVzYb9iHPomUl8Hvndpij5vVmin7ezGgRMw3I6xvQY6pgFM%2Fv1BjUS%2FEurJKiChoA9xbvbFOEdEDuPomaLkYemyc3trpyFO%2BVqzxcM8f5rE7j094jwog%2BDCDvbHGqjVnmOLYPCwVcfH7wyxzuudTbv%2F3oBhOS%2BrvP22C1ZWwMDgWF%2FO%2B4VvnK%2Ble2Duc3FRJjM8BK2Zcy341EGG5OLZD1nvedHuC%2Bqu5RKpbv5UpHlsutLC%2BUM%2FfS9HplhbdGEstEL6nCApiZyJ&X-Amz-Signature=cd80552911a724981d098bdec0ff7967c682756c30ac746ce13bb6c33f69e750&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SMBYEILK%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083036Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA9V%2B4%2BTNGWk6p42qX6%2Bu%2FHKxJ7wzGTqC6eXvVCAEPjBAiBzK4GVKkcNJQ4sLpWRorsvM8Xfehitmu5enz0eIHWtYCqIBAjo%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMzxS9%2FN%2FLyBCZmadDKtwDJwWLn11anYxccivNK%2FdcONDeJ6k2JWxyizsFkGRehMfdbEWyQCrvBtnf9nqm64ipEOHlGB9GF1FPtl3erdRq8oCEeeNrNgl3DmMxPkJiU0tY5rxD3kqsGcUDtNbdtA9cgc0HvgpgB1AKg24q7P7EZ8yOGP2r1GldEF7XD4g%2ByS5UV%2F%2B0sw0aFH%2FivNA4uk93ZHS3h%2FoBznEmYNr81pZf4OZEDdZG6aagTbPLaj5wfHQtsS%2FJzKUN%2B%2FWmaYs7ks6KVuXUNQwcIrUUKwjcIkW5b3P2h%2BPPfLmNGkNlzAWQC2Fl%2F4W%2BfBssigNfQRiTcoznjsuqIWc5klUthuyUX8BkdcyCuluGEy62bp1lQIcSg%2FPu7eBH4WmtHDcXyuZrQOD%2BgOzKZacvAYKKSp9Mu3PDMqJYs0H1m2yOS7lRME7%2BU836xGo3p9D1kb3turEY0sJ%2FGoeBhq75yKzOVAaBNNeWanI9T5KtIhCmeqcry7fYJrvvKlAHG7rGqgkKmk3DOIKgHwaksj3gCvJVdTzmgoQzZIxQRNfdVpSZJw1i1sJn7bDIw%2FqSMl7qNQwGglxJxQiO4WZWPottGKaU%2FZFxF1vpmsZtEaHwxZsoa%2FfujIxIvBP9e1kY7rCh5Ef73Lcwz4yxvQY6pgHYnaN5vTTWdqEr6IRGeEkiT7UCgseVWJCK79hMsf6OJh6%2Bx4nQLyehDPAm2n%2Bg8TE1L6iSL8NWe%2Bk9K3w58oNc7lpS3pBIuqMa2vETolECbW050R9iGb%2FQ03E%2FDVRUDITlQobv%2BOS6K4%2BCKfFQJL4QBlOheRLsRFxPUUNcb7yUWVM%2B2aeG3c94hORWuigdfmLgJhqEO1AL5SKtTYtHKsIWKmG6gI4M&X-Amz-Signature=3dcdc398b3975d71b7d89a6efb63c7c3715159bfdc9bfcee18f0dae226a890e7&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=33db4cd3d54dc8e382e229ba117799fb729fd4be1604f90c5c4b9cf4ac57aa25&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=80fa466f9ac1fa1100221148d36ed7a9293c3658640df83fb11fd07e0d04b53f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664CTID5OE%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T083033Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDWyhtGmKezAjDd7OwOq1uqEnKrk6OuqmCv%2BtnfwFa72wIhAOCpV5y1WKpxdJ2zxma5TeMLqxirK%2BidLezwdZEtLzOuKogECOj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgznTDbIjurbBialF7kq3AMuf7PgO3aQaVUroIlsn1ocpOvo1Zi7gtPNbYfbJsNz7Su28doyOXaOKR%2FLc%2BGmJ5sj1Tw6zCpp9l7JjpdIbvK17iaUW3HYtjAJJH7gh9M86cIdsnsyyZYpOmH%2BKRpdQBh%2Bi0sX5weQgvBwr7vERSqHD4Fae1%2FI%2F0yUH%2FnLKgiuwKJTI7J3eiXN2yUeEKckh%2BvudBqTfDopeouWpl6Y6c2pExLafQzhO8ejtVxWgqhfINvUXQHRkMXBh7Okd9Thk3pJzeFjgpU91RzmppH7%2F0MPBQesCxIBcGpS%2FmmVZuaynX6QUzGC2GQNF5TDRErrGOwRv6ML%2B8oo2%2FIHwYhHgE2lMN41fJTjYbj4WTneI0aTgRfJSf0bBiVTtWyek7ewfV4LlKtjeLS%2B1TIFb9K2%2BUYzV5SgXIxHWKeed94V5XJYRynApod5ldL%2B0wQD4x2RhxgNzXLkxowQxq7MFFvfR8M06pXDXHNtwc36E0EJbDtxuPiGUidrLxLrMPIk8XylzAiUfDZK7yHmDkr%2BaI7zsF%2B2mb1ij59N3oJA%2B6a79ffOxEWyqUHled7bvVzeAh0S5DLpgngtnRo%2Fki%2Bn%2BMvkCKKddJG3LERRw5Jlzf37Tm72g9S%2FqRcgECJmv1VavzDdirG9BjqkAfLnY12ZmpdPpcsBnpivp4S5Rmwc4unyePhpADsWCoqZJnn%2BmRIOokm26vmIhRrVFT%2BtIRkByYzxwnlK%2BUaddhtjWImsxzBVJhMHk9Ddsrn9VLmsmAiYCY9sTnwkIQyJm%2Fz9H7EFJleG%2BNari43QVW8pY4e5ZxXsrMzWXIa7WBTHDLhDMgIzg8LcrnNL4QVyn4vNaAYrf3JQJprI0mONk3zKl8wm&X-Amz-Signature=7cf637ba22789785e4155159e2673d170521163a98ac9b5e6132f9deb902718f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

