---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466R34MZM4R%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T222210Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEA4aCXVzLXdlc3QtMiJHMEUCIBa%2FZuNqYBpQcyh8HD%2BqCI56oz7GmOt7HL0NCKKVdZUoAiE\
  AtjP%2BSnctK%2BM6GlehTCGQ54ZCwq2O45r%2FhLVKMlN%2Fmn8q%2FwMINxAAGgw2Mzc0MjMxOD\
  M4MDUiDHZ4Z7q%2BsOAG3dOEmyrcA4IviI8s5JpG5WucyMubVelrSXlBU%2BqNF05WHp1IpECSyen\
  bri3h1d%2FHodlb1z%2BkEOJk%2F0wX9F4eEgR39uUTq%2F0YzOpIrEndDSLDXcdi1ccre87Dss%2\
  BNuA168djSd3cgA77SzZtKYl9rnQ3WE8oKkAR1Y%2FrpL1yPHjvO0iJKtG9n74V5rXWEn9dgADVne\
  Gw1cTMw6eGCVyidLurtbYW8GS8DMMS2769FHi2M4UVrouPMOlvNEALPVV57olicYMZiv7cNgui1SH\
  nRPweQTVAnSic7PVutesz1L72IQUBqJc7BcjiGJWqenRyt13tpxeo1A5CE3XwFhJpvvSrpycyIgtW\
  UGSVNAlygi0jl2aaJTm2CX5kXseYwYqZ%2FSOSiNUzYM7nKOK7d3rN7ConrP5tRi5foML9UqV0C2J\
  pazUqjFANEm566R%2FXwoix026Lu2tRTVlQIF1xbuYWUi8GIHghEDkIVpp38g%2F5twBySljv8Mey\
  t5O6PU09taLvYv7lyVq0JJNrkuSYiC1rLtbqlUuonAvZ6Q6zsDh%2BbYOJQ5c1xXMrHeKgI%2FHjD\
  2COekdsxOuiDRbcXPYunuz5M1K8yFn2F%2FZ6kSbCqvP5QaynHI2EwqkQ64s2jny%2BETtqKECFFM\
  NL7vr0GOqUByhN2lyxL%2BAB5iR6CaYylw69Q9aJUPScMxmhJiKe12TIuF3YwPzqthele0lUQw3UU\
  5%2B0pXsXVy4rSb4n%2FMVTdk%2Br4jJo2Fo4JsXDut7DRRCL3YhpsdIrCLulnDlwFYpTA9tsJh0W\
  2fFKdHAwbu4llegd4afaGY5CocGu61vJnu%2BndSW0FLjSjh52874bvn5cKZbhoBMs2%2FOp1ZVQW\
  FdMCGi5PXYps&X-Amz-Signature=c7495ea1b9c865b119cf88981686a7a2b66d3e2a79110ec1\
  ed01ca0fdffa7639&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664V5O7QC3%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T222041Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDNbwy1fij5RyVDf71458Jg0Mamj1R%\
        2FriMGU%2BMp8ho5aAiBZa%2Ff0RXiEnQ4MZZEbT1cU43ro5prwS14zDWlX7XovLSr%2FAw\
        g3EAAaDDYzNzQyMzE4MzgwNSIMGrj%2B2sMEw9c6Sp%2BEKtwDzUvkubpKCNBfb9EPRqQKo\
        dvsay9n3ovWROmFtws228oybOit5bxlYR%2BZbWWYZCsLUxw9OnBDsyOcbwgfiEjAPKsIOU\
        wNzUMKJqjgEG4gi1mWkojlN%2FI%2Fc12GKYqXhxkWIukRn0d%2BvKELR8OsiWVZmmTcDGO\
        mKRSPeLrveKSR8O1Mh8nB5e47YBSgZKi9RjzDKSxrgLTsAdUonrRZYRlEAR61T8CHMvxyWa\
        V4wbQbzyJPMyHCg8gANPbVdtjulrTIThOwY%2Bzs3IH%2FAHblXzZV5ehG1AKnhep%2FpwJ\
        zyVL0IHz%2B9GrkLzT0aNF6M31O8eepMuCL%2BHHbQEndabHXPCKXEI7W1fUNVrXYJlsPyb\
        QHhpinXDqakyK5KQfyEPGb0rT69owIaAPzfaZtZEuQtpV3F07shbBJ1zw7c2%2BJTILsUJk\
        rTI87m8oA3NQnO9KIbBrtEFXm%2FiDsbQsu3m5QEOdbtYtYhRMiCTfexhJwc24PtJix1TaM\
        UdE3JQ9uMLhg4aEIkzFS8ADV9EjL7vQ6ZCtQpYmd9Tsd6OdP2D8%2F2l1L1vdEcmH7V3tO3\
        1Xmnz7YaWatsZcUHLQNCC4TH6jFllwKxX%2B%2FSYNxzejbeDfLXPA9C4knYJQ2CG9TZqNa\
        2Fswufu%2BvQY6pgEHfxkLQ6wwWrnn7aqLmeeXz%2BpS8hHNJIPQzVpD8gs0CRDqAl8jrz%\
        2F3awv7RNw%2FAIdmwsC3pT9C9RO6NfRBZ0GsI%2B29s3Q7V%2BV5p0A0cCU9WbZCwxLCBM\
        dU5ae%2B7sb1l%2BgQJ1IIv6Sq1ZwPtQEA%2F8olsTI2U%2F1VNW8A%2BNRZVEB6pj4%2B0\
        u8B0fsrX%2BOxoC%2Fs8RRLUqhi%2FkNQ2R4rDYSULIkavhsbTird&X-Amz-Signature=6\
        e6350fe5e8843516e30528770118e7d77654255884da9f8f75001a4204f57df&X-Amz-S\
        ignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T23:20:41.297Z"
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
UPDATE_TIME: "2025-02-14T22:22:15.846Z"
EXPIRY_TIME: "2025-02-14T23:22:06.619Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=134fc751bceaf5f9fc44881f240b19ccecee7f14162d15425d6ae70602eb8d84&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=ca83eeac83014d381d566c597367a7001ca4e328120fd353f4826d672e39e38a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=66c0fcef0d8746f9f842e1bdfdef485b4129b76358a18a7927d2571878a5a5cc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=ff273b9847f708db19f25709e6486208fe426b5f98d26553fa63f63c104f8578&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=fc989c3dd29032dabb91b2fcb73617a507e13b4762a29b30701e77a93c2b1729&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RLCDNP4Y%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222208Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJHMEUCIA0%2BuEFZsuGVMiSaXXhTvngKwGKe%2Fs2iJ%2Fct7Vt9%2FR3RAiEAuDSiYQNA4AEDA7HJq62GcjOGWTK3ux1ttSaVnuWUhqkq%2FwMINxAAGgw2Mzc0MjMxODM4MDUiDN%2BdJHMjaNF%2FdX%2B8byrcA3Y6qyOV3YV3amwoZazzE6uJ3e5HkXSkZH4AglpiJ6IIQVSm8kXx42baaABnsMh%2BXYlDatYi0nhW6UAufD7JYb%2F%2BJfr%2Fm9ty9KJ5BDIAXZ771RgCBopo14GNfODIBJ4jXigtbEoSjOGO4wXzTKwTksLlJpAHqSvI2N%2FpdZJgWpa840b0XiRFYuNPs4czU75%2FIRvJTxgRKgTFF4tHib9bfQuIJi8Ji9Sf0oqp2qLq09A1DzTjDQxiBCNo0sst9Z%2BXCdckl%2F8Fu%2FOKZkAv55Juz51NqQ7B1%2Bl1xeUkg63oLGpJkiisW23lnAQkFeLf9%2FQU9vLfh6gL3KpyiBw9LzRKiBFtI2tij%2Fj5pBiAMdoizarUhq2o01iWcV%2FOX7%2FSmmGTu6YtzCHBiflabw255dqn8ljyFGXhv2ZJiQT6rZlMATKw12HNqwyawcvO5nc06Uj6a6qrV972E%2Bi%2Boye0WuPLQJi37kruI1h%2FXvL3BWIxoPj4Dj8ge5t1xDOFNNeozwpJohwNznVXBQZnYy2BWDvBOGrj6wzmGUJtGbwRiRrTPm3hnJAxMCvdQoAZSii5E5j%2Fs6FK7KgK2M%2B5bHU482lpMeqsIXK57mKeMqnKvFLGNlLFMRcn9xdUTTgmx2GSMN77vr0GOqUBUppJ1IihZsBoXAxNQ7pkTFtnMsiyJu2rue%2BalIPjUa%2FqX3d9n5N8bF6ieGOEN89M3jC9Fx9O%2B8wrPHYaoAzs61dWdIbWaEqLPafuXHMSfMQquzOAvD75ZUb%2F4XiAYkHGim8v1CaM4Vj8niAC8s4KGJ8cM7kqbdF5OPqB9l7%2BbRWc%2Fwcfk2LIX%2BbEZiQjto9JGGIzbS54D83VWwonbOMtYmbAKxmQ&X-Amz-Signature=d422dc7bbd56834337c9c672a974245dc7c1f0cd69c4297037e1fc6819608334&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466546MUVPJ%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222210Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIEf07R05mncN6KKtTcGtvL9MVPyKZMmT7fOK7JhldmR%2BAiAt0C1pRrRghBjEsVxUZUP9vqxqRr7B4vFYIcOQcuwrkCr%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMEgz%2BJYIe%2Bp%2BMfGdcKtwDrpUM6unWNQ8K2xETmfsYwOyCMFeoqUsC8dncbXEFcImT%2FxyeQKBYIyGR3%2FTDz%2FotoDNgjiamGVJYeBdT27KI21w0FD11wS7InEPRnMVJCur%2BEBgYojuJ%2B9c3pJmjvwcy%2BkXT5BWXt6Ux9WwjgIfCRE0IEdaOcfBTcJ%2BVfx1UkI0oisMmjz0ZfkCHqr7c8os7ithxicB%2FfGECKfA4qoIDN639Ez4djOcfHbPKQBjT3LfyZFVsG36YPgH32bwU0vCXJ7ltHfocGtJkBfobaS7frLD%2FDt4LXwyytnilSaLG7px29YulzSPY4RbBp9YAu58dI3qv2DqBsw0rQeF79Q5YFEcIgdJ7%2BqF4vp7a26MHULJVIr31gBRLkEDQg4K8DDTT6gEZNf57gjEKp%2F7KBNEydoXvAyilIk6HPDO732v3rgp6hLxlmfnT6YRB0zvm6aWWsVO3mxgyKpHKlOiAEF4YTiJ7n5Fqilf6GbnGVWpVLAoIveaL%2FHP%2BGXd1AxoVsYJsrRiMhHiRqxIzcAte9PGEybqggpeRb0eqUO%2FMZ7Cip54m1bKDYCcQGozAwEFQg14WjSujYslNGj6MLt57UaI%2BeWsBZgv9QNR%2Fgdzpa7dQGLTDfOumkIxpDGvHLEowrvu%2BvQY6pgE4Lgq%2BbAL7aJVPmmq1cH9rX%2FY949cAiNinGnWLAehPlBpoMrbJDasdnEBdoft4k98E5nb59ADrH0S1Yav3JBXPF1GMfmEtx6lbBKO%2F%2Fi6SVIvve51J40o4EdRBTD1h54taw8BkrtA0K5ERtqXwoTrxS0cjCD22VjvCr4MJDH1%2Ber26m%2BECIk5AWysZwaJILIfTDby8RgDG%2FiO4HAEw541H%2BBEm%2Ba51&X-Amz-Signature=42508240c83cae8a533093c4605daa7ab633f9c176c9a0a445e372fe8182e727&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=4510ca09796d8ca99266260043d5aa2992b10cfe5f4a2d363827abe89f9beff4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=ad84590e8d0a928bd004f6d1ba3e398dfae0fc241e68befed8961f0928fe74cf&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFUWMEE7%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T222207Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEA4aCXVzLXdlc3QtMiJGMEQCIDfczZLETmP8kzwwC9hJVEu58c1W9X1KnzWOKUDqjgD6AiBcgJxuZblIgEJ4SU1CRz69Agl2ZPMBLhS0lV%2BCH7PYhir%2FAwg3EAAaDDYzNzQyMzE4MzgwNSIMnwgxyp1tWgkVRdPQKtwDBH3WEFi4UyPxh%2Fo0G1WAU2IrV3Lfd0cX9tzU19AKPDLi9xO4Ng4qbH2G0W5YCDQKfUfKPa6EVRzaHHJj6%2B8CrF20vfbCkU26Vdv54MzTZvMwzY33eE1WFUCuIfqArt0Jdll7zUwenA3PamTaMaijVE701HE7KBeSjkUEd4%2BtZaB1%2F1Gfd8OGJo6z85SNCf4y8bWl0dHKN2h5TRw0D%2FbhSZG80oSSJOBrBWh59fl%2BHmwqtRtmURAAO6%2FauDhXl%2Fk3iwva5pqvkRqImuE2V%2Ftww2x%2Fl7prSSx9narO0qFqwJRCqUC9umKNLDQbfLjqUyTCLLx4GZpy5LEuF0%2FaIsIPi9Pnhp2aSCLNKK%2BxzdIxu813IwkEjcAg6Toln1LGgDCiYYfulYczvpjOFUV2nihNguaHSFsxtOd8b4ax8Q9YWb3XgA%2BLgq4HFte%2F4GjpR%2FmT0ot2tajJJfjnLF9t0YohZIoD0iDnNzWzbU5dp%2BGHWUPmpgE2qZzy9Z67xbcUkxPSbiyiW%2FSdYwVlenhPCc7cx270pYqulsjfjP0Wbxfz279DQB3lgK0cY1Yz636uyqyMnjSeC1ELs1dlDI%2FLnoDHgu1w%2FToOONB0rzDx%2BYhOZ%2FYb%2B4lA54SjRBYaN5kwrPu%2BvQY6pgF1kNaWC3w%2Bcs%2BJxYTr9wav7rhAH8gsxONeow0YBO%2Fv1JlQvVDXH8XoGtaTsrPhyAlcV6MxLWhLa3U8BR0mngcqRUC51RVBpMXkjPBlPCz5yedYSnDI5v%2F2pPxidPH2EfbhFeXMbPaVwgpFV8U5raM5EPu6d01kQq60xtFMcvTGI6JL%2F9bQyjZxtsfGLTSaDMFfqfwb7i3%2Bj3TAX26e%2BbYTSkfv9nDh&X-Amz-Signature=7496d1656b302b2e58444f5cfd12eb87132c4a1af536918c9bbdf61e7c7501db&X-Amz-SignedHeaders=host&x-id=GetObject)


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

