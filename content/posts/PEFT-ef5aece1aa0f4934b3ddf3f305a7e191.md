---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XNAC6KRI%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T032743Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGBR6RN7QKRyGRWQMGW\
  2VS4NguJBNW1oxNF0RKwWrdi4AiAHfW4QCJ5pl2QO%2FTM2wZksAG%2F3U%2FA985FNAlIfZ%2FsP\
  EiqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMPK0%2FDz93gMk\
  %2Feh7JKtwDHMXk62hfVSgBOxainW%2FSZjbAaOC0%2Bzllnq%2BLZyQHqQfF7kQbdJ4Xhe2tiFfk\
  9AQAfxdDNpwfvEtsdVrXLT8ev50YiEPXu9z38bnj24Bp1Yx8W5A%2Flr8FF2zRGcK7QxH%2F7IiWn\
  CInvHMcZiSGA%2BZx7ik0Xdv6%2B6DwBNs4u4DrNDCvS1E57ociifLrD%2Fg8TfJj1Kd3Dyx5UWD%\
  2FVwLzY5DE3mxzShfXeL5lBjfSDmEeuvLWc52gUhZgRZBM3jqxF3NbfA%2Fa5IYxIZ275qT7e%2B8\
  ez3KGzEngBEbAS975iADgddH7uboCRTp2FfWSXzEjQrYMh2ImUHn7mMixVrjH%2FNst2sTrCP9wPF\
  jv4pxfwLQR1biHlaJn7X0u3ijiLRENFUDyhkf5NBQ1WW9RqVpI0dso2%2BfyQx4OFaW0KUipWT2KU\
  YEyQ3KbAU6%2Byz%2B1CYUmUBSjQjzKwxNhOttJHZgq%2FCdSH2MgubHo4FOdzwe2hzLYyJNEJADF\
  H2jpRI2su3nzshvKAzLn9UVDgyHagGSvb6jN2OeTQwTBJktLBsPo9H4detfL%2B1OXDADHbc%2FgA\
  qOqdf1uTif8sZut%2FbbneQIxQhOvKbqlRInRCtpsSlTwIOZ%2BwPxqoBFxIuzhicEz0xIwhfeqvQ\
  Y6pgHY9isO1%2BxsZ4vjYiOGVO%2BoXlditTBPx1oKu89JhTQqrjzqgAn131ZComCuUMMYvGxod3d\
  Oi%2BwD7rsseoG6yJlt5U9xOCr7kZYsfbNn%2Feq%2BsbNbUq2Nci%2BmM63tg2uMNvabXV4Y4SYw\
  8%2F81AgfaWwuF2lH%2BY%2BopIvQ03FLeSMoXf9VF1DIP6ODvcYym1YXgUASmofD3y1XueudFweH\
  kiVZcPUuXR3jN&X-Amz-Signature=9dc2e9fb70f8acc67a1684be0480fe2a92565949fa160b6\
  352e02e91b33939d0&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QQO5MYV5%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T032630Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCIjCKFoqW6ENmxOHhtP81hqxjlhcN1YPcBYno8i2%2BHuQIhAIYqKGXKsA5Jjq9hs%2B\
        RWTLmtId0BQQAAOyyndeHKaesRKogECMz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1IgyTNAbOMGjo%2Bolu92gq3ANSc4hIZ9LHhOReM8Ttwi5BSTKAYtJg81\
        y7pRsZh%2BoyTZVTt6XAm%2Fpp49LjlwWa54LLJej3vC%2BCcolENK8VpLf9%2BLr%2BPZr\
        CgI47BXB%2FPsZVz9MOX8GodDcsD46I0%2BfcVGBs7vZwkyADhCwOES7rj1fQ4Yyyqwq1Ho\
        nF41QCSlh5o%2F1uZSMIZj74L11YWFXfgqH1DsWzN5D4zsBdyJTlmTZ2rEPAaBW1pz61mam\
        PCwObF0wvbsgkCv%2FIrYKloXZDWkTirV9dWSUjD6RsIzHMnllC8FfZW3%2B%2FIQPObaGt\
        HHrjQ%2FRIEoOxkbTqaYI0JvNE5prEp8wZrRMiVHE77dVD17z3Nkv3Vi9%2B6E%2FgTKf%2\
        F2NB2pwstCrD5tkav%2Bv2b8mYGF7TALR2CWV1wauPjfQ4BwnlBvW1McueA0VEE726c6op5\
        Vly%2FR9%2BVwnRBqKCnUlOoiUdbwNTkXCMaabfSln6TOHwX9ZWs3Y9krTd6ceOwGlNgI31\
        bFIyUeW2obA8vZ9q%2BrHuzyJMx8Ksy7ffqerlzyr8YC7rHoKXwEBuhpXjHn2zrFgzU0YzS\
        lcYpEXDCavnUcWm5m8lrFnKnODCoJwX85b9Lgqbtv1zmIWoR6Hwoi8gpH9E%2BF9edQyTsA\
        XZ7vDDX9qq9BjqkAawvDZh7KfwkLVV6VyiKuPz1x%2BwtRCFkLxig8HrSdaeI6b9wqTVndQ\
        rBfb4W9LaqB7wPXIhaV4ojnyJWC%2BnEj%2B4oefHd8941GPOSiIvwT7vfCgLNU8X3TcUaz\
        zmsXGror09OPnpUPe3BOUbfAzrQsfReTHBmpkSPet0pSz0djG5yulGoor0cF78tKKS77hYC\
        wuGvqsnBBdtivDx4NygUzYv9kav%2F&X-Amz-Signature=c831454e557c5519d34ed2f1\
        8d155534e2ff3befa80681c3ca7f524421f63efc&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-11T04:26:30.765Z"
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
UPDATE_TIME: "2025-02-11T03:27:48.720Z"
EXPIRY_TIME: "2025-02-11T04:27:41.132Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=8fe7ac3de75ecdd2907bcfd5001a2b136390d793afa507623a17b82cea90a205&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=939b7ea45b51a2d952d701bec4f6a27b544c6a2c215c9dedd4a97677a96c5a92&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=e37e898244bf5e3c50be8abbf90d2de65cd28b218441ae1152ea462ba5cba349&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=caac1391ae9d8fd0c542c31ad588b55f04fbc550026f0c88a8066dca5b674009&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=8479132267d1a32aece2808bbceefc77a91cf23cf3b1d5adb42425e69ae2d4ec&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663GJZDXPK%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWQJi2iliVDnzpngqtmpsVaE9VZaRj3vXPuhPZAI8UKgIhANEDxl7dMzcmRMq1YEiqIGc9gPaI9qWiPsiOSYWxNiZ1KogECMz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzIG8RfSYPla9XSgMoq3ANlRr1TdLSsvHNj%2FGOvW6BWAwmM4MYhmN7cu7oWvPALw4rKyB%2B15H75gFyTBwYgwFFWtMDMcEdhUni41jcfOggKmr91IOzqAkHjozoE6WHbQ55%2Bk01m%2B%2B%2BvwBkFsMwLhAMhIYMVfj2zoLED8xdaOWfPVbqjtytY3m9VuOlmulu6wfmDLwACKPOpFyea68M0y3SH0w91Vj3jdUb6b6AxVHSLINeBdsTpqg9f4sW8gGz7rcCIT%2Fn21R640eckveQDtHSokTRogot305v76GNjriw%2BxfkA1y4zCY0gJAujIbf6RSdhdCe0yD6ceR%2FWqmTj6DvTSbFuSEmBKKwuE5hTeiZD7jbulR%2B5jDmAClCsbymU%2B3%2BRphUMwjqo9Em7HwpGr55rrmLrD6hth%2FopBDIXlhHndP6fqV9%2FQ6ZmTPCl2Jy9rWgdRoZ%2BJG8crqMOyFVTdFj4yWtg%2FYfcnvSX2DnR1TdifniuL%2FLKixMmXt0YcYgrbO0FwQJTDAdqa3zylB0bL0XgybEFBC7q3XdrDXeYWxWgc9nRQbwy84qX9pgKTPhmR3jcbylbw9dWfVWT8sQ1DlhRYnlQudYmY48En1aIQuMpTymrZKoSchStxdnQG%2FOJwt%2Fl0EXidsqo6JUHcTCv9qq9BjqkAchq1B1zwLjS1%2F3vcXBdqkg3Tq0eoKj8vmDvU%2FvOZEbsaGrcILM6ntUoJ81V1bKGGrO7pL7Fm5okkIpRMaF9ETycIQJQeKLJMRKbnoqyL26ALNAiHo5LYrFY4F5WGypnjCRSGi84RAk8gqU1Y0oH7h0Q%2B%2F7GJ%2Bb%2FdMWZsMijWAXd3zWnPaD9a5WCObZongPR1ZqYNK7YHNxHnStSTC2bbpajX%2F2Y&X-Amz-Signature=74dfed00ad5205695ac234bda2ca090cd65ee89cbaa64f79a87f2c134608a4b9&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LFSAU%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032743Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5tI5owtD6nZZe0xlYsR17BolQwhIdy9F6LorHt%2F2d2QIhAM9dWBIK0AqxwRbSEVO4LAPZ7Ebz0e8iwgP%2F099%2F37pBKogECMz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzJJ2e7kBr8RAG4OW4q3AOS1N5V8wAhCFQJai1viHtXw%2FNDHIKotPQyZTEDPLDIctDEcPCN3cj1h3qfSuLRP3BiFbOEZqBiuNBaTBbvVsINq%2BxnUDEUx427a3XWLfMlPRxOMQV9wPlKI%2FlhRT%2Bgebnv3DcwtLadHUbDb0CArxjuBB0on4CPZIDt28LA%2BCNQiDEbbT5TL2PgciYF4q6GyR2uW9QRgdZI7FzXRtdLQMNkVUow3AAHIeKtk988Il%2FEsM5rsxT5F93GMMK0UzmrwGHH19Q%2FuTaxoMPNmNpwR2tqs04bTAVprP2mHogS%2Bd4mj51L5oZNaDZU0giZGDjnQtUbsu%2B3i1pc7UovYOgCvUtmHBMzxJqb0UTqfEu7aUQuBl184SE1k%2Flozk8kWtGvQOg8Pfbi0myi5A3E5HGziPjvYMTevRbDZZAgldlbSGq%2BregygNQnUdG9uB3GFbdVo26pjbFCjQ9x1SYa%2BVuLOo3DXa9mFbB6PR6YGikVhVzl32spaKGAQQPe4Gm7sZYpCWkqjjF3AGAEpRXxH%2FDTBB%2BqA5Au5dLT7V9g7IF48TySB%2BCqA2Pco3ve0YWMaWGdqneo0%2B9QZBBvzXppNlqmk0%2FqPK51qXropc%2FNKA5wRayoZbizoG9OT5H0bl2taTC89qq9BjqkAXZBu61GgD8gYw9IPDKbFKj7prWJM0RpTlvaeiO1%2Fa47Jbkc%2BbyUMPILItadYc77hZmyrOAeRUgKETzjDNwPm9gMfMX3TwmAemMsktMWAs0wTezqgdBhgCZY6lVeHwii%2FQjD9hDaVjjNVzsPyLn7fEnI41EX4E%2FckoLZIprgrV12yyQZ9JlLp%2F5H40XFaWhjDgVKPRkiSjc7QumjLHm8UXYjaRIz&X-Amz-Signature=e574afc07196164777b19917d9be77ec42bc79545ecbacf42fe748ed320b459d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=d7a43a70ea0d57ac0afddc49665d5776d75920e7de778d234fd5a4ab5f724f8d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=a5b07b2e14be3ef6d3c550ef2ffc923391f2c9e557b45ca2d8e36691cf43357d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YM4IBTAJ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T032741Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDbyVm%2F%2BL9Ffs1QV%2FSQBtsQm2BhPj5EqVcyfTCHSgnjdwIgO%2FhjGiQg0QDyygWLErtktwyjdvEoDJa%2FzkT0B1QK7vQqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJwDCujezUybN0pYOircAwptJeUWlH1ppkEkICmm8X3xlYlPs6%2BgGKKZ27Hn8ukUt6DDjRlMQEGFMII97PmJe7uy%2Boz1WGYFyh1r6YsA0jVMckqnWoVLLv7FVNKZf42MnwcP1AI9QoeEFG%2FyW3IgKfL6PS0SmRbWovwDjmk9%2FPi6Y7hUXvKUoIWzcdncW%2FZGowUk5OcbeDgsX27cftu9leu2%2FArCXrzaXc5TXzqzJQOdtDyZdXcGNeT4GcyVsDjlxV6M4FykZfuAlH4DUgGhgex%2FXQRqsXhZqOY9NRNmQlF27D2aC89m4Ob1indtGULwncZVk7kKzONjFITq7SscTmGhFJlbub3%2BkinnC%2FhBjQbrljbliq1%2F37bq0VQS5Z%2BdANWmVf10bONzbCYnQ1QLPZ01oqfvsSGgJwIWLKYF8vyUEOK5aISDsJlqxhXFi3%2BPStq3sXWJsL4R0uAvds1%2Fx38Q92HPB4ih5CSayy6KDlXjfVvlcUyryrszw4x2MGwKVm4ltZhiNDI96vJ%2F%2FeBQMjQVuprYx%2Bg5rKFVjd%2FxnEfy5li9av3QkG0R6L5SygWeptM4QHkI1dhsFnIx8hgO7xlI6zu2NUCaKijeBxrOFq0Go0rar1GxoGGdP2ciBIz7KuLGRUagDGQ6UvDSMKz3qr0GOqUBerV6ETnB0yVfz1gj2Pb8HgpK7dbhnDgBsg1gii76SbTlkns06U1FqOSqIgNvWwjzi%2BqZ5AJSwhCyqXi9V6XCjl84K6G%2Bx70Gsn0gn51tYLC8n1fWZ%2BGFTHqwdTPN3z2Jm0vbUsiKI%2BpK9SRYPaqgPYtSlA7Daz39vm5kEtStN%2F%2BXphOUBhfP%2FLWpVQvHQvryAedrHfy1Ji%2BlSFy6N6sUn78JJ35E&X-Amz-Signature=a70f2e043133a8dcb087eadb2bc30b02d8885eea15df99c13f9242aedf78ee78&X-Amz-SignedHeaders=host&x-id=GetObject)


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

