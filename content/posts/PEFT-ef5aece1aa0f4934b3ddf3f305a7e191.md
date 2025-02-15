---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WHZ7YZ3Q%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T232044Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECcaCXVzLXdlc3QtMiJIMEYCIQCkUX3CwkyIaT4YtCDJJq1ed9qf608K5SvrfZyogDvC8gIhAIw\
  ifsHhAz4yfvaqzD%2B0hF4x5dlv9hdotQrUFthlS5bhKv8DCFAQABoMNjM3NDIzMTgzODA1IgyHsQ\
  yDRny8gbk9bNgq3ANocaFemwnto4yBl174%2FW90IHvl5IA8TnhK6Kvn7rdxZYBaHdnU1Rj9TKzmX\
  PaMn6SZH06TPinBP3wBCu76%2F9Blg44bTIhTUiNUjjivW5yub0CKL1vMVkRoY%2Bb4lhMHsyMZEJ\
  ETD5DdVjeMn7fciatPHcRSMrKPbCRwr57YEliOm67%2BHIcbV4nTY7Ag8IgN6humo0R02TwKfYWml\
  AdidhMCX%2F5K%2FPMleGeUt%2FUOX9Zdv4Hu8RN%2BRphHSBrvvGL9RKx3O0exatHnoELEOiqxf9\
  mbo6RMsolAP8rOYja0KAW4sS2wR%2BJjmFJ5vOTeg8ENwpYNKMvB0ZpzMVh7yrhWDu9juQqNd8NIO\
  hMwvGyV%2BtRlICEXzlmPKgvoY5f4r7OC8IFGG0quq%2BCjGNKHZNRjhApsE%2FDSJS5tFZsEEHi%\
  2Bb2SSi8OyNz%2FTWN2NUnZ3CPiOI27RYjl2pm3Kc%2B6fwrx%2FFzH4QKa8fWp6P9xlTEOBRNL9F\
  RJY0CBIoW4HNn4Yp4wNOs5%2FE5gd65T6fncjul92CbJehfRWjj7BgZL7X1rJlYaBxJeZbdERi%2B\
  DhJ7gz2oJ08UYehI1eOc3uXXMG2on4jIJ22DU7akVtswcf7HAfZZOIPw2RbxQ6W7%2F2He%2FDIDD\
  GrsS9BjqkAeBDq3wQmFk2MpNCwB8i%2F6nB4DSSiG%2B9EK2cB01wSGU0sn5FCjfe6%2Fcnivmyez\
  ZqJjK1CCNCiTXx6kNm8YnOjaDDK3o4ZqMUkzPiJnnP1o3c%2Fd6h2%2B2JbmHT30mq6Z7GCoZqvoa\
  BCb3k%2B6qMRME8T%2Bs%2B%2FWCAvNA6Ri3fhgaNJewQlCYhuQdlI0wXF%2FvHVVYYLyW0%2BHjT\
  qsmJC4c2Rm3LQ3%2B9wTqc&X-Amz-Signature=5e80910e48e9a4b2b3e1e5f28210c2db9402ca\
  ac04301614a0e2d2acb52c8d7d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466R22RIA7O%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T231933Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJHMEUCIBTB4lEdmOLTYah1uoff5sDZrVL2bkI\
        BYD%2BpyA5xTCMOAiEAvAxLgqG2hqS%2FmZD1llu858AmLM62aY9TRSDHCOfXPa8q%2FwMI\
        UBAAGgw2Mzc0MjMxODM4MDUiDCDkm1gbUY8euvco2SrcA85K%2BJkRp5DwaV7ojCa7dFd%2\
        FfuduE9gUF%2Bk9qjqMRohGtca%2B4PYPkwGXLayBuu11EpYfNlfqv3esTB9sBlt1yS8cPf\
        CNBnhkbfZE0bhsKl0D%2FsRZi7%2Fk0y4pfnKHxzg1xkpJV%2FIbjz4wi7IiQktveAP9jPl\
        i0pH%2FVMYktsdsOSz98nMDO1ZNuIn6s%2BnGlgimY0i4gIvbc%2FUsObrT2SJ1L7Il%2B0\
        ZxTEq0NUrNs5y83THjc7Z6THM6V7IUk5PQ9IdKPDnRnsucNkjqfO8buapF4geey74bAIna2\
        eNXriqaKEM2pG9RuaLaK6eqTmvwk%2BvRmZNKUiadaeO8iAjMqPbi9BYeibBo31uxhMzsm5\
        TR0NBvv6%2Bfw4GlmSrKqlQhxGgphR%2BjuSl%2FXJxjMoMfnrjDy7Rzscyv3BRqb2JrWVU\
        7yy8ma7TTqNF1GNIJ2XUq5oChqZD0RgkZBRVg1HTRmoG2xFzAHMB3%2BTx2kXiGUs2XxZA1\
        jRNXNzK8%2BCymi8ktz3YfVDP7%2BqDPVgKCOHAtc91Yq9UeXvNW31iVvBOWxNxecYH7aNI\
        rdopPqlj5URfyp5dp7Gq%2BWi23C4aJgldFoRG3iVYtgxStOfuQdhkhfnagFX9HITgJpO80\
        DHMPJKpGMPiuxL0GOqUBSMKQTL0UESs4WhIxZ0FbYPaMjAgmZ7ybYzJlgPnki7BeJJ%2F8h\
        BsEjfG3dJFPYiozIZQwNfbYrLcAGTU7sD%2BJHeGvhR5mc1hksew%2BPfU990KCPSlp34Wm\
        PfFMuUOfl6518VQKUiQF4rTeoRcBQEVwyDMA%2FUciKjHMmxpYNURiUwagDqX%2BldA2NZC\
        %2BOTHf1kE7uRHQfLqs9VVqrNxBF7qG%2Fi1B3QGR&X-Amz-Signature=ca77dc86e0741\
        cffd35a8961a611f3cad44ecce9c17f8d9192ea4edfcbe70a3a&X-Amz-SignedHeaders\
        =host&x-id=GetObject"
      expiry_time: "2025-02-16T00:19:33.782Z"
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
UPDATE_TIME: "2025-02-15T23:20:49.627Z"
EXPIRY_TIME: "2025-02-16T00:20:40.964Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=642130f06b4ab3cde16ab571090f4672958cb56f5749725819f3ccaf7a128d56&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=03c83c1afbdb842a247f9bcfb3e333b69a7be5db5c6dd30ffc3bf822a72dc5d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=41f149407e9b18925a770685a31061fc8e69f94d3c5cbb858ff5e808e0ab7bb4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=2e5680d4b78e518196cdd150e83c3a714944c005be0d7d98e8dee77bd842435d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=77581b2d585a83d0458303d10cfcab17a50925db92d6bd4682f3d65ea8601f2a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662ZI566VV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232043Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQDLmvvCthcZlXpCi5P8RTiF1IYWqiWixvqBjXm7AlOO2wIhANqcmXmf3oaXHbfQ8tfyxLygo14i1eWOh7hXlukL0qOjKv8DCFAQABoMNjM3NDIzMTgzODA1Igx3qz0wrn%2BXoME1Zv0q3AOTHkWt8Emv58c3dHx2mT8xRNUiIMlvvDl%2BMg3bB008WNAJaJvXpRNQ8Ra2LVTlvIe7wAOxdEQB52S38OdgKOiG1XxjBADogv3T22%2B5AGsFlv0VQxZOhyBTEzdEaAxREgO3lDoMTBqyDhMfzuy2ezUYawglc9%2FRnvEK0uu8wsiHCfEXRxT4ICaFGFTrR7Aqh0k47VQuUDBV6iZcB%2FXpuyKw6ty5zn0S79ARNYWTXr%2FmH306P8JxwO4lo8sGahuPhjfotb1W%2FWQYEjItvOkusRB61Eqfp2ZtLI%2FxKvOAGg5dYhdAaYweIsgpvPdOARjiS7CYMxdmdhOnLv14tXscJHb0yS%2B5BngIVKQx30lozviVSkd6UVREIXnXg0iW4c4CXcqhapDBBUdF1aXi%2F6RagzMGDi1tNfLiAdDiXkEjyRoUEyZxTX3FpS9GeiVweDHU%2Ffg2%2F3gu8chXy4eM7vhVowJ74UVWETgUG7R2uWV2wt96GFwSQt3YGV7CAFNgun%2BmnSf4fN%2FADclb%2FMPjscHNWaSYL%2B%2Fj1O%2FtCUymck%2FJXYpYVdV4NQC76%2FR3IUIrbzqFiCQodthIETW2kFa1go8AhLZFj2LMHFjUmUjd3yeYZ1i6a%2Bl7hmsSxgUgj0hmlTCprsS9BjqkAdDTHfkFtJkGlYH9fTECnm9jY7mpA4liIIMKen79a4uMZcYVcLr5dho%2BD2oc%2BauCQfkf0Tc5jM3YOJlGImbhQ%2FA3lzmyRgCpiyH1ZE%2BOo19Gkl6k8%2BMoysWMdtXTPmMUPgFpieHYlgmzDeY4wncvxS4xZfpoCgAfdqRhoeyXCbS42%2FhBcfxzdcZQ2lKyOHCUfn03HXgiEBe2WPjz5bJoiCPiUiry&X-Amz-Signature=bcb47717e71b6aa9223bd0e582a6fbc650da312cd98e8b05c619374766101bc0&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VVF3DOSV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232044Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJGMEQCIB1ZqDuaoyn9fNREQzbfg9EjoXDN7BkDvoz6cZfTT5oEAiBEboi6bn01AU3JUWP9b7eg6t1fyP7rIkNxjBuSPlALoSr%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMRS5ZmpP5TtelkBOSKtwD7I%2Bjdxt%2FDDAZce2B%2F1QZoj5jT6PI7z4Eq7z9kdsACclezEbPgvG8qDBXif5dhwZssf%2FuIz3Vk8r4Q5vNysbVYNv7CnrZsspvjijNWXuNmViC5%2ByKizUvIQ%2FIMiRSlTn5uGCDXMOaPNBnszV1zQhUP4ifhqSCQw%2Bk1QwfbG9HrShnNADPAtNRBfPum%2FNTVb1ZKPtiGZyXVOR2O4%2Fimp7m1afdAu46qJ0UyqFv8bZfJSSrn9fS5xzozcl3DD5ZCbJfUqM7uVqSBB8HZydkExAF29mgYVcW4dXQg5iNJSlXVJOkvZmms%2FG1yiBDEY%2B5kZFvjCTZGqw%2B6F3QZ%2BECTCHVzkSrzmJQEszRBPP%2FUHp6siPTznMWSdAd8%2B0tG46dNgAa7ZBFP8Xdb1mbyRlAeU70S5qIa5P0J2Rcix4MOyg4h40qfpC0Uzt0ajaDJ0%2BWHZf7NlQEOrAAFyQORwL3I%2BCkS7vPLKzkp2NCo49cMpBL56Tz7Ow%2FKV%2B20%2FQGhmwbarb%2BuNiioR18J3b2VEsS5W3kSBpXvZ%2ByQu2N3QUlYsA0IyLiMF45A8H3NAXSRsOs%2FjgCnLiT8q8h9GGzt9tAeYW1MCVWWDnzAImKb46Wn43i%2FJX0COBThfCzNjrM9N8wja%2FEvQY6pgE49T2s7y%2FG14OeLzq0UbT4MUnEsW6pkkSZoMik5WxoT29kQ2xq1yH3FRPxEFOanq5MkpqQBHGEl8efl00FsN%2FqqHWG5xPizgNIMw2ytCa%2Br0SGT4HQNx5%2BFmdarZDQlek3D1gVz%2FhbV6CYdO3VmbRFo7Gg%2BuKNkb7dmxIxpnXRNSU2DmAwGJj7LRUyFwYp8at4qKbNGPebkWAwlMX%2BG4VUUfjphkGy&X-Amz-Signature=3a0ed9984773d00ddc3d414fca30ba55b0755c4a057687d752bec4045c9cbc97&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=8ad89cf4e1ae508bea06319dba553cd73e5028bae4cfee10701e500a443fd582&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=ed20b08bb98d7be71199f7f3cd65d678042ad2d0087e0878d97b8a1c2a149d40&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SSNRBI2M%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T232041Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECcaCXVzLXdlc3QtMiJIMEYCIQCUd356yWtD0yOZoMLKKsFEfPLwmlZknpCZ%2BHmh3B1QzgIhAIHuBPysdzTv%2FUZgKtksTnMgt5zjZDAKDbJQmBIn5wmoKv8DCFAQABoMNjM3NDIzMTgzODA1IgwxS6EiI61BW%2F7oI94q3AOCVMHo7EVNh54sUFout6uS4iKfGhseIm4fLT%2FdzX3FiSaREL1X%2FKwJD7Vai7%2FAxitkKb20VRRMy8Tpvql%2BEebT5%2BcCk5zFdkemi%2F25YEHdXF18nCOdVwXDAcEhfIbOi0BhAp8rv%2FyGJWSmRVxGt4Nx30%2BLKno4svHon93U333CD6g0AkFbtX82P7%2BobTJJpHkxI339HEJI3cWvNCkhumt3OsOmACIhyZN%2BzsmrTgcorN16UkvWGvQoQC%2FQvJxJ4Vaok%2FncheS7odWfu4HX7%2BdaVDiB2oY%2BUnDXqFwYIbVXiSeoq6m3TWmvUqv4VNHZiOiT91yovssxxlFlEy4OOH%2BJ%2Bwf0bROULJz8hbRJiqQkzBy7Pc7FI1yIXLPZLADuRGbl8UEiVoHrJKRlR4k2DyBWU8hj8PfeyUOzPmzjgfH67iFMJ3voUBDRN70bb94riepupeG%2BJXbUeyCcvZIQlWaXx3zU8w3XX9mZWTXSx2Rx6WGz0%2FUpMRnS%2FuulsWd8wRpuLhZ8s56UtGGkizBnogehoLkNZPLk36tbURzlEsTh12rYELd6XiZLLt%2FPMyVmkvyBHVEu1eqnWqY32%2BtJb3BH13Iad3W6talgVld%2BbGLyrUtCJE8njY35laBGFTDPrsS9BjqkAQhd7HkH9f3BAPLzJ8ROoRgBVI9qjho%2BgVpmxstbEaBU0%2FZbFYrtUWqHmVMOTBtliRYI6YmM043VBwtsiHt0mqPrPAmSIqiiJX92MNYk780rJYZ5NvVZ0BKr9pCPh89bv0Edk4dnaNgLfYXuqOea3JTJjgvIGQ1WeN%2B%2BTyFO%2F02a1psvtHM0EB9WrEPCx0MTWYmdLm%2BBgJtsTAcIscJv3yy%2Fhw%2BK&X-Amz-Signature=cd47842768524a22051aa04ee431805544e461d0a6c4e66f27f4f95b4f165cc7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

