---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QDVCXUKG%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T024812Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGoaCXVzLXdlc3QtMiJGMEQCIDLqUfW1HcgCZl220xCL5whgqwj0SBW0UY%2FONJW9rEvOAiBhd\
  Cu0LO%2B90mG6QdwDvTCIzESO3LzI%2B6rbDXFGpVDNmSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2\
  F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM9mBXlwbAzoqv9YPrKtwDa1z1ws8IzemB4xmovtzWXIM4xZd\
  hw8DJyYi6BGgpUhTyG3zKetnK%2Fzejuzek9xc4UKgT5djiKDO%2Bn6qU4QFXJ9LzXzsJAg%2FnXM\
  6bFJrOg40X892aY1152yMgat%2BNDVZIr2rLEdJL5M4JZn7Z%2BNWB5C4BBeVPQjIOVzfJC4NbCbE\
  INkEU7l%2BHEIBrPFdcEdzcnuBBYv%2Bys%2FGwH0TgYv4CoK4%2BH2DJTeg5ftpPlCn7yb5iVmD%\
  2FB6p2c3ieE0kAprK6BVrsHc5dUqFDvWzoRNyBPKMui2k%2FBg4IYUpP%2BR6LtS1x6fTUqeru7F%\
  2FBF3dtPsKzq1lAqd1l6ks6vImAaV%2FiM9COLWwd%2BjOqSH0z%2F1YKHBHAJhggJ1KvrLitJzAl\
  uoUud6vO8ZxGjp%2BguvDruUB7cmop55MUISocqYLpJ98LUFIdrtEwuY%2F8RenP%2FgXCTwYqEFw\
  zpUfHfn8Ff5C8peOYmP6CuC0SB1Z8wogDVN9eG6FrdpQaYTlciQvnvXQonpRWvfLbUlDk3k6HZ8QC\
  nI0FS%2BoyGGLVuyAWgWCeAKnt%2Bl5pL3bzt7HFoc4Lxj%2FbBMg6LT12uBx36pZM8PMSZ%2FQZY\
  J3KvLn7DKUUnI998fHDJttbXrnk63U%2F3m%2Be83gwhvqavQY6pgFZHsbfvppcvbTCEvlq382CY7\
  Dr1wCa1Xvdj4RESiTLq2BeSfg%2BtXptld3s4%2F6kP2xCFM3VIYtHclHRPuVlL2IQkYvEsdu%2B7\
  %2FUl%2BfFILXd2FBZdFPGgmvbvpqRS5NROUGbp%2B2Dg2REJSy5HJLQYvA5l%2BaF%2FP5O2aC3Z\
  ZtRtl%2F8rje29EHgO0FuZ8OZfqUK1%2FSFAHHMZ16aUwTx5wLwzU3fOJKttZzDL&X-Amz-Signat\
  ure=e7ff4cbea18673de96f7e835a84886a380093aab4e99b11c1b524e22644f4b26&X-Amz-Si\
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
        redential=ASIAZI2LB466XYV5W5AN%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T024701Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJIMEYCIQCV96cWXcDjRYme7qCDK9Eg5gEU7PR\
        FpRhMuDQ93eMdXQIhANisIutZMV33O0BxTCnyA%2BstUbPnI7oNcewM06eS5HpLKogECIP%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz5R6ijhWcygmL2Vyw\
        q3AOICOF%2FT2hXeLpAZHnvWyIdN%2FOCYYK83YEQPvSv78QNoFA14xbYdY4WgKMRzxBqbR\
        JRPVDYQjWOlfAl8RdPYA%2FLg8IfYPMbAEHPDgVT7JuGINfPd6v57pieTFzhiLDU%2Fztm9\
        bmHstuof0bEa8GXBcohUlRA0S%2F41N5pen8UWz9XxAB65qeCszhvGEURkDE5Yy2x3ivQHj\
        iE1a05AVWiyplKu1zu8MbOA3yxm5BICXjbNgbLH4fBx6EIEnOy8uoFTPkjhfQ%2BNBS9Gb7\
        lPiw0JsvspxQpVUbXdFg5AAe5iiI1zgZtKXnjS09nQnubaN3HnRg2XxOwC2O3Iu5rw7Em0h\
        iWl9szgIPUf3A5YI35dVkIku%2FGqK3pSoMHpiF2Bl30iNYVerLGC%2BNJkdx8WzlhKBMLa\
        FuMhMhATtpPtXv55BTlKBnFDvlg4eb1HffvksIK4rN8vPVMZFoR5d2DUjZTKksLhuv6c0ke\
        KfDF2OSk3i3UZnQzudjE8MbRdZgkObOljwDP722r8EnnOxHTzGfvVsZYE6jYfi4TMbux%2F\
        A2fKEeX9aN3k1r9MGtuSyY9tLTykXu6L29kABx5XUzNtSEo6q27lks4b3UqbH5Ged4BKDis\
        KeuE1cQiwtgniBlL9DCN%2Bpq9BjqkAUeZP3WpjO3tkUZ1mC%2FGJRI%2Fa%2Btp3nqmp76\
        IZj7h6KlcwlYyQqZfVpD2O9SX%2FXnPYAua6ks7RYpU33A24wPa1hMYQ1TZzRqjajSEawTy\
        w5DO8IjPSwS6Z6ZoPKxpQl8CAJP5DvuYuehMdhPMK1eYTZxoQ2ptx374m3WLVYQdUxsZ3mo\
        3mlltcxhPPIuNLlnd0qERGQ0ti1RuWwu2%2FJxG52CXrBez&X-Amz-Signature=9c17f71\
        eddd135f2368224b80544f1f61fe1f829512bbcf77db23b9d57c5bead&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T03:47:01.702Z"
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
UPDATE_TIME: "2025-02-08T02:48:16.642Z"
EXPIRY_TIME: "2025-02-08T03:48:10.339Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=a94ebe0e9f29fd0c4d145186078e3910a197805247cdd010c6f421704f2ae237&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=55aa37c74d931eca9acc4546295a81ccb5fe20fb70b6674aa7bf7f4ae44adb62&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=23bfc8c626f1ca485dc9fc17f2bd44d06459e685716f8f41d46bdaabd3e95dcf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=a43ca27818ef25cd83ee3f2b26eca9e1e41bddcf92601ba5628404b84f6cf2d2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=f2bd60ffed8590df2680d849cba2a517277540d369d689c994c5c2b8cd80e8e1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46654M4H6W7%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024811Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJHMEUCIAR97ekqFIbtPnWj6Ae1IHefsqVAHn23B0g1RZd7o0eHAiEAqjHabU1f54%2BSe9zbGuT1EXBTKnZo94zLfbIIFs7rL24qiAQIg%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDO2%2B8cQRadiMNOi5ByrcA%2FyQX%2Fi0NMo%2BNxFVwIw1TWSI61ScSJDd53fllT9gOFWoUw4Tr8ofR9Am%2B4TALWpKDwgude4BE5uBYzxVg%2Bz3IpBm%2BU54KbZ%2FyGn%2FbNeEzT5%2Bv29QFqcvZJ6QbzchLu8RII7TGnrl1SYoNGx1v%2BkQhGDtSjMGJ%2BFQbmMX%2Fgz%2F6bMbt1Z3NUjjVxl6AkPuIY4OXLD7%2F0YPan6CatD9Wb0%2F%2BpGAZ3ff%2Bm2jFmLov1twiRTEu9%2Bgf9Q7sRJ52bzecvwpIjMqorS7y%2F1e%2BxXYdBBCaIQaj9TBwKKkziwMqWJSl9%2BBcOK9BHQhOvpvPGy1G%2Fl4g1qo%2FL1PMLw2cegRgZmYh26IEVoiuht3RA6BaUn8w1wXQsyOFKG6L8xPRXW3MKqYQNRr40JrLJAa4xZSvwTqYdtXKCWelIPy3tzFeSNlds3TP9mgIh67%2B47qdeYRjo9Akg%2F6UUw9nsvIMH7ZKWqPKh00s587RPRoVHTf7ocs1khFzV2DmeFPrnfp2CzskRXzYBhN%2FTH1KEVlqqOEjrcNXL5YO%2FnEJc6CN0XScERPn%2BbYtfwzaE3iPzDmfO8Df4nGMEQs4kdo4QngSe%2F1uXoxrArQ45jioMXCDQROxcCaiuJj3f%2Fo31Us7McQkMdgMMv5mr0GOqUBzSQswxbfXN1tFRlhCiNW2G0FiBNUrJIzmwa5IGuv8koFURQaHer1z4h%2FkP9j9MwSoRhJOUJCwhd%2FIo3oIYxM2JLgklWtDgLxpaIObpJn9Irdg9wzexiMAeQt2dOzcofRZsjPEFEMXTZZtd6akIapSmI%2F6M%2BG7z9CAqLqAFP4BQUkYDqFh2eD%2FfSXH9JNJ3xcnKxMybu6hsZzjRWSqtRXHkLxyRN5&X-Amz-Signature=64ca9ca4ecaab52ba327e1465cf96096ab2de521a3fab0add3470d9fa7a36c28&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466V5OZHJ2P%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024812Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJIMEYCIQDum7ddTAhAKoEg1Q3B7rE9djjo8bfPxi82mZou%2BRwhKwIhALM%2BMVxrKueGjmSVSS9p%2B2I1bbzh3rsH3RsCxyVZAy%2FGKogECIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzjgEYbpDcrdtIMNMIq3ANxsQ0SE3MYI3eW7aqvS0krIRKPIzN6xr4A6KSp4w4RixxMvO95JIGAn%2FW9KhgnZqjpWWFK7iexlHRcDSdDugmoWmJXTF1GACQnODiventW0xWqbqkhXoRcpsCeArk1JzNgdNsJyLIrh%2Fj2cTpbVM3z2XdMtYwMlabwLzTSztLv9rQHliKnSc3CT%2BsUHCapNf89nqrMe6j1xTeUgET06Y%2Fq7%2FOuN10fTsmd9OYgx1nYBrH1Mu5menII45uUIkfcKenRlBEBzYjftM0IBYPBhg5lXCJY3wJJBrG6mXyCXd%2FsEwKbmAK%2FfNxmnytu5Qvww%2FZ69UBrzkGLfiy8Qqj2ca%2FUR4mesrKTB8Hb9PNaMdNfWFP2I4s%2BH6SlVJH8xdlCYv9Uy0QB7325q9gBK09Pc9UHrV3QpC93Rxle0oWh%2FAmL08yZUPGNy2aqCu2Km9bmZaXEITOU2NDOoTBTBISwSGEgv5N%2BYGKR%2FlErq%2B4AZscfflAGZyMT5Px%2FpT0ykXCO7M9XEOGBmDg6kd98UR67Brwf9HxiII4%2Fz5e5AYY4DdODnBf%2ByIwTfpoxQb8NouYHMoKeqrF7C%2FYV8TCmvqLYtlZ3igK845sQzesYamyvWMwb7gi3CeK4jwtw%2Fru1QjDU%2BZq9BjqkAY63prQHug5REtJu9PX7XONfzr77URvimYfg67Hm5W6Z%2BMtAliVr9D3S%2FYG47v4nawIOPMvEBnWjI7LFHCze8J4eywgo7oGEwSDVJvHV5Dm19iYVZj7SJxgevsr%2Btt767WhZ5y6bIvRk6slbWb8RAxxUaVxqzetIksW%2BpkeuSW0lL4e9pO8Es4wuuEli0gTx%2BYO2538tY5Np11QjljLNjEG7xa7M&X-Amz-Signature=077ce711ba77f976e77906b4fd4ff087ffa024ce2d058e0f04e62ce86e6ddaae&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=e675b035f1770ce7a35b684b04ffeb1a13e7b61151145b13c2d36496628258d7&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=02ef53346b1d703bf0d75670e98fb17cd69531284ec1f514501d1c7708ed2c87&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666EY6YYJV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T024810Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGoaCXVzLXdlc3QtMiJGMEQCIEn4eLhKyGaiZkTgyPXU2vERT%2FGGP38hmy8rujdde%2BjzAiBCo4uM38ogPPjdo9r4lFMzO4x9K7mKP6NhDJs3p%2BJwpSqIBAiD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMQGv3tloE%2Fx5Nx3WiKtwDz6zimNAZSigqplZEtur19b01SK9Nh5OAsgbgK0pW7tq7OKcIkkMUD7nwlth0KBS2w5jfX2bYN6P3YhtDGKdmzUlR1PxgMlcYMeYHEUci7CG4Klm3%2Bw5f7GZ66fVUvgWtYq4jkMYe%2FDxXtS3%2FdF2rBb%2B1Xy6ZJzkPq6V2GnU0RNVLjb92%2BMQB1G3p5tHtvEwu2aORILDB6Z8%2BCdaEaVrqi78gDZDwiMFhBtzINWgyzOxVcOUX34JNb0TChWo8HUUZghLyw5jdOv6ucqV853hzbEm7dAv276b3k%2BRXSNlGeEJuUP7ruahMMh3KVKYn4YjtcpyIpEkhTICGvb%2FhBAdVbKuL6d3SDULFmFKRkzLRD8xTXJCaBD%2BUQA6fov9zjbXi%2FWFcq%2B%2BBY%2FQG0ztsCx3bqUGcq7QN6WP2rIMLkZXi0k3NlD3BnVF%2BYj0S3buSb44Uyi9ThdWY4MYGBSltf0i9gt9%2Ftgcj4pHh1%2FHn1baR40V08sYMDgTo9t6jm%2Fy38G%2FzTXMXK%2FKowYw8X1kDN08BWajnHR4ymXx7WliBocpecsUyQDXT1s5Eyw1zZoVK4MuqYKkRFWKxtKhS4SaRxEcTzhMBoDEN0YyB84lLTpwgKPw%2BBv2p68IaDfwbEh0w2%2FmavQY6pgGWoZsNVwf%2FKyAIEnM8fQWD7YuoTmKA4oCdYcLih79PfpblMJ7kUqe5WkxOT1pq85rph%2FHfk39ZxcYMK4CxIfT25ZWB6SqthlVnz2rcVMO9FhLNevIqTkHFgv21vRUOL45n5iIJW2r%2F7laBSOFseA3sHZp%2BqNwI7OZGxaMId64QNv7dPWyqN2T329Txubi4E8Qxu2ruAwDw9c2C8%2FQ0WplB3LZU8qOT&X-Amz-Signature=be7f7e92fc574ac68116fd91bb830cafb014c75515e07134c0ce5c5e05e85185&X-Amz-SignedHeaders=host&x-id=GetObject)


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

