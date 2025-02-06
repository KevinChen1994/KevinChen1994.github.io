---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YVGFYVI5%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T072328Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjED8aCXVzLXdlc3QtMiJGMEQCIDUnw0GzS%2FSnhqejfRrFJFdkC%2Fh0A84hKd2ZYm11wFLaAiB\
  Z6kdiZXQEG97gxAwhejmM%2BnTKQMHQB7W7d03gKPVr4Cr%2FAwhYEAAaDDYzNzQyMzE4MzgwNSIM\
  VSKLLrX%2BZUKuTQ9HKtwDtdR17XNrBIkn2G88InrEmlwuLCcv%2BnjIpa66ItH4equ74shGN%2FF\
  93yWTAHJcj0gQ4reoPXSZewvEyRvmchQaaLkQnfSLoivf7xbZCYRkp5x4B46ztrzWu163uN3uCZGR\
  1tja%2F8DXKEwFTild7CWC3jKdRZMDseco%2BmU8aG5qBbZSgV0IRPnpH%2F6B9Ve1b2wixb6QzCV\
  S5gL2W3xDLkCG52zqDB88aeRoJJ9%2FbRPM56jd1tw%2F3dy2dKyfJSPouXnQJxof90SetBvgwSAq\
  r6zBaGI2PCDRJTrU5mKBFy7RyXwWOsV0d4NLdbYw06NNTz1vtPyqdaszyVE6ubqBZuPKqSr8KTVUC\
  bMy1CW5l65FLPA20vKFeIDl5imvMX1yv9C2WdJ8%2BtQXROXXyfy1rH7JgWG803WBUGlARPwYhHq2\
  gx8TNQSdq65KyRGRDY0IAA2jy%2FVdAOVH25gLfqJQBj%2BZNYmaJcd4NyqpSc4A6bgQX%2BlW9qw\
  p5EetsaSyFhBMPURiI%2F94A%2FJVclfO9bxS3mVFX8qMq4HFQ80YbsRJe57NWznb2oSqFKudihcY\
  MWMRDU%2FJxl8S821RL7kZJ%2FOoO1Xi6LdTcvJQ%2BWFbiPViMEL9S0Z9VM0VUlsHVz3ZgaQwh7a\
  RvQY6pgG0HBAGshY%2BhQvOjvVvLOs2yj7ei4Hm%2BoHKSZlEHWIJPBMn%2BzIZu4uzam%2FKm89G\
  VAWte9WbhgHRe76T4RtTdNfytXmToM2pUcEF4dkyhS5rVqRoRSEV5dLCiB%2BErsj061E%2BXyPHz\
  19rzpAcNU8TpxJu26VHyGfOEeHjcQCNqGj0eBzOKi%2BBPSkULgYII%2BTFs8tgsEmXEluiX27pas\
  8rCPGPdBi%2FgQXr&X-Amz-Signature=13ec55b6e7d518b93798126f59212928d4e7014efc41\
  56141e9399d72a9e2dd7&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TA2HRXNO%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T072159Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIGcwZQOzRFYBImT5ptHvAUJQzT2J3Ne\
        KqLk05CSuTihCAiEAkf7PB0LZ3Q3iYjUhL0uH8l9Lsht31cjfYOsY1wMr71sq%2FwMIWBAA\
        Ggw2Mzc0MjMxODM4MDUiDBZIvevl6ugS%2BakxhyrcAyWeT%2BFP7qCz%2F27a292RMIhaO\
        XkufCqFexU9t%2BEZhZJperHEjqpvNbzf9sqZhkVbhEaDdqpeXY8ZyfZSCOSsdYzT2xNsTL\
        hnH78zuKxMWpi7aCZs2WRJ1f6rjNvi6tjDaeGKOf3o5e1aoq79onhPq%2FKNwtDZzPg%2FM\
        2SLrhTRaZIXVuKOVoh8q%2Fq%2B%2BFpt6KC6jj3VO30fQovpFAzN3SRV2J8Z9%2BT172m6\
        xftGfA7hn%2FNlmwXoafm%2FQEZvOnt3bn0leGD2RR%2FopcKmpXsPe1k1STqXcCEprM6r9\
        A9wBuIqJaDK5q1N91Y4M9LOoyv2u7IL%2FFXhRKiUModJ6BhZ04jrAftHqFULEVMs2KnOjf\
        JnG27%2BQpT3r%2BDzcUGKKdG%2FX2QnVKxTpnVoOUNyRU8DSr4DERljjhEo6OemuvgEM4q\
        hPGfNqF%2F1nwtF%2Bm6LIc1Cjt42Jxrw1UPwT4CQidpLFlJsIG2aV7Q2vi3YZ2lwYkLqXy\
        Pf%2BQ%2BVYfmmYKWVi0b7euxDm%2Fj%2F2P2BMYC6PZAZWkzav4Lq3x4k3EBDyxzXS1jky\
        Xe5PSDyotU8EsAuFNTDR6ewzR%2BUF7XDYG4KccYesEeLi%2F4V0vFBXKdSHB%2BXmI29eu\
        i7Cj4Hpr9hFZ2idKEkMKa2kb0GOqUB1rdTj40lKyLD1c9CbXRnegJNyrE6RPqlmTubXSZrZ\
        d7CvzPjkN7l5yxv6X4jlwm4JKPCpREE5z8wD7k2Ki6RJfDdwOHkaMBm2yHjtZvK7SpdE1ob\
        vMfLoafl5VTHU5AWYclukGPtuDq2XmTIsMDLnwpL0cLUnhayZBa%2FOurSrx4ccOSSMICi2\
        3oa4u4eVjGLaHX5hKJjDwdWc3oO3LfCAyUsVjfW&X-Amz-Signature=a3da84a5c057d7b\
        2219dee878d1cb17f076c41a7fe2f780030421c12d04bb08e&X-Amz-SignedHeaders=h\
        ost&x-id=GetObject"
      expiry_time: "2025-02-06T08:21:59.012Z"
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
UPDATE_TIME: "2025-02-06T07:23:35.893Z"
EXPIRY_TIME: "2025-02-06T08:23:25.071Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=942351d372adefcf26c16fb798dd4e0c87ab507afd09f533944eb99277d98d6f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=1c50ba9b2db59c0b6f9c3b6dc61d8047f7d1962c9c5bd65b0c5593b478f7fe95&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=03873b63168765ac3d137ca0daaf968588154349b15245ca67ed2f7c4442cbb9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=484fe845cd5e505040258ac138b61ed3ae987b57effebe28811c9791cba30d8c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=95c7ef89af6f334a6dcc11275fb304e3ce56f334886e4c84823b6fd8ea2b7b3e&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666TNK6TWZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072326Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCi7H3qn9QfBe12evLbxCVIhXurLG8QDtriGIZPcnm%2BUwIgPEWyqvapav0ijBmOdfpcPwNmwFOFUgLf1vazIqpQAI8q%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDJ34eyzT4pdCwphyGircA5EXhxVi%2FSX%2FvE54uF%2ByNi053SRVetzGqIVKOamTfkiFRPNim%2BA6XFLLwYXeBYfOBI8MKtjfzsTfXA%2Fn6yRQfxUrJQtTIBRFnQKo0aw2HyJ4cGzjLGad2W8lUNBIvrAKJMpl1OLqJdX%2BGgFu%2BPQNIe8DxHJyfD9vaAr2%2BsQu2M6vIvBQofGsnupGrnASLy7QXTCqjfnw0JjLKquLQv00bUjw1OeAu0d5mmeiNnui7IFu%2F3YoUUPC6OwYPseqppUVgp9Y5gcjIza%2FFgba9awHiZfPTucEvkQatIJMzFNF3BCbivar%2FOzkcwOqMNnTLWn2H6QS%2FiRYRf9xtqYKudF6NKAnyg3q4LjqBbVvM3qc38Qm3mpNq2Q3aa4lY3UH1aojsiU13oUaV%2FfCGzQ0AvDP%2BSC8VFeLxZqNOJxFCc%2BH%2B1PuA2rVlrHYNPPUryGZeY4GwmOShwF9Zx%2F7jOAv4FZ7vJ7r32KAGLtXXBJsCuqgD8iVIGIIyu2rrhdAZALGGBzuJWivLkRHgsP5nU0jdIMU3sgVe86wxMaMCR7MHnUmSxOuBoNiUjgzR8bWUu8SWStyj2Nva5mSpMnXu0Yi%2FgzuHPK%2Fjkio8o6IAdnZYXIjRjEY5bEcK15W9Ny%2Fpt3SMMm2kb0GOqUBS3l09%2FjRm6TP1WFCTTa5ErQ9pPnnoK2zh3V6nR8ylucuPtjgFWKrMShmYmx0SoJfakYYr19zjjPY%2Fn6i59h5YiG%2FQOjOzF8Gs3jn8%2FhyjX8hmdqfztASAGw2DRQdPwrNRenH4LtsjZf%2FC6dV7XceP%2FERFyFNPdzWjgHx%2F%2BXIOjyxQc3D%2Bbw0NHytXpsWz%2BlN%2FudaYikK0sDyUq57A7nCDusTxmxk&X-Amz-Signature=37259fe983ed77bc4f335caf50c845ec94bb61a31d3df45e1123290a77d6c281&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XGRGXRRV%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072328Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCyejw9MHSRVadWWnVr15u7ZFAjkm1zNktS0BkVCVSV%2BwIgVplZ8TPhTYBKnwN%2B44qqQ5%2FekxnsdsuC9HwTG%2BYVYxgq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDCqKDgaBihw4hT%2BLoyrcA7uPGJytCEFvACF25n98FD4Mq9XPF7tl%2Fsvn7KfsDXsTlLJrcfO49wCMM3SDLmg5K%2FRVN2siwkT9DOXkxnhPOUogog2hLJR8m%2BIM82Ad5VNfuY5S1fRJ%2BMHFOcCpQbfKCBSkWQAPT6OkNe1sTuuCTWCgtnxlTP9DfTnsZeYc%2B16JHYIlqYySYviZeub7lCiIurRPz1pmqEp7e%2BuiaDQE4E45B7NPMLHdv2YSbcFRZCF0H1e9AgMEIYLFBJwWxI6ee3ha7PduRSIGUnsGfP1%2BxEHCU3vAD77BwsctMPjsV1N%2BZ%2BhYkSp1MGs7hM8l0TQFIYu%2Bcqq92yY7%2BMqnDnAWuCDBNG%2B7Esk4QzWGPqE1DTdeIYZJg5eS664FWgrnNOhrx%2FF6tdaylzkql2%2BSJDgOGzfwY6a8c%2BXOhEr%2FPpmTBvybQPVR2MqWXs2%2BniyQpxy2yMx7e59XPVMeYiwEO%2FIHoMetg1WYYGvDcykr%2BymaVVbd5bKe7m4ZQViO03GvXiZWwYNe9TeTQM0ujqY%2BW4q2OP1nzX%2BcWzQ%2Fha42UhEdZw3IfG%2FTaxL7nBGlF7DcN9MFzxBIo%2Fxa8kHM8X1YzCnRylfnhCZ6mFfWsHGg3BZuxRJjrdqcU9mFOauBHuSAMKa2kb0GOqUBhRVGM1RckNf7noSevzlVTKGD1I4kfZqk6%2FiiwwhrflfJMMpjCDr%2BrA6Rkc1xpQrfQ%2Bhs10CjP479NshdeufIeGjx3ICzNupbNB2Y21WIB4UTX6onoEWCxV15LZyIvAYdpRSd1puQnIeqVcDJVWkemhR9Svvz28cHFgqF%2FqfqPTPZ2EpZGyn9nBAf0gE6HEvOVbnhKYW8BtHsD8M0CRRhAXJCu2VT&X-Amz-Signature=8e70ce091db97f4398d752012ed40e55b1c7908b95f8aa523a69be89beee79bb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=b501a9f95ce768f2e10d00c4bd820bacd1b589d50f358539c72ff2bcb62424b6&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=7be222e26e56c855ca33c869fb702bedd0e088e3c5c6b029e6cec64fbf0fdfb8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSGJYZY7%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T072325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCWJzLFIaLRuEM5qAjfFJmFNbyBCQlSBM%2BjL2Nkwz9NQwIgLt2iH4t8ORiL%2BwxsG8iPof65YtmvRQPDJrXpv2aJN%2FMq%2FwMIWBAAGgw2Mzc0MjMxODM4MDUiDC%2FAFjfif2uAwgkkcCrcA41dtt%2B2KubBkj3KAFSQKcMsImXRkidQXGVZENvoQhaogU6fiP%2FNZhyKO208bQ6vCUNwHx2ZM%2F4tHmQhwMU73u4CDcT0jcohsV07cni7wrEGHCrzQOtGZdej3hxaGsC529Ebvdqm3rF20VGKowWKzUqYLeDBFzGprfBtUQgjauor6kUqB%2B3WRMNXAwDwkkXC7CmkOth3nLH0EW2R%2FXtSGYyP1jlrZmU8sfxa8DUSM%2Fp%2B2xyz3fp%2FYU6rjzYzsWI6PQBFcawYBPZaWwxefbLBAKBpp0H8%2FIITDif6ev%2F059f8sqVcCosmq57iZnojy2H0A4TQohHX5OvkxEInIWm7E6qq84VJlmsrKFEHu94sj%2Fo7YDM12k1L%2FcGfxmlivD%2FXopVfCCg6w%2BIf5Q2BjanSI8jxUdnH2KapuAnkG34YUP%2Fdo0DUXh87k0I%2F6a%2F7GJ8zI6Xbuk410BTiqudjKSyIrnxVqVMSM3mxvCMvH1iQYMMLRH0w4ypVF1niyTEljESIFkHDwHlQpL6vNJcdnCPCKCFzjRqAqcdsnJdATRip2V7epHmKKBWZi3etE8Zuh6tJqa8N%2FS1t3%2FM%2FkCu3nVAvUD5nv3IT948ffc%2BB63Ly%2Bbm4CdOnNJ8XsMyJhT0IMMm2kb0GOqUBT7X7D8%2F84BItcxwJ7e9g0mdxzJpds74C1NNAZXnUeRxcK9ZPjCFAMsdFeTk8fGz2V9uwNSpiWoDOFk3viSYmx8KzVxv4Nh7E3CqUyE3HP2d3ANyiVNbK2eQyZJTmNrw16Lefa78zKFIcKYXKGoXyaszxYA0jtHlAwVTsMr0pFG9k2aM0H6Rplcn%2FStD8WsNK6tc0EC4big%2BNBu%2BvqdKXaZtk6pXH&X-Amz-Signature=4f292d55e2f820dde0a2f4126caa4d9146bc9a1c1f0deea8bf6fcd2d4a231906&X-Amz-SignedHeaders=host&x-id=GetObject)


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

