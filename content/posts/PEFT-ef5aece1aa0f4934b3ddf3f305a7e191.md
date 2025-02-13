---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662FR3QETL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T124606Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEPwNY7pppBX8vCupYG\
  NXoDQCG1UR8gK1hjUkWjTx0XCAiEAwvNsjlZHlNVQIFUZc0jvKRyNlXrAfFAkEhNBjyn%2BnpQq%2\
  FwMIFRAAGgw2Mzc0MjMxODM4MDUiDNd4abl7aQl6WUWtNyrcA5BuW2hImfPA5%2FVGr3KV7bddlYZ\
  oY%2BXDlye5zWlzcK240Y6acrU%2BMLRh7PET7zHBr2UvjaGHghDmlHDWySZUtN8abxIv1ka92JHi\
  fLlSxJYV%2B71gG13QKeKITVuzpsibkF0YqqRO2qzykJEpxEOq%2FPBUE7ToqI0GcooITn7pH65Ae\
  2wUfVlDGC6OcnxP7gyK3OIpcymcqKeS%2BCacCGOHf347JA2UHWf2%2FLqty1f1e6VKK1hscI%2BW\
  N9ldVVKNmgX%2BrAYReOaPZ8nrTFUQjOvFdSQgz8uq4XVWXx4fHUT79VvR7nba5eE1dSxt2hWtizG\
  wZ1%2B%2BhQiQewQAY5DUWgsITvtg%2FjA13rWaE7kU02cGp2xxGR9R7nvfeCmLlq5l5GztPKsWuN\
  SwGKl9YYqR%2BRatkhYKFPx66CtFWAniSfaSFLBjha0SkD0uS2Y27Vu%2FipfZceBqWZWliRydydo\
  7q80n8ytSOXkyHItShxnRp5u%2Fj%2B6bQGbGDX7e3MOdhTtJOQ3iiLhBqlPoK3qNe0YB8BXXrZhG\
  NQ5nxQugomCEULaSOejj%2B8Vswp51zMmHNIaza%2F0g%2FBmvH5P%2BZv%2BfMoCJpgeCM4HizBO\
  lpj5GnyhdSLjY990bRy%2FDZFfDYJcpXLA8MP7Bt70GOqUBRZXR1k4wC%2FPLO5fmek3V8RyNzcFI\
  ZJ8aJpbrT5IdBsThxwgm3VXR6DZwt3Oder6n0L%2FE1MtjSrB3mDoNR96zP0S30qrHAqCUMOewpFf\
  s71XhmyyPOq5UXWvC0hLCc3XYz2nREhZr%2F6V9VfkiDtXi4fM%2F7m58oCmKN9MnNn0aDrixDtVb\
  V%2F5rAWDg%2FGokrVMUHK%2Be7rbt50rN6toUmBPrK2GEbnmf&X-Amz-Signature=ffb703f6b2\
  4ceb632a8afa739eb6c8c46b45b43f01f80a87c001ed5d0fc01ca3&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB466RI2R3XGX%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T124445Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICa9VmcG%2B5EOXVka%2Ft1mlquLxRT1h8KRd2vWyG31mKKiAiAT1vjPqVBgCO43%2BZ%2\
        B6JMVErWVJ7Wxr07TQz4iB674XPyr%2FAwgVEAAaDDYzNzQyMzE4MzgwNSIMO%2Bj2tqEf1\
        HR86kDuKtwDFu9TqusuBgOBte6V8V7vTEwUH6wQFxrQ4nLKH5q4hMmdWpdNwCgAzPv8HmN%\
        2B3yKQMIAtrbyOOEB8EYjiwa1hOFNg0LZvBsonQqOkGwgaKFN7Fix%2FXNebg9GJ2Xb4kuS\
        VF20vZ9F79UXFliJnZQsvUCBcFvRYK1Cj4pVwLhF%2B6VcfWNDKjQCb6aPTi0DlnLUy61yA\
        5zNCP043s0Ezqd%2BKxXLg2SiU38ddOnG%2Fb81IuJHRpHMjRL3NHXmUYO12ZchtazZNh3r\
        woKMy9YoATfjfsjqy8slTpwdbvXMdGkDq1tJQfNSPehJojfTw1Xv8%2Bf4Pu%2BqUa4KYtM\
        kB96ZS7Q%2FBaDeD3ru4IcsBBILd9c3NKvK%2Bab17ZhY5VcEYQ%2B%2BJrLObg4whLatWo\
        yXNZ1ilgktoDKRglpCdXRKilKvyBUc082ce5enKxcR6Vg7v9OCC2OgDneu9cr1ITMo9o9fS\
        O6rFMMQ4EFlxWkR2tDhjMD31AY4ioKjK4lcKpxyERch3Bc1XGA5xC%2FasfseMymELOZ8zZ\
        0ZWywmYjqXinOdykmvbxZOHmY9T9dOkSrer1sBE38KwQJB%2FRXpv00eW65DVd%2Ft5iWm%\
        2BTM3sTRTovCWb1kD8LzIz%2BhpD%2FgDrd1c8WH0w%2FsG3vQY6pgHvwRaTekJnc%2BI0A\
        BDYu4W0rNw3RqA2vozeloEO%2BNhAPTl1WokQS204klxjJxkGL9eI1Gdqxj8kORaQioHrPX\
        2c4cQcXs932juR3JxvDzBNtfCveVr1QvNoVvY9Q1KQc61A8uFLp1KzOEqiCkcEbr4BQ7SoN\
        k8GHK8mdgXCPeeWfZph7qGmQB1n4jP0fXthpRWJKEzFXt8hM5%2BvP1MX%2F2TwdSZ6gitx\
        &X-Amz-Signature=b91c9a04f1e93193853befcacd972e7a1489ee96e7a86c6895279f\
        30dfcf087e&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T13:44:45.724Z"
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
UPDATE_TIME: "2025-02-13T12:46:14.200Z"
EXPIRY_TIME: "2025-02-13T13:46:02.107Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=b4107ce7e04ae374e0010df2bb47914369974fcf43a396d0c7f1bd99a8bbf550&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=e21ac6187bb6902e19677dd982e706511678ec2eb531c14f2bfa0bc20c57b090&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=6ffa80152d4315c423a605f6118373ea2669799781b50cf3de017b1a1885ed63&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=51b2389f48fae0653b9ac0d616dc79a50055499340ff487f4bf6c4ec258d3ef3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=11bd5365400b13159823d5425a0916b473faa6ba059bacd7bbcca44192492b33&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VAZWZKCF%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124603Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDv81w%2BuJlUwQFpDv1NyzqMWc3GmgUoTjDEONW6w1RsWAiBTWCjgnZVqrD08yAqwvpfMCiROAvBZRae8jZd9OKsx1ir%2FAwgVEAAaDDYzNzQyMzE4MzgwNSIM3huNF3RCaDmB6EH0KtwDYcUTukeyEqUjfT3hqHD5u7jQ%2Fu8kcr3gBWaY7fLcWlVgfIU3U5zC1Fk7sgZQWn%2F9IA2LV0HY6vLY8WxMi6MXNdWe6D%2BnmGTG%2FwD2UB90tK4DA5poeSHto1KfnefYm%2Fe7jiIfMTcBAvGEWL2uHc%2BHvTc3i9rgIFrzefp0pWHLVSatpYaf%2Bw%2FmDQT0M1ktTA9yfVj0a%2BwY4WzCF9qs16jlC3gT9idCtJHYFP556I%2FGdp9fI%2FKLNokODrlkEdvGqO1UDq3racTFgzfL4EGD6RCPdC7DHVJn49%2BJAGNqku1TIK08FKakeOPJrtF3iCr7PVDn32fDsGt78TnK8Xm8R1NsqdFrKCMqBNytY2Juhx6YNijarDTEPYFvZjob97gqIR5LJJUdNkpiSmi8domNbrxGz6aHLY89WL%2F3E%2BAEtTkaJAg51cwLeBV5vpvHRvULyAVcxaBuH5GopWGAo2VoqYv7IgT0tfym2uTm9Jy6DSt%2BHRA1ILYf5e2veqKSLZtadnJYV1FEj74qC4dpwkKWaivcqIGEX5WZcy%2FIink4RU0fVDlw1647FTz%2BO5927oc%2FVlYoDG%2Fp41lx3pa5a%2BQOPxwGDwJ0MOgFSw0C34wUVeOmedmYvgP1LbH%2BO%2B8xOMMw6sG3vQY6pgHdjRezhurGLYch764tIkjVUUigCpsde%2B7ldAgowwjWAqbjAiZDYujetyFfk6xLh7QnUVWe%2F1McOEo%2BuCiW1MKBdaqwF9di1Zx42GvR82PJIiQzgtl1tjxpdnj11zwWqSDd0Uhm4fXSU7QGTrYp%2BRfrO2iOHPl0xk9FB7zx3DoKe9SkXCt94JCRYD3fNgWA47mQjyB11VAhxCes%2BFDpAN0DtIaCeShP&X-Amz-Signature=e78473569278ad8de994bc71b2d1325bccc9b6dca0ef5d0554e17244a51fd394&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RZ5LYART%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124605Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDter%2FDXGCI5z5%2F4lpqMOug0V0EQJRTcl7O4cXSNOG12wIhAL9D7qxCDoI4dMObPTULhnXlBtCxArJocynjpCEDXyF0Kv8DCBUQABoMNjM3NDIzMTgzODA1IgwJgGkr65kkC70TpWwq3ANlglUpWo%2BJhCCDlVW1RS9%2Fw1YJj6zzVZNmAsPSREedTNBd9rBod8LqFvcvZz2%2BKN4k%2FzGfUJQKw9q0JGg25i8pAdH9DMrKK%2F7%2BurbWYJwBMR%2B80S%2BR%2F0mzn94jZ8tjMwoJYjV84AXC%2B%2FLCYgZLKLvvhk61tNGdyWkoA1SabFEAgsqICqWr54kJf1Qskgjm33hQGv8jyxrL6gjJwjxPviBKEf7ZXM%2B7UTP6Zq%2BDX39yCcm5F1M7eESJTVS7v2cmhPVzh0Rg1szr1NiqdyYl5z6epGn521efARm8x8r6PVUCvSkrU%2BoBF3V2rIHygNI5nn5mdAHQ1U84Jq1z59a2j%2B3sBL0dL72LnLgrQZ8%2BcpG45Ddv7%2FMvGo9DsJ3XixUL6qnUN6CluKkswrpEbj%2BaLR0P4gymhbXAzv%2FQAjYbGC9yacKs4E0swS5EYuel1QtqiAkienqJbVnfmhHON6uWnXseMNVljEO4aLDLKm12vGKQWHaVQB9mlnObmSzc11RKkMQhRCZkDjvj4jzDu6T%2BlJvq2OMtCov3W8iHJF2o2ur9lWBY7SMlvaZQIFOdd1VTNWVPC6M%2BU7XAldAo42IQSR3gRfHgrTU4xXc%2BoS7MSBvh4tpOOPN3nofMUESCcTDswbe9BjqkAYQx73%2BpYPXAgZjjCgHbn3ycJomoxAHlz97JcuEHsr3VdHyslZ7W5ewfWkwsQWyH%2BnPfLi2YNGmtFp87HKGLMhhXZkhn6FJxcQpOAv3ER9z2cEcPmB2R4MWi6DqoANVRwRRrXW2mTbo%2FVCEzclvfzPjBBXgI2UETcAGkrz7VebIp2q%2BDOHpPsCmzj%2FwTdAxHvjz5HhpSY0ZU%2FnNPGyeM663bzf2b&X-Amz-Signature=5ff4eda2f51395b35a5a071170df0be9fbfd939fa4671bce9a984258b75050fb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=3a97663bc6fd4123e349dfd99c1024f03bfb2c3e8c10a01de0b28599612077bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=88593fc1469e11b048d78dfae9f23fa01199567f1efdf1c52b142126e3c8950a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UWFEZSTP%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T124602Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDcYhR1Ml8RMWohk858iUQ4rSo%2BJvIMtO4lpzrOKqOmZQIgQvKGn9tSRRCs%2BtSQ8v%2BrXxRtlk49%2FNgjOBhRZqhxeoYq%2FwMIFRAAGgw2Mzc0MjMxODM4MDUiDJS5KZkScX2FKN%2BUnyrcA%2FTEQ1O9KskuGW0Of50oTlHKO2svSytQVj7vX8qzPUOYcitjMO9CLsCrVS9xqUezwV0OVpH7nhtCLoD%2F4RRJgZYyuxjdnZsRizJ1ONBvi8ehiSRwgtRxeQhTidxBU%2FJEi79gfDmUR51cBcU3nr3bBwy5Dq1ubuR4M8U3SjT4UsC1fvCaVekRR8%2F4QBY2lKHTQwjOfJ6fyfApi0FRN8Ppew64H6btkP27S3y64j6mOFJ2tMwlqjFplZFtzLB%2FLi8MJ65i5QEbmJXStmBBlkNpbCVLHE0hhjvMER7Iz6WRL86TzPs6cfKsYdqfcNfXzX%2BHByf5wruO3XPcrPAK11HsP%2F%2F0dOtHN%2F7VPH10BvtM0ptOtDcS9g9KAgvd0yOYXIddpi4GYEh49UDNZpn%2Bm7hcSAVVhWHoDLCxYqYYpw9%2FZcg7uRlrh2SkcT6SCI0nASBx%2F1fohJUmND33f7TXwBD8HIDxU%2BLwPKFQ%2F5B9cwuzPay43pOdVYt55d0JxatjlOqETqTMpvqI9KOkoDwjhoUKrsLW0T%2FUL4lGk6xkq68MKkmBY4cwXK4Ddz9q10VACDl1clzL26l%2BDaJdcfwuAMYKHWQAbfZdMhrpvz8qYvz1IrBMDIElo1bexSZMlo2sMLbBt70GOqUBZX4c68WMaRAvYtVn8YYzPDtS6pRXTE3EGIagKUV7%2FDmrpfCWL0VWqqKipEvuJwh9FcU7j%2F1%2BM2fsCyYzHlZEa6tZmpYSUUOw2VoHczOGmMRtLHScfBwfKmlEJOwsesMiM%2FMB%2Fns4vr1bNnVGAXWQhUr9o07MY9bTtcYj05z7BFKj5RX%2BgUuq1nL%2FI%2B2MnTi4qx3qH6Z2OYvIBXxrid%2FAB5eBneju&X-Amz-Signature=1f32d2a58a45155770d8cfcf61ff419d43fb6b3c45754c2aa30a475466df2520&X-Amz-SignedHeaders=host&x-id=GetObject)


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

