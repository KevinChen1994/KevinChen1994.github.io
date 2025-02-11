---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662E2WBNUN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T052401Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIG%2FfIS9U%2F5mA2%2\
  F4gMm0A1B03%2BcmP1Xj8%2FZH2bAmVbkpeAiBdmY5DByTqpk3JvLxGovphjNmUs%2BUZYY8jN4L1\
  FrDG9SqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMJNhLAH%2B\
  pCjhsL7vRKtwD2rYGhBqysjIpJcFpIkdB539tn0w8h4ZmzFONk%2BlpmHeCNlezKBfm5YI5AX23h6\
  %2FTk6yFSshfDz%2F6LfhNQY5umRfuMF8qN%2FJiXBdAkx5lBTl%2FnRX7lE9wAkgssqxQgB%2BnK\
  N0man7WiXavOKgCMA5HO5nvm4Pj2EEqFYWy%2FFflwBYVc6SqVaw3FA5CEAVtvdr0ObXmN9Vov1V7\
  JKoL2i3ZkCn023PkhyF9ZhsDmqYMgULMuarOG36rkIVWVzpdwQ36KJpFo50wlbDn%2BHipx%2BXTQ\
  %2FC4LeoJJfC6L%2FdNlxCVN%2BWtSk0HEsq4UGNo7ae4nsz4G4WWg93Fy2nXTi8Y0kA0ZT3RWT8A\
  2c7PNp7klZ3WffTalDFvbY2QjX1cYciiIHj%2FzrNKjaDmLkkvXMh2a6BPpU5Gzef%2BvOEvzMyLv\
  6xKsLeWGSFpPASJ14ExQjl0GY3d5Wv4G3pS5gEDWzcYG2wiNg0FPO4H8pV5K2q8RxDYshFA%2FUOk\
  2iaG7zpY6jRilCeRH5OhuwVUTCUfI4fqfg9wZDWTuBunGzeU9TJCWUaC0v8OT5UA2RyiK3rwFa%2F\
  XuTK0QILf8L8vjoKgDcdfk%2FyzPnhETz1HTjMJeSTJnSEtiPkxPMUjf0igMjNqdGYwoK2rvQY6pg\
  GOmC1F%2BvsyNJk4drM1bzPKXgZrT68X0PDBcJfRuHxwZuW%2F1afDP8up2wybnj8lPxDxkfc4YdV\
  MRjgw77bm8AdqyiphOJFuUy%2FF7jUPMgaV6%2F8sjw8hho84iB1uH6JpbLpAN3MyYzsXuMTfhfL7\
  ZOku3%2BVAmO6qbMsKhMs89539yLrCxa3gbr%2BcGeDyiQirtGOySbFNNNBWX%2FVt8FekqyCceB7\
  GTMtT&X-Amz-Signature=11f37968c8720724e5862d947df7c105648ee8e30f4258ee88ed994\
  52343a4ad&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466Z3HGDLSF%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T052241Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CID7C1%2FnzAXCme65eoU85RJf%2FcQqwcv2HNj%2BbuuWtDf7CAiAReEMQCg1IPRu2%2B9\
        3yWQIUBTeCFM%2BgfX5DiOqF3JRLmCqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAA\
        aDDYzNzQyMzE4MzgwNSIMKMELWxQb4kprADKMKtwDj723YfHOYDDlPg7QfGjVIOk28%2Fz6\
        WXNEEiCT8l7fYUmLLLB%2BE1xIIJBN%2B8sTKO5CGi5Mhqa5RZQUD5VZ4wxkOGE5nb3tQNU\
        CT28qnS2tV7sUzAS7wWfT3gIiowTcaEhXCpjtHtM2r6G7Oworee4J9NTfJUzu8vbW0QqM0K\
        XBrRPTJwkJNL7%2BTtJ0gWqfUDGU9QPy3RkuEJLadsJ8x1A1D4GLhbTWTINgyqSVklsRwXh\
        F95LGQSbARSea15Vd1142oclj72CFE50NlaYhmZlYjs%2FCUYCABqByYdlK5a5gttNHE3cb\
        VmZAWwiiB5kCdOwO%2FQuI3Xx9P2ud8cUuPAZ2LwmpZ8k%2Fe8ca%2F1TnrQOxAY8llJZGV\
        MCGXF9ZvYrLfniUu8593wmIGC%2BPbxYrWfbDjDx65tm85j0iPpQi7TKcahkwYKefp%2FQ7\
        I%2FuraFozYJHgMD7T%2FYB3kgCQoEr%2FyqR1hommVTShUJ9GO7PA5X3w%2BCxB3Jj9wcx\
        Ell4g9dlpWVAPpHctP%2BZzCil%2BXRK%2F1wQ%2BM1wsBOh17LV7y77VsFubAMypkjwmJ9\
        PKtCjVRUBD85%2FgZdeBtr1n7wimaYa2%2Fq8sZCy%2BMRox6AHD3%2BlpHp3TcwyRN0LZy\
        NIsYne2U0cw7KyrvQY6pgH30F57wI4Gju0a0a1XKKayK8a9DugJkt3kwdeiOAvJvwiimv38\
        vCARGZ9OLVm%2FPV3aARwGePyRGYeEuwvrOiGiV04E%2FM7TPNbFBiLtPPAUQ9GMIRheM7W\
        MTHHKae2BE035hFb279H8t9h8UxTCCksxqVLc%2Bwn5OepxuHiKjr43%2FzQBSg%2BTUelK\
        s603W5HaGjSbHhDWzwvYYso3S%2FJcFA2LOtJQkRnQ&X-Amz-Signature=cb2eddb0c659\
        712fe3ac745a9579d6da70691cec206645be9911df988c49d99d&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-02-11T06:22:40.984Z"
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
UPDATE_TIME: "2025-02-11T05:24:08.490Z"
EXPIRY_TIME: "2025-02-11T06:23:56.512Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=5eb79426fef2134a034c99cf745667d308f0b377950ef63b5df27eb53b405cce&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=49f7e3e922d4124ebbaa6a68909b25e04807726f3feb315aa4707564f5234f6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=ee907a22f1f42e4ee002426c146fa95f436000c18ce606d4117f73e73844a2aa&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=d801891335beca5e74e47fca4036aaa8a79c398d76ad8adc74ec18cb3a73c7d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=e239e27e4cac212c8c5e00aa65194fe5bf28787cfcd8849eb6271d36229f6ab3&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662XBOVJPK%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052401Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHkJRemIjqa6K%2F9fBRA%2BWB6ovSqxbDaC%2Bij42MZaN7ASAiEAnHfD5I599xTw1KAXj%2Bi1WDIYfH8vpKf4pgqAjl%2BcKd8qiAQIzv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNUwxM9dVHXDbuwoByrcA%2FmTM225eOBLUo0IhMl6e2KKtNgURwqUl0CyEZfa1MjJYbFg8Qsr2mah4qVtBFGhT218B%2F90B5V46dJ0t4ESfuF37kkKllw422hwIa1fXxk4pXxum5yy7UW2x5RgxEFq82rqk%2Bca4zZodxCG%2FX7XH%2BwOOyJgYaogMDmwsmnbA67wsHItZwhSHkfmClcqX5C5sWnxdT3Qpb1Z51nmNrOXSanYsqgvEX6HWD%2BiQstjzcvQAYn5AJW7a7Iw7UerGi7mrW%2F%2Fq0aHGebFxYgFjPiCRvxuap0hlX8QBy9viDY9%2BJOgLbWl43wdflLgc0x6JpoE3%2BmgBstspDhILh6VJX7LdLGNkooeNmyLo2VOShhqcl2W54KKOI3Q6yK3ibTmCN1E%2BsEdfkO649UPqy7%2Fk9clU9tXs2FkYKpXpa3Cq%2BxGtvbTjBhl7bNnRy92X8BGDU7%2FLcNgwNbhkLhIdwfuRDTVgxAlv4QyTvbME3bfd%2By%2FQXZmcONtewegTKf3D2zHmFk7dbYyCJABXQRuC%2BIf3suHLqyZa3UDcVLYUl0CR3UWOkOVhdjX%2FRQpFVAdCWEiz9ltIu6m3bz7967VD4mq%2FzaEsdaZquxv7AeRjLMrkHg%2FKGOP5tlc1tK9UH1AgmthMIqtq70GOqUBRzlSG3k3BXliZV9bYvXDj3s8yqBTTCmlWLuv21TTCODPJzVmostTOgHiYV0GqtHTKdWzvMdozbwNFCt0SD1%2BAXDdMpyFgiwip32BazIzDYFTVwXeBI9d4tulgm%2FwbghvXZ9Qh5c2M%2BYQIwACd%2FNgNbu6VimFqafw5qUseuN%2B5Fww7B6yqUXkTKWMGxlaZxFhcH78zZ0rem1DwRIDrCug22QDUg8c&X-Amz-Signature=e7dedbba836f6abb8ff4e3ad7e6ef00f68b7ff2a91059b8dff0b01fa8a6f1bff&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666446WFVY%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052401Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCPP83vN16zaMOMeRq%2F%2BXEbPqk2mhH2hgiNbokgqjuUxQIhAPncxY8EucdwQ7Td1TuT5GR2Jq6PLswxxeRZ1fq06ziMKogECM7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzUHwxdcVTbf6tc2KUq3APETVc4vZHl1QtvvgqpWVGS54U3Gy41bsvYjJCVjnbXa2WeyO3STPYD0scr11Qq6C01UQgDaeBVD683%2F1eK5uX68%2FpuoyGLuOYMo9En387PTj3ppnjaGV6fYMa0ysIzPiGLwD8GAmUi0A9VVQQERDOKcmJfZhy%2FewIjFZ4bLMvih43zP9IUNxe2uJRwbLGwQ6eO5ZUeV1cob0rMsP%2BT67oqv4yhs30IzSyXKOUBc3AlJgMDtPNi%2FHhYKaf0RD1LVIdCX3zvDWIYfFLgVdDJrmBg0vpZceaIWrF8pPg71tnQYmDJVfOkd9cIPasNDCRkWmEkwM%2BP2gWiIq7b%2F6L8EfQcKB9aq5FuOcAtFrPlctxLsX65QG5ueUB8K9VWKF5aJKvoHISE0BghxrnQJ8siAgPqgWBuGRw42nk%2BzVJkCkkVkDRmllq4dqye8DWTp6Ml4Sqve80EVQvgzFHjSSMD38UORo0yld2rwZrPYnj5dTpvpYON1f4QtlawBT3nF2I7ruKeFMYqJatiuOe29eb%2BYK%2Bk4RUdaQVhBUP5fyRGlIkeYQNlqSqSu22MxqJJDo8vHRKG6lIZK1hMUkLu%2BjKCNMUn8AtXZcAD6ZPKUx5smas%2Fg%2FXa5Zd0caYYMkQtmDCzrau9BjqkAb3iaH%2Fjbb6Qlsu54PYwfudHHOV9bBTJGDPgLM29D2x4%2B9xFeRLPSLlX%2F1Ws%2FZ0ErZ0My5azkwVZfJToSoXcu4rSjLgdtEc4LTVFuFuOq6rr6bw8NNgKCgdq32mYkqM8aX4fPyynwAScKeQtUfd9RTT8ieNMkQok9v8Wp0WE1zlaGjf8mGSJe73dY%2BrGxUOhsdTbhn1T6FYoTImWsto57cB23092&X-Amz-Signature=e0eefd5a5757401f81bf26eca74b63be831e68525e4b6774aba4f19303c8ee7a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=0682c022f6af0cd53f36f95180d15478a2ff303b0a65926ff6dd8d51cc10d399&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=35830e3d50b34bbcaca1e5b1998cd7a55dcdc783c471424b79d065969461e349&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662MA2ZPIQ%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T052357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDRZS%2B1zLgZp0FEu7MzxvPKwXr3tE4fX2OpQHPV68dk3AiAzLdHEiGhPh92WHkljpgt92pxTs2o1xOwkEWiCuOi%2FkSqIBAjO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMctY17Iu7tpHuO8WJKtwDdi5ABWiJkBK10yll%2Bwg54BT4autw3ZosHPTiArDR6CxHeXWppkhuoovyNjOpMlbJVYGwaNQ%2BTqEK8Y9OCpTGi4D65io05diQBsOjc5RmuMxaG3EI86e2ocFmxYIRSJlEG4MvhumSPvfO2hN%2FSl0IlJHeUjhUmZEuPBZovkD1LquzE42sCNA9RsefhW1VdcCn13tW7dQXlEMCtjasMk57qzQx9tIzeslSNfb8A9sQSrte6Np9toM8dEbxtQfOtSJSfWCUsjDfcJe%2BT4LqLBTIPfrAh1p3MHgnJQldFMlVJvTU3j2j%2BVV7ukShWkCra8qHUvUI8rdXjRtAlDjy%2Fg3MPmPyl9SSnPUodD6vDQJDDN1QEnz7AqCG084itTOvQnrPrdq8OPMJ5TDIIuFLzvu54Hpp3JrfkpdqcMTiVe1gyvef1QpQf2WHkmURoK40WUFSeh6IuV4ozhit2yLBYvMilS%2F8%2F2G%2Bnhrvjn5MIJ2d2ULhn0rG6MFHvTU%2Flf3YjnYiOJAAXJL9c229QZIJ2t7YPNPNF1q%2BlYJkFebfYjRe%2Bzh3a3r1hY2IzjeIwN2YHaVt5QuN4zKgGYsbL6OimdQZFzmF3doSI09uXJzOmPefJijRv3xSEmprOC%2FPacww7ayrvQY6pgH%2Bvfg%2FszWto7%2FhZrfC8yejrGvEAa9qPTyDG5wII5r2DzKo69rKeo8URkacMoNuuYTRQRbeeBp9UCnRiLGXRvXYjbTkH4BGeg4eiyLeYUNdf6Ez1Ii1cdgxcU4rrgIhErzRjCkQhv%2BsfmO2LMjDdy3ELH%2FJ6g4oRRWoAjujiCzPiZRpA2A3kWKeKQqtT8c%2F4KxxAfqlGYNUri6LUVlP6%2BZ8fep4ccQz&X-Amz-Signature=61a0405c7579d255c360cc657d46a6f85c5ca77bef1f0424df106341d91a9d5f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

