---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZLRMCP3T%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T102428Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAGTBJ4lFCyR9MD%2FK\
  Y5DbMWvI1PMUFmkYcxIWYuH9%2FfvAiBOSJzl6fOZmBRZoW4c8TPk8MEWVcBSv4dKDyBoQGi%2Bpy\
  qIBAiL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMULLeD3vFEpNJpjT\
  6KtwDDs2X%2F3MVcJ1DhylIP9rlmMMYpRFAVhts0Re0F2PR00OVSoCDaKSSe98AWgPKhCq%2FfzXS\
  g%2BmAnZZrFUPQyh3FLBgZBfFVW5VDfL7qbZfcWudMgtCbwc%2Boq6MynhY1VebnpV1QWfh44bB39\
  9jn%2FEym6JA63QVPXxZQVEO5rctoWSKiPVpgONLUlw2rOXAsFDCzo21%2BncWl9iYiwjk5wwdcEG\
  LUPH7q1ih5up6Lj%2F6Hr1dDIcYI107gYVI8lnZ1mxfejD5su6NDtPsR1bVoZvBpenS9mxJhFybz4\
  vS0FStniL5hI9EeWxRYByXqGif5G5dCCWaw8QEFudF8oZqnMbNttaz6Ax6aHRd45ciYEMpjn0ghSA\
  BciW%2BnFcwu8vGJtILfggCnLlpmy2mHCb7oAFfV7etnvc2mCJeh%2BHf4qQ43aUX9GKdx%2BvDzb\
  MvK5y7u%2FugM5qmcOc2jzOHQHinkxQQqoXJdqqlua6VOHWLoeogDKPkkLd4MEbEsRiuhBhI3KcRW\
  azF9zhn3FHoFKLVkqbLt5zLaaRF50Vq3vIbkhqb0UvcYGc3lJ16kyWIR3A%2Bx6NK7ZrGSJZx%2Bp\
  rl80M%2F7KV778Xv718deToMIgRnymboQ43Py0DrckthldoC9oIAw%2FP%2FnvAY6pgG6SrNkUNqs\
  V2SIaozOoMM%2BlVZUCZZiAf2SrWrQEDATDFzlBZLr16C2zh2qeVdhhz5JRnxVwvTN5%2BiPs18mr\
  D55byr5dy9%2F63QKzQcwwquqiwdC992gcFsE6JRBq0172OAOM%2Bky3PDA2q%2BMVJg3dt%2FHo4\
  QfDQRmfthkyKpp%2FXSpMlg3zQ%2Fz0DDvALAc4%2Fqb%2BUEIZ5sK5ePpH52CRMsZsekzWFpSn%2\
  F9e&X-Amz-Signature=a61f2fbd6e1a4bb696342bda842c432c8cac63ff45b5727965d80f16d\
  47b1f31&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RKJUGXGK%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T102311Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDs1Iij8p9AMMGWQvkJHmQvomdj0g00Kbecv2YSjwGmBQIhALQiqtZpZljMLLmadnpL%2\
        BJRMSxDNNwp70G6OHx%2Bn5EVeKogECIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1IgyCGsW976k1L7%2BHvPkq3APGTOgPKryBPc5i3mm0zL6XOJjGKWcpXZ\
        ggyik%2ByiMiIAIOMCcJ9NAZ5mv5Or%2FbCk25ZZRHlxjclZ05I14FmDhdzyYyw9Jk0%2Bo\
        gKv3YKDCKDs8Ax2NvXHrxFlN44tgXAfg9DPFPKiShFUiH7puAxbzCOd5kVrBLsCINTq1EFV\
        Ra6ARoAjc%2FJUbVCSHyx81DjkOkfSZudKmj%2F0FFDXPXckG%2FQDZBlWJjzEd98GJSR7z\
        FHKUo1A%2FRdWXNE59LmWQ04ZXbXPFOVbKOTH4tkKUhe8Jef39ZuDTSjLmGOIQBex4B%2BN\
        e4ftCJcz1mDqLa2JPCDJYKmzL65nqzJYIo6%2Fp4lEr8sYBJhPLTMk8BEOwl3YOPmTXCYyN\
        Xqq%2BEdxOET6FJElFVCmAjypz8Q4WFIIfakb8rwKxpIOFzHtNG2a4HK2YyHV3GonibhWCT\
        R%2BrPTA43lqcU3Hsm3fv%2B9myhPVV%2BYf724it5CSHuSabDyGwR9h9AIzVQ6vqOhiukV\
        ZAQwd3o8J8SKDFwIfEvtir6Qpd%2B2LUluHFH880bhyXkttC%2BC%2BQgKiHI51vJzH7djg\
        4SPXfRqqZjUK01vPgPQeEzlm0K3jpwg%2FZAr%2BzlHuUvItS34q4t2TUCWrsjMw71P2V6z\
        jDmgOi8BjqkAahRumJmSj2iwkOXhug9DsS%2B1GHkdhGn%2FHHC3wZEjDQjEZK3m8nk51GS\
        HUMcrPk19%2BtOXNuYifls61tKLRhV%2BXdK%2BJMO4JRt0oVZUKyx2TaW1VF72D473Cp%2\
        F2LJVMBujIQCUlX5lusHUHRjvJ388d4jVXkPwMdATdM6%2BnOqHb6LBW0bnfZxWPb6jfuoq\
        cXWbxsfrFaKwLzaw4O3gvNZy7gkPpk7F&X-Amz-Signature=2237102e2f2de4d8da78d3\
        69262ba49113b0e40988b55a9c9341fa2d503d8a1f&X-Amz-SignedHeaders=host&x-i\
        d=GetObject"
      expiry_time: "2025-01-29T11:23:11.735Z"
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
UPDATE_TIME: "2025-01-29T10:24:32.881Z"
EXPIRY_TIME: "2025-01-29T11:24:26.925Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=4a666ef7465bb20ff9badb08373d714676583ddd44ab2e5fe5e504c215b940c5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=68fa46de507b40f969caa418a1906948457bf5dcb4d7d85b7ed6ca6f26773c6e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=01f6c4b7a02a097a96e4e00abb85f28a1afa5208936a84b645b9317509ec06ea&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=497975c3f31f36829982f6cbd18f6d8c7163213ba5d3bcc8e8750cdbae1f6692&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=d68b9b1c9a6c9a0ea495df9da8ac5ec9bc2353fabb40371953d8cc21f77e06ec&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SLWAFU44%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIBBzRRcYJY3Gu8UCberpSpfKwhhjr09me%2BfJx6UqZhtmAiBoBs9fgAkquEvKqJOFR4T6R%2BwMz9IJnjuZ69Yn8mxNESqIBAiL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMDR9gB3E06py2cpz5KtwDmkyvzk8eX0hG581zCYLSDVbjl7HoJS%2BqtemwuDxw4EcMPMXl3uBZj%2B2sc56p3ZQbkTZfb1FwpUvyACJlYTM0HKPp9LemihlxMOhrp%2F3uAVjyGmESWsYye1HpgDixKuzdLSB0CvvuT561AssSrV6N09ZQFeayjMIaJJw0TNROhLIOX3ja5fqvQGS5DKrLDzv%2B8Q22ZMtLdbyAsE6dm5hjhDcyoRVPWec40kpdn1SlHsEmx7oWPQ6kdaSXMiU4wpHl822kooPhdhP7WMNsYsrENc%2Fn8%2Bd3VZKDGgrdJiAihcyl7DypYC0kL0fOWCB3hPiElbZlOwTV2WRcUjL9srNvKx%2BPBg%2BQsjFJFh7uMz3ECCXgiUpVCUu19OMY0%2FHwvwKAS87LzTMor83oDD2KRXaw8j%2FRixSjGJZ%2B3OLnkOTuRRfuj9VX06YglYmBZif7iu5QaT19LG6qQ7Kyc%2Fvtt31hT%2FiuQUNPASdxij0jRei0mGskqXwg6bhqTCT6IdGE03KSyo2Fzcy2ILratEmrMCPr2PEsDM8Al0Ov0gv01mT9sGKUx7SmxBKMYqnitZNcPg84delZF6zxXsCbNQF8cNARMONPxe51krTG6JcsgBGexiP8pcX086WAT8OQnSww%2Bv%2FnvAY6pgF32AGSz8zrtB%2Bst2OwVXknqJCX6CJG3NG2DOYAwqscLU4QLXLLOH%2F6zEbjCU8zMTU06Fq6sGsn2%2Fqb2%2FRn5WhkUO9qkIDm6AREZbuNZ80o6jGkc1pOWmf0xg0lVdexBhRekY93gp6bKplV4lDQDItUUBsaCpLj4zwAkhrpYwGrMDwGjEA2PMqut2YPTFEJkORUmSBq3MbI06jwwaGD4RGEujv9jVyG&X-Amz-Signature=d23fa10ffd1e325f817924fb15bb549e3757295e4c6460416b4cd68827b0d258&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIECBWTD%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102428Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHLbx5L2jjejvLLUoqKTW%2B%2FVU%2B5m0JkDqaD%2BeQL8xGapAiEAnc8Jj6i3cdonFnJOXiwYN2n2ZwmuN1I%2F%2FTfRVfZRXTcqiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBRa2NbTWocODd5heyrcA4K45LiunVdXbESfNZ3gWH8ZUcpJ3uYEEjqu%2Frri%2BmISkjnlpBVS5Fh8fnXBgtWdjyZJ8P7Go6lvf%2FJXK4rwBsqo5AvW8VhFF158QayXF7ZmXUG%2BSN4c2kMXkUC6TCqFL4cH5pEACBAawKCqa9ucQtpsKkbkaMpBO70AyXTBDK9uZ267zH95BVKlhntkowTIGK6xU%2BvjqLp2K3cLMR0fdY6WgelCUkZtyvagv4FC4%2FqgL%2B22wN%2Fv0LCTZz2pW%2FrlPqF6q5xGhyLnUqUQbs39gg7whqCaknHMigJemmHWBz9F1OCih%2FOYDKU7KsY8zwkgcwUr%2BeF1cKB6hM1jZi27TLnFxEvKR%2F9Sffa%2BBcoWwzVzrSSnMz7vzPHKluCbjKAz0EHEN2C8UHcG%2F44mSEtCL7WER4J61g7UpjPuwBdJUxXID7y%2B7zFa%2FkNhdR1gU8z0a2ayVha0c58jP6geF3%2BQAFni3tz57EZaJF61%2FLmmtrFyu2cRXx5%2FWKQd5IUxP04puZgAdYLwPcfUJjZrFgFe1p4PxVSGveKbw4knS60qJZXCFjwe7odT8E5pSuQw8NdtrTMj9HiyYKLJk5ZVNpwhtt81NGD6lrzr1m0Xa54iuPqAtdftwXaFk4%2B56TswMIiB6LwGOqUBK291jtoscC%2FxrzlqAa2ALULrt8dGy%2Fqqn4xed7yiglR%2BntuBXUwi05eYhgZRRLDR5v7m3descQTD8Sr1Rqa%2F4tpIcot4Kl3bSDeWPmwq3KDJjutnXvFYvA4cyhP63rrp%2ByK1l%2FpykcIlEU2zB8xnsePazdPj%2BXhbsxzOkuVGOnzOPxcgZZgBYo3DVhdl%2BUumgTBS6BNH2V2WZheGfXJqlsGtS%2FIt&X-Amz-Signature=3276e03a0d3aeb4f982957a8f56529dcc260780dfcb24b0e7c1a60633775c800&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=6ef1f21984293564d8b949a17cc1ba5abcfadbfbe189ad28b4621fa72b4a5ccb&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=54033187e7e90f0caa253b89b895218ef7d05e06135c538496370fb6fbd0f1b0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMJYOGP%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T102427Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCa0ucuNDwck%2FlnEnn%2Bld9nUM8IK7rjIjvsi3hlTlFcwQIgdotFUcYEey3GMRlkVHpDJ3nZDwBDiGAOm0ab0a39xs8qiAQIi%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLJu40ayyQTfloVo1yrcAyNqOTSOC%2FjdflGaIujZl%2BCTaXFZDbF9Ot3h%2FMI7u2MfnRWo8k91RUeohqy4qEB8ZtoOPeGMKrA8gJWUVQxe2El6NF5HAwmCZF3Ljh5TuZZvRDAx8ap%2FdNNqshq%2FEZDYlhxRlc0qYgVpdyL%2B9bZoCEOBWSc55zcbYg5MtIbsdx10FTcThj9qHzMHo6KlOIHPZieTcExmIIedx%2BGffYHvESDaUS9ztmy6Myjw9NlDkwggDDxrgKEFj8d%2B%2BasNejH%2FtAS7WjxkignVax88ipocg6Sx0UXX2tJiWlWZuPiZtnBOjHVQix%2FKHGU8h2IDD1L7ynEj8m27lBS6UT2DKSceL%2FoOp6OFIbepsq1iwctgIe4TyIoHYQJNeHFDmHWpNTB5mAnWgQvY6Pf6IhksCqWRjoyiUTJn48zMZXlbIGstt7tp86zKiDH0mUI%2FvumfRQKro9%2BGtNRoBxrdclXNZStewPtVMEv0owdna7JH5vivm3eSUbfBeAD3EL%2BDSv0V1vAUgvx4HWYyiCotLjyPgMmxGNv4U6ZhdH4%2FqRg%2FUVM6Jxw8%2BD3qo2Jr5LWuNmbguueovGn9n%2FT6nrkb16upmJclJlHbgL3szTbt8kH43q%2FaFfSP7RY4M0f5EZ0sWcWnMIuA6LwGOqUB7KwZ598V6y1bga9iFATuqfmVLVG4BSbRLD3o%2BxZU3hYlGX6Mi4JocWvzoY5e4NU2n%2FMH9WBdsrJrquPMcrXxRaEN8ontNHMVTtM6bH262W5l9kpRZfqXwdhLcHnn7jXZwJpGh70I8t%2Bb8F8EQfUVyrpjybCJVUwT%2B6SgLK8NDMYViYhVCT0osupsUWx9gfJfuZ816I4Y%2Biu%2FUQu3%2FIEnlSiyCKKR&X-Amz-Signature=4bbbe78a08c6aadee1a7667f3232a07076d59bf090490ab655232daa50844b2a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

