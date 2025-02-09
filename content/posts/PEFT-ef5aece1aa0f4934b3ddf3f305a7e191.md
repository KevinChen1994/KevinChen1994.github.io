---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RMNBMRQD%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T102330Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGI99FeyVGhl%2FnzBE\
  4Q%2BmYZrhV216wUPuUcjtd%2Fz631oAiBuDTNIF6wgIGjIo9Boxwgtj5emw9G495EC9GmlSyD%2F\
  liqIBAii%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMMUdCMQdAi%2Fl\
  7JiDXKtwDCIL3x1bCme9%2F4uQi10fw8UGkly%2FBvXISPcwGVuZXzk0epbthvgb6qkhAGhZjnc92\
  WZggcpnMNf96dfI7X6VBnwp6bEO9y9YA6kN9m5caKkqEUr96KOFy%2BK42i4db8IoMQbWyjSQUqa2\
  ABNdg2FWAkkDjlFLlIHmfLegwON1192TsFnUU6UnR68JMXRMJb9GkzEGqBGNi65Fg4LFiMJ8NXmgn\
  %2FSRqK85mplq1yjMEfdbN7PBZI6HRz6Nj%2BNdw64t%2B%2BZnivk%2BrUOVIKLBbS9IW4iKHNPU\
  60hLw0q2hBHkf6FTcWEyZ7uqo31%2FIK5%2FBkwvYwqCOSQBjMIis45UcpNEEqQEKApqyOxr%2Ff0\
  K0ZCcf1FyTx%2BvZC8tBmVhg4ptFpc9HsjoE5XID99VTVxO1%2FCiyJPdnc%2BNLUejg0CZ%2Bu9c\
  UuHbV0aPmxbDZM6eoS2N8eidOI0IwzqtEiqhVXu2BZDenyWmIvnoiBQkLErGDFOb5jNh1HLV91BZb\
  wrC%2BmU5u968rsDu4qMy2MLFWpVjdpWm43VmGAopbGVTmDjLzcXxlcFj5a740UsInbeodgvX658V\
  HogDbsxOFZaOF7k6GFoDl9cwUUWMFmUp8dnqa8r1BffLtUShxABrXpUREuv4wguShvQY6pgG4OWcy\
  lPg5m1UqYpUoUfkmc7OgQvMEnBQ%2B4HikWNTBUD2r%2FQoDmH3Edy0ge7rnxEl6aHsW%2BFNZI1f\
  EInJ%2FuQUSP0MOAc1UO%2Ff%2Fgzr4PzTrRhykAqwRlctGrOzFDQgFNaHoojlyRug%2BVxdM3I7R\
  HID43OSaiLDiQ9UcIM8JpfqTIhNtcEmt5tGVm0Ctd7ZWXdAz%2F%2BvFW64aRrQXL%2BY2zYnjKLg\
  TFqrM&X-Amz-Signature=b62d4e3d6a401b18fe0462ac9710bbf591ded3e0b16e74348107236\
  1424ca6a8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SJFE5MCC%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T102217Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDII3vEWst92BuvGflsu%2BfdxGVqNVbKgupXCQKGig9oFwIgC%2FLS8PrC0ROk5QMwFN\
        ztnO7nvFI%2FGJI7lQlGtDtbnbwqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDK0iMetvNY1H9RYKsyrcA9YlfCk%2F1D6AWDJBz4wB%2Frk7Ni1sPH\
        7e40K9ZzsUtNZkhYO5p9Yh3rQRqfLzmo4rWvfc095hFDVL43bjD1xQL6N%2BLK9KFo6eHm7\
        9Xbx%2FN9qBUosHlatpCHMOY2Od%2FvJQ9deeQXdBL9YMKc0JuuAeG3UE%2FXp1cK2ExDC0\
        nJAW3St%2FIVZl8kFLlYyouBvyazSmwrl%2BoaeqF2%2FReTadnjRVdGZz025%2FTCgux7z\
        %2FS6XQaG%2Fx53VuUI6FE8%2FqxelPAelaYLD8TTLut50tzH2heTEyI%2Bj%2Fo65SLFoc\
        ntQMQkObsGRx3hCqxyOoptq%2Fvd%2BL3MfcXsb7uhsGgQ6S5Ijy82fV2%2FFOn%2Blxjoy\
        NjKAwwVO1D3iGro2kqLyZnIHB%2FS8dyMAFvaKnZZGEOvXzfzVJnTuPsTFqVDtEOw2oCwJi\
        0awRAH3KT4aHEI5EVn4FS%2BwfpsNfH0zEoWmzNOKzRYgqNxR3Ski1eNkhCcGLywhsM1hFb\
        JxqP3rbq1Y8vq5jiNpcmETMzfUuQ%2BZ0%2BcPQf4EzQmPzqvzlD7IOjjxn12%2Be6QFagW\
        sChzh2FBgdFSoNPZxGlH1fijJg%2B%2BCvfBVMUxHNYg7NVL6IjlWJEvQ1TbYXpIAP1czXe\
        I3yvHPVh4ZeYuuZMOnkob0GOqUBqowomffoA4cnHIXOiEXktvDjV4IKa6CwVTdQcUy6Hku%\
        2BL1KJJiBVzGUcMaMWEivVpDjFBPXf0kB7tuu5KVPROr16YavbWVrs5ce6YPkYbYwDsErTI\
        lpbpzAkf7R3Uh6jXC%2BJmwIWK9oELfOQyIImW%2B1HW1IcLE0zxKOgw26YZ1ZePrEb7fjn\
        CXr0RkL6vnt%2F5vpfqJMx4xCWgz%2BU5hQGLj%2B8PpN2&X-Amz-Signature=09098dff\
        750d7bbdad569d16934f90e5f0e95f3e9a103bb709222d7807b9bec0&X-Amz-SignedHe\
        aders=host&x-id=GetObject"
      expiry_time: "2025-02-09T11:22:17.593Z"
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
UPDATE_TIME: "2025-02-09T10:23:34.626Z"
EXPIRY_TIME: "2025-02-09T11:23:26.800Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=991c34aef2dd8e0c34348e20df4bd7cb3dddacc35423a63e33d940fc029ebaac&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=456806de57b80e77bc83d6b804c14e7b1c43a643e88feede40e932d989426d37&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=1c83613c9addc9f1dc83e60b6753ccdfc1e3448809af9bcae002d78a201dab32&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=5d152a7dea14996be9bc73035ae5ca235124bdbe0e0e3fe03aa944000c61f7e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=57422a0ac201319eac5bb51ce8e33ff1a9cb7631013032cb9d82b5e5cc0089fa&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SEV7EJ7H%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102328Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIENyVDvEoxqygNnuznpVvHIAf2h1FcEU9AFZcGJeospRAiEAyPgpCuEYvD8bFaXzebxsEgwOtjx6Sgn6%2Bd5Osz9V0VIqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFENEZ5%2Fdsw6snaa6CrcA%2B58sxExCWdj3QNdt5UrA%2Baxx67M1Igyx9ZmWM0rGxbsgwKYZ%2FYJCMdbyKpeDg0DmEetNaazQV%2FVCYkee6XP74OfMGwikNYs5yL%2Fb460JmnXUEGFy99E8aIFHNQgsxAxBsHaQHmPC%2B0xwxIu9MZ%2BqtSywJhhhOHpell6AkRgfAQaBf2JafPAzWJG6msVS5okSLREUjgDeCkhcBqbnPKJQ6m6oWuRcv1W2C8L%2B1fbhx1n3JdbyLNG1a1TFetLQjs9vhV5EdAp1boj2ri0CVh6ED38x1AF5HB7pXVf3V7WzkdRudk8E27P7NkWhq91q5jYxMhf79iqs7RQ12gRnykV0u4yFJc5xChkBKmwIaoEKDQ8aTL9w05pSypYRHwftFCRwUA%2BmdpxM1zIBGGodAvWyZKIyN0IjxKbqKg2bIr9NhW09sVvAAdWyFnWx7c49Z5HyvpVgd3KG6ln%2FyogK1AUK70pq4yPOb37kU%2FLd1ux6wKWOI%2F7qlKmNEuqbihelv%2B1rPZsNFgeYO1wOXTEX1RRmIuT250tXqydR9QgdHxANBlkYDW8vbz3u9X4UZvsJX0Le2wBAPWriE4wuZ1I3yIG9%2BYzoVXWelWuGCiBdx81jyUV6ogT6S0T%2B%2BsYDR9DMOfjob0GOqUBUIHOHAQbQnG2stQmtBFGk2EGAkkqensQU5eMWkQSD9bEm2gyo02BZBKPbMwnq9176yRRQlglhpdaIhcGc%2BqUSgPd9rsMIRA3DpNInK1XYdMZovST4%2FZ8qfWKt0Y6LCHidgBmIKgphMtPlYtcFhssPeob9pNutr9NuV6KTOl1%2Fl3K6awEK8JvkXA14r3XNU7PyM%2BKmYhieUloXVERUWHJz2eQxK9P&X-Amz-Signature=45266a948d06a81f66d96b7dd593982b859f6e82b5ec4fd768f92d989079bd85&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466THTQI5Z2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102329Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDP8wuDNWIu2K0LFJ0uYiJE0pqV%2B6Rvn353IWn1bC6agAIgR232aSlnlPuSHYI8%2B16THYWMI6eufDK6xV3xmPxIkgcqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPjRQu58E%2FPQ12MYbyrcA9nMoFlHFB2lL2xWwJizbElEgZOGeJaORcVNkQC2FhkuZtnXKVqkx%2Bp%2FUyyY3pm9NewFgu8BLF9X%2BXvRbEdYY0e4VwbOAk2Su8y3cVmMmcuBcvGcqgoRnPQUgVj9%2FufcUccOiUVci0U%2B5QlbRNJTpSdigYcVGyKBGodlKxLXM19o35CG04neOptcCszVM58i%2BZZSvD3yite4Zo%2FxwErJCdncnMAN0S%2BhR%2FBv4IrEO7G8i%2B6xi4vGSNPP0wQl420Br%2Bplr4qreS%2BCazwEEffWmeIfMid%2FC4yXkcAB0tqfGb7jV3p6Z%2BLrvxV7m%2FCI4Zobay0XUekt3rON48W8VIXwGzNrx7qEZ2DEovPufwNh79XpGecICtHRWTzoGVnMFpmv9I0Dqe%2Be5PTX9%2FrxGaGzqS7QPjj00gJw8XL2Vnc3Ms4SfknfhqVuY9bROaKslrxnVjGZIPviiGgPl76IfSFMtxig29rViUOCM65UMqaRN31wYtzU7vZYjd2hIVP%2B4yt96WDRv3wO%2BYQTdzqxeDIKAiS1wWBEHB4XykSSSo%2Bn5gVrDxcnietQ35iBrvZYRHmmRBoHn9%2BbxX2Yq9aJvD4Genfp0UyvwxqWimrt4kSUDOCu%2BpYfDOCxd0ep5FFrMNfjob0GOqUBXYhmCIkJQLssC1qlYTGszSLIIXx3rCv8WJfLekeW36M7tGyBmG6UprVyEr5QRTkfFL9LBw4C8tnR44Lfs9MKTwkJb%2FtUdx0bwiMy%2Fe7G5atuZnQMSanRkbuTgbZ0L7CJmUCRvTOoZPbgK5Mu7bFR38nvFtm3FExa7lfsMyDtZuiFzecokjWGVT67SN9R2M6fVd4J7D7yX077JYLtYQLMoJgwYQ%2Fb&X-Amz-Signature=1be6c984fc2a03e8a6ecfb3d9f75aa0dfce240e9a6401a802258a7ce82e3f060&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=faa418dedd17610f066ba65590650b9abaaa245272a3a8a3034c590e4ad322df&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=26f5a5158a119ccf6b11554b9a03ff8ea5eae76b2ea46ddc1fc8206467a6b035&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46627Z6VGQU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T102327Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDPqAd7koM40m1LiXDwHBfdoQQ9w2Uog5aIn6WGJCCe4QIhAKybZSShUGnykgN8p%2F7GxJwpQ5hohifmonchXLAXQ6UvKogECKL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmXv2fv3kNT1aloAoq3AO1ksPtIsvG3qewYQAJxjYE1u0FKf6UxsAzeOh5tYWiqhDnzH%2B00H5j0EylK8kC2Gn%2BiPj%2F6IqyknV3X1HvuaL1m3PdMM9L5zvDqpjmkDFqCg6gma8%2BJNSNMyqrRCq8BrVxW9mum%2BE3WbdhvwNDhI8e0YMQSykcL2ajCAF6MRgFYZjhJkMqPjJ983V0nf6o%2FDJF7XrA7UfzrBlsR%2BXN0Yhtu9sFQ%2BxbpPeB3nkp2BkoJ%2Fcd8XcDGVd64n1t2xklXs4QJ4HmgLdoETof05kfgvocWz%2Fd638vLrWf2OnZrvRMYyMsEKzN25IFbpcahpJWWfZp%2FUmkGmRiEc8x6JMcq7vuWqjMTPaN3w4vpQkAjKA9fr2UTzDeqo4sNaGu%2B1KyqSkDmee0VOp2PRr7htcVFy7ePwDGMxRSonD7WfSm7ioB5BT6%2BopRcnQhUd28z2nfJNg2aJ2gP%2FLbI8xAb87q1MTj9dDNcI%2FpQFdV9R24X%2FHR1LNqErYx0LGQwUCnQ7SQdTThLxzYumkATb8Ee0RIpd%2FIvTw7Nfe4mICphUcBhMW3k2W5zCS1R%2FWApZ1Fbhwhk62LL7ccx1zgKyAq1ZfP%2FcDRSR08kBUngK1zMzLcBe2KMD%2BGNY%2Fbmg0rplZV9zDp5KG9BjqkAfNFLCXVmLXmTe35DI%2BNYT41gDO2DHGRIUWGhKDr6JTmIo9%2B9muxlzrVWxjUaATz5twN8jVJmEkU%2FkUvPm1wUKAehhxke%2F%2BsAi%2FAZH9JfXx%2FXvYQB4XmazXwxTxgBZJvAce%2Fum5Nt52GDwjtnG2mCU9OMYugJSusQLE%2FFzVPisXUAssU43g6OKPjn1Ev72F%2BB27kFi8FYQXUbtskqZD%2F8I%2Ba3mMI&X-Amz-Signature=5a18a7f2b44b1aaafa2bb6289d1826316e24a204ac8ae0e6c85dab608b839978&X-Amz-SignedHeaders=host&x-id=GetObject)


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

