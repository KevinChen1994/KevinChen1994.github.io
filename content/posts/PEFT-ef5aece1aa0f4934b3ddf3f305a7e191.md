---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466U4BMKZ67%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T102621Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIE%2FBySjP%2FtFfNHs\
  NfcFmZ5Fuw8Xsd80IyMq%2BlrbG%2FSlAAiAnn4bipxG%2Buxi0KA8VO6PJeg4fPCTDEfdHvcxrNq\
  JPGyqIBAi7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMSFF7nBqWW1M\
  JlQfZKtwDABFvIwS5uARIORCt5ifnG%2FvsVSD6U6fmq6g5Aj%2FoKDa6VIAtmzunKoQ0dASVRkMW\
  eSjiG24RlG4ycvhferLDBcyNOJztxj0pa4gSHt5m4%2FZnwWx08ynyGqfbRlj4gkeWCBQFUPhG%2B\
  5PUoxim8mz0p%2B4jcrov9bYsHmxqbhhkcq5Gb3V%2FxElGV3zDa6ns3%2BBEVkJaa4ICyNTcKJ7X\
  MYP%2Bh7fz5QtKVct9B9YAl1zmPC9fsasay9MavcRLeMHyOuAbAQ3qGWgZB5WNyYuL88DvwE1RZW2\
  xjNE8ncSTM5JNcTD1fi4Bjd2ATcpdJebWVXV9yKr43qCdFEznSCfB7esPX77mx4lJLBqptI6bQ%2B\
  BXaqdsxlFkDf8wOS4JJP7RjjUcg%2FuK13NU2LLGsVeZhcyhdZYpfn0LDZAPbRMGw9NovwZ6av8nT\
  3SutwiWu%2Fb%2BQjDYOwv0WdtNWxWgbHczG4Q1LKmvt2nwU9Qmdht36H%2B5zPDRTgyO6uSkeyrU\
  cMs5iCLFTLPJnhXgDZKQe8eUhqy%2BbMRv4KawRz9izZsjW6HVSC2184kevC%2BRcdjhutgAHfIru\
  7jw57qOdcOdu0WdUdXXH%2FQMUAmOC90%2FLZVrtBKTqOyBvVma9YEe5tL%2BAF8whZKnvQY6pgEf\
  cJJy8TZ6k2wyqHtCOZre%2B3n%2BYbN8mS7a7hXkEzfSdxIMTPzh0H1rQONie4Wo7AE3B9UdaOCua\
  0VULaAhcpK3LxDoDBj96mzUs4sRG6VAPeWlbDFkZuxwz0bx%2FDqrRQWMogmfjyHpFptRfb5BOZfj\
  FDQBU%2B3LnPVa8KfKtvsNvJziQeDLFCDfVRr7yGqPsCZywkeD0Wrf%2BIDEMSbZwrDLLVvegou2&\
  X-Amz-Signature=a2a840665a8d9190eb52a4a3697a581683b1a5cc0fad242e21d9bf98478e5\
  cdf&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TXLRSMC7%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T102517Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIC%2Bp50%2Bp949AnverTrsX%2BSrKZJ8DyucBCujHFHGYp%2BFpAiBWPM6yNCfm93Cpbn\
        KObSU2oc6BPVDWT%2F7ucnGsB4G1CSqIBAi7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAA\
        aDDYzNzQyMzE4MzgwNSIMulH%2FqyBq%2F8hjLaCjKtwDSe5AGU2%2FjWNVo52HwZ98VSTs\
        0FEBYVDX66SX4lBkckPmP7CjNLV62E9nrVLPzPMFoW6uzhgpLkdIG%2BbDi7sBc7khg73I8\
        57ZNpYd5olv8%2BWGQ%2Bu%2BPVgavRWN7C3m0eZs4zJJRkDV6c7Dxsv7N2kVJpK4JSKS36\
        B2DRrn84aeViV%2FpehEQSuy8%2BETrRwufmoNQOQuVj2xEAqhCIB%2B%2FSDVKN9HWReKN\
        x2M59kIQ8cfw5LbAbAsxL%2Bhi%2BYPXdr7jsAKuYl4eqbeTpyS5N4rbYS1Xd4sdtJgCqVW\
        zYsFP3GWOBYN3sZrTXMQrAOae9zztlv8XnLnf8uVL28A6Z4mDeZXsmX%2FiXYwZYkDs0Edr\
        PmTqNJUJWLVoVlE4vN4LEf73nrSfIkOnunyUSMUVjrFbPXJ1F%2FL9IB11QfoQ085jWwmga\
        HTDuOYZImQWq349JUjaTtwFEzzfrLhGnKToAJFntOUlHhUG8cWAC8IQKldex6JH409gRaKs\
        6wagVkpE0359nubswZ5u0IfYzhhQIBqMYsa802Iko6kT2qH4Al7q%2FblLPcB8eriq4%2B0\
        ALU8Gn8t1MH0%2BiuGDFMobsOOpNeqHxfGaVSVn%2BNh%2B834ON5Vq2YIS6rHAQUcoiEQB\
        XNK%2Bdww4JKnvQY6pgECrSyw3IqZws53Q0uouTjisrcDiEnE8bdmNFCqAywNDTCxW5YYM8\
        BUNYM%2FxDboPCJnJWozuS%2Fe3d0QwwO6MT4a2GIKk61Ute0rc0jmb5%2B19I1Aw7gNe9k\
        SYkjKqTCO4MVpFkOspfYCRSPwTb2kd6h%2FjZb%2B9NY6Y4%2F064Klc75pL%2F14DUicdJ\
        QHvrCt8sdyhyi5vQm%2BgPTr5DvrMVk%2FgLnSBlrNV%2BmG&X-Amz-Signature=e1b092\
        16818ed80c70ecb03f10de70690952a07668f658f4d4c71d208197c116&X-Amz-Signed\
        Headers=host&x-id=GetObject"
      expiry_time: "2025-02-10T11:25:17.248Z"
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
UPDATE_TIME: "2025-02-10T10:26:30.746Z"
EXPIRY_TIME: "2025-02-10T11:26:17.832Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=3144c868781f6803159a47a37ac1219a32139690d0c8c4d3e4639999e10af4ec&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=ed362ba053641aa4196857f9e90c1461ca62d8d162ac6e042d096207b0d7f095&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=762f779475471f1d92dfd59c9d126c5f067bed20e24de0ba54627dd9426e4716&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=e4e48cb137e98f38222089207187ed3700c2684e90dd4b66cd2faf183881b1ac&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=aa16f02e8cca3eebeaae26ce0de14ce5df2c7152d731536387b0e6d28f2f955c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QX3EQH46%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCLNRa%2Fya%2Be%2FpNcRVN%2Fx5fVGK5K%2FL%2Bj9fUzSi69acdsVgIgPo%2BcViN3GRrBkDT%2B5jrAH%2BtGlb%2FOyzvI8JD0I%2BmL4eAqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBqP2RTKndAc0TyItircAxfIRORmPaNBEfEJGXlWVwXzKHgBuTp80j6DPmo0NYwPZjfVb4T58KKqa%2FpR2%2FAETd%2Ba6SMKAiprrm7zUt7TVxE1UvdKS7fUh41ADzm0h0NXnxNSf5M7km25L7Wj4ly12Kcd3i0VBqdKzUcbeTX1Yx9J6dgqWJ8nqyoBUb6bxLCOZlCr06sjriju6%2Fpp3r%2BG%2FoWtGNJgxM8EZy7jP3HIbSTj6m3mdZCbd6aFf4xA78SasVFXpPSa3A%2FZKgPs%2BvxMnDaOkttCdmfR%2Ba%2BdyH4jr2wGbkzQFObBJDp5L%2BsB6p3E2dL78AqI%2B5cbKZCvuBU7uKUUx3XytDSdsZdBT4ORHd9SlQFaHP5XGnN%2FDCE%2BQ9o7JOBWhXuhvmkW2KMAriM8QkcVcnT9PLZGYb5FSbHFa4zV%2B9al40VUZmF%2Fznpl6IVQi1eE4t2YdqqvZzWDqteKXj5%2FtsIL3MzFlMchuR7U6oor%2BWU6k%2BgPXqg%2BOAGFtQZQSxmzsY%2FoLYX4P4ZICfjceIblJlQZJF4LZRJWM1ZPmKsWd5SO9vttTSlMubwZ7IIP%2BQgY2Wi2R0zgzxaVAFdqKrVJ3Zs%2BzEqIJ68D4q6sdGFp8W%2BnE5Tupo0yGW1pKxJ4pQybJKRFbaQO24FKMNiSp70GOqUBWVw%2BX%2FI96z%2FfRck2nkALb0%2BKtgqrvf%2BmJW8lGWejEsHLmre7TSjobMjFH88waJJB0chzWJeJR1avdyDIUOLJrPfeNU2Ne%2Fh34tf%2BuaBLyfqXkxMx9ad58P13WVxqlZwpotaNS9V%2FKjq8hMvHdIjteh%2FtFSpwG%2B97CRpBKImxw28ePhmPUQMJHeyNusYtUcbhVVjjv65qT8jg3Pf3QlVHDb4GegHZ&X-Amz-Signature=f16cc2011c5f22507e56763e366fc101a08c55e3d2dfd67ce665cf96bdd784e7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WKDT36ZB%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIC3JGpCA1IRCKKIUppGL%2FWlXd6fxpRzMWCdFcfcnTjgRAiEAy2pl8F2PokoDNXkcI%2F8W2HFjd90dclwW%2B%2FjxxZDuIuwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO%2BWjlTmEgQq0C9UMircA6KdG9KTVFAzE1tuwOvTC4LY2JQAdYx86kRmqqLCFZLaQN%2F%2BOmHocon6HaZWgohp38cDRN82QNfsIHTaIaIoN3ejw7JiA5TdDWtw8Dl4KuJo%2BpGJReOotCqM6nPMeg78adWuIKkvIEAeTLJsaL0svErRe50thged4zEEVbZfCmlsFTBsMVJM7DmAZUAOLBgpJWjAqNx11eF0SYBaFcKAALYvn6L7kvKc8tEf2uDLeQVGxgJaBm2A4GjBGbHTCtZBHpBJTSsDAzbUZ9TjZhKWB6AtBTuGBs1FbUiLDdAkU8TU9sHl%2FZhbrLCCZVMuHZy89XCy%2BDxHdkCH8Q0SvpQQum9jgeJ0%2FJKuFlb4rjw5NT13v0%2Bq7bE7SEdHjHFzAG%2B7Pjal04%2B%2FpCWuWxpbXEPVNoHIqyLVY300SPYYxeZVn8C0FZM5C3VhNG6VaYyY1xXg4Yki1itppSB7DQnqJg1%2BR12d0QTUEjw0VL%2B7aDNsZq9jECC2lkWmK9he92u3ULC2rW82KuLQEVsJ4uBvxkVYLF68c3iLfSfkxbB8ymDUdsAOyzdhrXtn6G0SD0KNUy0MdAisx2p5Grik7GPJDKDUuefnxSl%2FVFjoUpDH1Haa6EmTmwE1QBoxXA29rBE%2FMImSp70GOqUBrPFIazFO8QbeMpfHC2mI9VNpRBumyj32HYgB4F%2BOFxL0CBTHUjs4Imv%2BgPVcJaN%2BF4v35B1JDc2rCO3YkIi6empzn5kBgtIZVLPWOLrdPpgbKJdsgmW%2F%2B4thPAR2HQSOqgBMg91F5o1aC%2FTBVsQNC4rIIbIZF3oUvAx%2Buj%2BTtCsLqCXp6NEjun%2FwWcZqyCr9MyfeEjJU1AKy%2FB2PMkrbGP2KokWr&X-Amz-Signature=152b04d2114ab1cc6cea2a0b996fafee8a16d91f264f906b2b52503971687533&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=813284f8325d14f60d8dbd07f4d4cf4e243b04a4922fa768c4340b948cf743bf&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=6798182f2ca9edfe4b9bd35eb8fa1c36b11f4f6826f06e1a30232e8510c5e9da&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLDJVVPM%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T102619Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCKpruBGpT9fLkLzo42opO%2B%2BCKqCmpGxPiM84El2MUg2gIga%2FhqGeZJspWWH9kCAMRlGfBn5Lz5p7rfre9pfXGkZlwqiAQIu%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMEmLinz%2B2IEIalT0yrcA2LO02ZqW76hYWo0zTtLY0dAKktYDG7pS7GtLSTuwoUmlpz4whqA8E%2Fh49Dnl76ARozLH9mV7sfsg2to%2BbfiVI3jz5K8eD%2BZ0Um9%2F2xupCRg00VwYYn%2BBYPPXM4MIms%2BO8pYldqmT4woaVqGtTK0sT%2BdBfFN7MvN9YlghiRJYb%2BihfcEtTh3AS8koHY1kdZym7v7BhqxiCl4ieagkghdf3jhggogh8qzXF%2BA9%2F%2BsncNpcVPNoQabAN1oDAXxG999KsScCORwRXO16y5pq3G%2BjqnvsDR9ptBz8a7tyheYsa%2BLg%2FaKMOlcedC%2FJVC0mPrun%2BQ8RYPe0IYlc0vd%2BSmg9%2B0MnVAl1wT1kgggSRUvlluOFNBCbveno70YKkzmoGHeutVpvptz52i2HIp3HWH9LMjtSazdO0rU%2BDBYZddMXFYXd8ZsFeNzfkZRDGogZMSN0O3fnxyb4tIbYz6TaLOSU8F%2Fev7dOPuvf1qVm%2BgAW1YF3X8gBSKoq%2F0Id3HYe79hK3EC0dWoYjed60aOrD7hqmW9O80ibk%2FPmbqS4Rtb7PpGoHH4Nh2UXEVw0ZSASbS%2Ftwy%2BRnforPD7q07ygeUhIPvmXgSz%2Fs1RtxJL4gQMbwfJX%2Ff%2BdwPeon6E%2FMm6MLuSp70GOqUBM8%2Fm0qzwDpIDiGVNo%2B2JUFXOya3HuHyjeBZLQlzVZrsdfBXfNHX1alDTjRVzOA1G6J8lIctBsbDpDSTE6zOzNAKCJfugwRhtwKoIIvpxuT5rhAxOckZdpnxUyBN0IXTQqnTZeDVWd6a7eajQAilWJPdZvdnuXBws3btx3itZZ8tIhOztjwXJ0FOlLpFz96AU6ToFvCkakP0R6HWehmUHgRLSGW0u&X-Amz-Signature=7e4ce27ff46713219317712f1c7d4df2defc4cf7efbaf46e3dadea858e1dab80&X-Amz-SignedHeaders=host&x-id=GetObject)


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

