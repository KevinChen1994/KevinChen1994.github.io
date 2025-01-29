---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YYVIWFPQ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHwaCXVzLXdlc3QtMiJIMEYCIQDud36c%2FIknfz8BMBPxAX%2BZ%2BYETJt4wXpZtc1mlkKFPq\
  gIhAOnX%2BdM4uhh%2B9yzWRLulvd%2FCzUVE4o4BWC2AIFKlN%2FQ2KogECIT%2F%2F%2F%2F%2F\
  %2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz%2FlbvOjr33zi%2BHZ5Qq3ANiEAa9%2Fu4QV\
  xt06vX1LEKVc8s%2F%2FPjGDRFddHyVyBCh%2B4aEdqa3o2n%2Fb8FVJDit0hGIjeer0ZadwwgOgN\
  %2FS7k0kUostx4E0i0EvlByoQ0Ghy%2BFBy4uiOOabBuHTmZdfpIZF%2FIPuXso%2FeSDLV7p2u0Y\
  gn9FTd6WzfJ0RRGWGT2kCEYjY72Qcn8sH7swCR87RsKZpVAWK9bW2tzIC0D9Xx7DImFhlt1TPQW%2\
  BF06yRB7QlT3BXJOCUzaeFlbbBrS1c4E44b5%2FYI4dgcNBxvQWraYY04jNcZ7YBQzgKDesrUYHFv\
  e2musLbU8EP%2FtR4DE6QWV%2BXUzmWzqf7zcBODwgYpS1m9nRePTpKWxdodn7qe%2FSdBKB5JJ3t\
  up3RD2rhRCVRjR0iwwFVXDTLJ1TCUpK62h7wffwIApBo0RyVI%2BxFvHypYvJhIC1csAvxO7vI0OD\
  eD%2BNa6vAFcTeZXnLGV1BuaKqSdWn3VoIiigyi64xY0KXAlOrvdRTYdenXCg9O%2Fqc9oj6HxLuB\
  bimZvMuMvXogmQ3wf84Dwh0Qpu4ENPDe%2BeRX36QjieNAx0UeUaNu0wHrIRM3PsUm8tQebvxMs%2\
  B%2F6%2FsnE8Xs%2Bzu2q9PUjmXDiVwdI1FLC810lH2JERSOCRDCDvOa8BjqkAStMs6U%2FF%2FTI\
  CH92C3P8pzGdzc4KzMRZpJTWp7kSUNH4Di8bOoJRKfzxPSdZhuo8vhA%2FnAe0e%2BAN37DowOit2\
  zSZuJ7%2FdfKxTT7EdAaZoYT2H0Euh0GCXWWWr5ph1heZCZK0jDInpUFC2kT1loHF%2FfLBBHd009\
  Irif4v5hIhXXBcQyfe7xOVz3lV%2FCbsBDdD44UE3utexV72WbR41604KyAcLtcT&X-Amz-Signat\
  ure=ee3a93ad61c35fa51afbb6da98c2b83b3c595c635e744fc2ce32b9b474c0feaf&X-Amz-Si\
  gnedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WAOJ72ND%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T042541Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCxWLh0kEN7pDKh%2FacE7udD%2Bk5\
        vcqBot8Go7Tngv3Mn6wIgfSPHrkSUlKdwei2AeyPFwZRaNQryCaH4wFw7DFsUGOwqiAQIhP\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKM5E1O2Q9rCzB5rB\
        yrcA4cL7S0JK09RzcqmIgHptVZtxPJfgKVpnRMFcKo63fLkpQLSMQ41%2F5n36h0R08NxaF\
        %2BlBKp8KxbO%2FDZ8ccjwJS8OqQ2vFsXca62cjqsS0nLn9V5OeGk3UBh1kOh6xFUXcIqI2\
        zFoc24qZYs1Z57YUlZW3zbjpGpi0iixhatkIIxl%2BpQt8cgdGFycSNse7%2BbxbVChcP9D\
        %2F%2B9Ow47VMFLpzwq%2FLmLhdHDvViEiJIcqbc8zYb6uupBhmF92wSlWLnvQDDB3TB9IJ\
        SiGO4hauD82fW9VwhhqpBlirXMduvOdGYGw5nCVrK3%2BFPD9aB16xOqePBOzhrgCNePx7r\
        wWmbUsaKPS4UguWjPxGW96ldrpvrF8ZzoWV7KExZPZS0B%2FLAXVWBPWA0GyMmM4BoECM6t\
        EK53sx5F2uAu70Pzgj3fCSasaX%2BYx%2FC25K2FeYDaBpbc9%2FvIlV9vly8r9X%2B4Nc%\
        2B1lo5mFZdTSlQvgDUj5LL63r5ezOuAo3IIJLN3XhnEGEhxqk0zaViXCfCBzxT4nwvhzZlT\
        Ho8oMa%2FCXLSYFlSJljW2oFmGkVNKNxKHrWcYZEX2WdnhYimsoQQ748loR8E6syeTvAt4C\
        %2BMNQcBRqS0Llsp5%2BjS93pK8BSIdTUbxlMPO75rwGOqUBkEm9QBHIsyNMAL2EapR27sH\
        zVErYQKgC%2Fzbf0lw7EXOiRPQu9g8oGjodcY%2FKgsTLFQHp4ZjNPHZK0GRyzxlGB6DgQf\
        tb69SwW%2FUy9iQWviL3UwZHFzvd97Ux18kkAGo7LtaRvRPTQSu%2B%2FYP6YueRGlFFCjb\
        jlMTG709jg7DFvp1z451HUwl2TPPM8Z5HXpGQtJGNXNWmNLX4cOWgG6YFZRoNYoVc&X-Amz\
        -Signature=aa56c764ad29df093f9b18c04a5f49d92bc644c6e30f6072a3c815a1dd5b\
        8009&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T05:25:41.858Z"
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
UPDATE_TIME: "2025-01-29T04:26:45.967Z"
EXPIRY_TIME: "2025-01-29T05:26:40.057Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=ce045e50aa11ef9887fb427882ad08b1c117f1fc1449e54b93b7be6ec8b6866e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=6a29cb7bcf1bcc484e10c58c0da73ec0fe75ef733d7fe729c69ca87d27b8a929&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=516014dd193fe4cb78339f5f9a664b18a1144d82d92a967f11f68ad360ccdad9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=71ae08b5fc7411cab560cd5a485e44403fdf9b7f44bec1f7b6f0cf042cf99ec2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=3a261280670a257d1c68e90fd9bddb0a53235f62b174b8fe5a60bcac76f4d7e7&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46673N6DTEG%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042641Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJGMEQCIGNLAY7k8e5Mgn%2FVjgGcnft1Wes7JyTXD0ZL%2BspGG8eeAiBU3ISN4W0BjfnOQKJE4btXOiiiYwMjiy6oJrE9hlMiWiqIBAiE%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMw5NUi36pDo62wOMjKtwDaDG2V2e2oc4rrcpCw3t7v97lyriBZmwszXeeizWoeZ1OuIbcKDXgvEhY68ZJHZPiBXOa2YupLZUCsXosq9voWZxzgWOydzmHUByulvfB3eBIfcF6NGp1%2BjRcoj6P3JJ0qLD99mlN72CF3XQaQBEZoLU%2Bn%2F%2Bu0kpMR1Ly%2BHeDD0iY2GIQMHP7fARzYXWQK1sRJmP4QCt3h9TqVndU43PLjO4OxjS0RaDWhHQo8PXkgEUt924q%2BwL2apeKNWIeQgb9X8w7q9MROdOEdyumkTCV0TQ%2Bk5qSggVyQCEThDKFUqfxRcyDXClVeaoBOiSiHnAxfkeq8Y3eoPHJkJEwJlLGNpnasM5%2BHlBZFOV96O%2Bw26mT7zUpkKriy9sMoZf0Ff1b4F4jaUX5pwCDkcM6mulRWYpr91lTgG86iNCmTm14axYw47dYYO91XssZEVJu9lgN2lX%2BOFT57dmulQjr%2BsQBeb%2FFKbX5VpKvUSS9m9XGSJS6VHxOvdc01VgoQggKfATiiYB0hszg5LMWdnIAmYu0%2FrUTPVpew4scRkAOY41JEaohh1RjuwAZFFxAOt%2B7k8nG7CyjR37rAdRk%2FWhGcLND81niB7A%2BSRAGzzTN8ayQ6XqMyotlsDfunzK7Facw6bzmvAY6pgGZL4k1NKXlCFsvzq5IcPjqndGerUQwjetI3JYmo3BZyWBgcs%2FaEDCvhTJ8dYp5sXCpHryfUrt7y%2B%2BFG8%2FoHPkeFYLU1d3Ux8nlYyHpP61lHmpnyxoH%2FdCKviUpznaO5Es7q%2Ff5slgJd0cFm92b4wTt%2BKHfhSYI0LvBeId3PiBdl5OEN2b2EXD0OYg0wGPZQFjiZOamzLnDPIuapvVAI3jSAjGvkQyT&X-Amz-Signature=5c197533663a3a0385708f302e4bda80108ab868b4a7db49f2773ed3907abd51&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q6X7TDUF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042642Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJIMEYCIQDDLxKo%2BNQ%2FeOWJZqpJpbLA1oStcgYqXeMwAdNUbCiTngIhAPXBKLIphIK7bhm8GnT559tRvDGWpH%2BMpE28x%2BLbfE7aKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxNrbW1l8cQfIeRVYQq3AOZBt5sWT1DlcJDaQy3PJ3Y9ZpKNUwxPuv9eALEv7fObjf0%2B6PL6F0115u9aP8j8O9UgJKr35pPUOav%2FzNcswJ9TLzeEL90mR4n3qPnsNckaehzaTtFfCxYLsKFEcbWRcdjBaiKLucaLCUyMcqj1vpuwSok6f2IJ03MxLvYxjpHPX4r2%2FZj4%2FmDT2cbfPkbT%2BeMnkfYWAVunS%2F0LQdjJTMNq44roQdthez0yy7%2BfVGJIDitIMOl5KawTVzDLQFPDFqRqk%2Bmp9TADjh%2BXbAUviZ5JsdVpRtz4P6r%2FQBbjbDUZ96%2Fy8RSTYLF72u3q%2F9EtIbKmi6asXGPEBux6lAGSLA75P2Ug9zLpQ7%2FzVOWPdqSz26FapjZ4Q3HPvGWJoUNSe9OZ8pvYSb2kJHpXUfRQ68xSAQtVObkBt%2F8smDdWntihF%2BVuy7u3NwhQt6AkZbbVkJ4nJCZMiJv9%2BEfZ3IhdQsckoTf23sf7uNDEme9msIcNuA6C6FkDttiE1%2FPQk9aZxQ2LbfD%2F730HnuCpwj8sfz79if8rc3kA4Bpu%2BxD88hRN5DLfyeIfMlLYnQ5K1jfBvErVkOuQ9fcN3LSiZ9gpKc0PM%2F8tL%2FzEG%2FYH2E4jcItshWxy95wtLxvMULuzDCQvea8BjqkAcN752cEeQQRoH5DEu7nO%2FY0G5h3z1JgkPh5eoRej2hwWMyByfffjaN%2F8GQ%2BMBs0a4swvIe5gu8Zjs2fyec4KNIzj%2BKKFo6Z5BlfF%2BoMhc3cZc70jbZm599bSN3cDVVy%2B9OuVxc9biEARttY5v9x%2B3YPZDpANa%2FWw6tm9KgzKfkr0x4FEv%2FEzvQ2A%2F75ndp18u5cl9pE7pRC1AXjmdkLod%2FUzng3&X-Amz-Signature=db31951042484a17117cfdcb6ed576c800af5ff29472c7311efcf8eaba34ed0e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=79b5a961001142f14869d4184d0db3c03411d31251fc4619b926bd8dc4f43c7d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=19953214b7f6f2b300c5dea6ba76262d1a3b669ec5bbd443ae4b34bd4176cec3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CLVYCJJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T042640Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLXdlc3QtMiJHMEUCIQCX4Jvp%2F%2FKPjjSVmoSpYegzxOKqmP2lP%2FQhJr7KRbAfaAIgF68CmyVAS5Pct7ALb8qsXVOG1TEsgEO2PWAFCK4lNCAqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKap4MUHVLDuxYNI1yrcA3DIiuWZYLyWhFIk%2BtO%2BurznrhvQqgPA5BTMgk4wvz1lUoFISktyKK9t42O%2BeTVwO6wRuMF4%2FzqVbfvtGw77ZHF8KJI%2FjfVWnO7MmW9da41QzzOnm4c4TaFlxswYJGAN5Y3zPQifLUI5QafvgbjLus1qG77pYbD6i2cd7VF8VM%2BjID1Ux42TfvO8bDHWQpKd%2FQMSq7pJ53XUfZ%2FLNYLCFYZpgT%2BsP9BtDIrcwI%2F7NjdAaj7FCzNbjh2Qk78BzhiTIx9KGn1oBNUl0Wz6mRk5GH1IuXLr%2BG0AS2skYHLXzTUTZkxFb95M5XxFaZLtEzuRKAMehJtMxF%2FD%2BUrsCrXo%2BGAAakJUQ2HDQYeg6a5B0Fkdy%2FY94hctj6ZVr7V9fe9hPTMVLfut4PDXfzctNAVswjZu0ij8fVLyRzhowhczynOwm99cUEdTQgVYzEmHazZKQaPOoRK9sL293AB%2F37T4ZEU1DXpWHOcUZXodoQDFVUucleleldehAz4RZwnOPa8%2Fxf1QXZF8xdskVZ30uVXKqqID4iMxMMcAOTUJ7LtQKVRlSNQY%2BJp3wg6h5uBYJpF%2Fa629NZ%2FHwF463e3kw7B4jG3eKVE0ZXUCuGNIie3SoJ9bhyatFHPRpHqYm3RkMIW85rwGOqUB7zJ0u5wMgtAADV9Qsg36LQq0Y5t7hf2s2DWhOguVqPnrtE33lP%2FVk8zrWFGSJWdqReSCXyIhXOzQAYTfvN%2Fd2YJhemfB2cLKPKsSpGWVJaFw2URTWBJIZ8SsLp4kjONmHk7Bvsqqg39pta8Fcd1WX8itbZQhukmQxrrJpiYw36PWizNL2iypDl51lElGl2gPDk45Td8h4zCZNfBMRDerlwkK5Azx&X-Amz-Signature=5d79eed0b7dbe325709e23558f0b372ff26565db29daad9b1832cd4e8cf00f21&X-Amz-SignedHeaders=host&x-id=GetObject)


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

