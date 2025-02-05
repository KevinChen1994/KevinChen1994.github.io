---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q7X2MAYM%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T162933Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDEaCXVzLXdlc3QtMiJIMEYCIQCu13Ay8QelTewiOZZsJZosIfy2fCiaQttA9m4eZv92EgIhALu\
  vI%2B5VLYoIKD83uPLUeQb5MMGqIGOvNB48%2F7wDEzhHKv8DCEkQABoMNjM3NDIzMTgzODA1IgwE\
  sNJRphC5ncVHO%2BEq3ANg6VNqk1ixVRDxZu08QxMAfx4jkh7XviNMHtgrIh1NWfLQdjpSDu6%2Bq\
  7vQOmOgbZ5orgjYoaSP8FMXV%2BFGUAC6WMTTYWiA3I3PEl%2BQm0gn%2B6vOU2GIQZ1GhbPkBvFL\
  fw5QvpdxMsh06tdqwJgFDfKwTh83HeOiubrzj7uvRBOZuWhCJNiDff3%2BSU7otkf3%2FGIz1%2FE\
  3cjt8hGwxN2up9nn%2FtK%2FarxeiQGu6UpAE%2FXB2doWgnQVeGG7Bqp8H%2BeAvydxRd52rsujN\
  qa%2Ba35dzsznNbbRy8F6owYd6vo7r2ZTh%2BHmvCQNv9xm1QrqnLETLdfNeG%2FXeUjmKFWgjf%2\
  B5AudU6eZOgzTUY8h%2F0Nl4uAVxoytnu%2BWRst4DB%2BLopDzJaXp7fNf6Ed%2FnrHtlOAqs8aU\
  PSxGoOl7OuJM6YEla%2BTyYe3VLM57n8wZf%2Fj1ejjNupf603GbITMnbsBpB5pj2%2BElECLqdrw\
  KUcP2xY5fTB9IaKYA41jh9z9L2dx4CDuOBP8jLp4J%2F%2FSnaWCzYe7QAUhOSbvHE5odNUiS5v9m\
  3U6ZjxRKBmrjPc6s1sagwzkfF2qGFe%2Fm3VkUwLFpUcdr4s8vAMiJ4Uj%2FonK9Pf7g3yMjnPsP%\
  2FeqsyC%2BdneEnwY6TDrno69BjqkAYWGUNygXY%2FrCwN5ZyUr9HUmSDqFd0L9T%2For4f4ZZz48\
  sDDIv9Q82XJclamsZ9%2BiJPIm5j9Gu30BAZ1CnUiFliiM%2BLMyU5LzN%2BDGI5TU6SQich53Rfe\
  KULQ65LY4pE%2FM9%2Fij3FJSyoOcnokoW6V%2BIQmZsjWEQFkMYmuZjAiL%2BN2Y75FOJsM%2BNT\
  x1wkqXVIo%2BvusB3nDv91opB2tRD%2FneRKc5YzO2&X-Amz-Signature=d8ab28e80cd7a7ac19\
  144be9a69317ac57fc57cb896fadb9da0e9b1cd311e762&X-Amz-SignedHeaders=host&x-id=\
  GetObject"
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
        redential=ASIAZI2LB466QLUI6ZOU%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T162826Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJGMEQCIAXXPDoHDKGIxSS1blJRfwF2vZOZPlm\
        rTEXYSQWhO8EkAiBGSye37VUzjR%2BJhEK31GTEcFqyvg1BO4hTrieZQzHfXCr%2FAwhJEA\
        AaDDYzNzQyMzE4MzgwNSIMPdYLSEjHUCahFpVXKtwD5wRUb0k7opMrkrhKXeOX5RTGCBKhu\
        LxvtJsB236kS%2BnDFwJDMnBrLQuDbvCQ19ber5QbqcHfKpD5AG2aN%2Fi8K8kaDpAMVfml\
        5lS2VqTQNuCd%2B0y6pk6HGsQELhFgU7YiQ8%2BXyKGumtJBgCxeioWaLgnIAsi9JTMX7sk\
        y5fM4HIDoOEtOe0Bia7lGiRDCZJGuIJj3G5mGqJgavudukJqIF04JpCMTDjjIVxBPDG7UTV\
        zCnPQDkeaJO6NQm3L6Bj8ESdJoho9w7%2FBYGwJbiIpu2cKeUllcAMch11VJ2LR2wqgDz55\
        x8299cg8woFf07Czogo2VOg57cLgV93jWZWkFl9vI8FzI3SOnp%2FDZqcN8lpwAdB7iryK%\
        2B4JEUgs3Eo2cK0IGRRA0xML10eUSSDS619reQoXOFEONvIKbz4Xlx0VwUJrm9QtrVvi4WZ\
        eNrD2vvFoLaU21tVws5jZ0KVW2bQpIuJqnK5Z%2BGV4bph04OvB%2Fj0JWmMWGgC7YTy4s3\
        nU3hbIwpPAKSfyumet%2F%2FvBxsWnYf5VGIRI6KIdw6p505z1wkjWDHFh5qx%2F1anqA8%\
        2Bta1NN3JjB9mpSDXR9oxnj%2F55tWIQC974VQPrJ9SQQ75b4krXQ211bkubYqB980w85%2\
        BOvQY6pgF%2Bgpnrs6yYFAhh3VmzIC7OHJlpsH7jgLkHZviaXH5rd2h4FdnNxPHT%2BXl59\
        FLe562J%2BK7NMzZCNGv3LFsNM2qgiaVS2dydwNuD7jxHqlFHd9BjFD%2B%2BCeS9wmX7aF\
        bJiygwBZqReJbBEuE8vBU0ZJhlnL5gpeRfLDWkiPnjcEc0bLrBcmi04u27XVX6rBV%2BhH6\
        14%2BtM8gbRBC9M0nZIfQuJGCMBrLjC&X-Amz-Signature=ae2ef29a3c02d86f6a6c8a3\
        10077d3b69580a7f027f6457371c78af617973044&X-Amz-SignedHeaders=host&x-id\
        =GetObject"
      expiry_time: "2025-02-05T17:28:26.164Z"
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
UPDATE_TIME: "2025-02-05T16:29:37.663Z"
EXPIRY_TIME: "2025-02-05T17:29:31.156Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=5f4165bff484a1b1d528ee6db99e8a229b1cb0d82f079c4341865464b45d3204&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=490a69dbe0bfc5924cde2161dc40b8aae759be4ef986cd7eadbb8dde9af8f874&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=34209ecdcc2d76498ee7c636d110243678537042160f81e91ec4c1f108382728&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=aa9789de18b0089d23481e2c8ecb6ae990123ceb5d44e6a72b470aab2e37bf03&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=ba3cdedba078c865f489b9cf3bd95aca301a30b5415ca9c90210d82d26e5a0a1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WKYYBQI7%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162932Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIGxqihL8Uh3VoViiJE3ozGC0phSoCfX1SNYTvE6bxmCdAiEA4FPscMfXYrQb8oChV%2BqC8FoU6Qj8K%2B45J4iv8c6XnjUq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGG%2FPKY6wEsrtqvXVSrcA58sJ7sNv09K8dr6JepQ%2B5941vNMziWjqDiW3TGQ5ir5V52afo1gzKJ69Bwr%2Bh4R28631uJ1QQPa1NI4Z71MZJN5qlbkUE6MTgww8yF0c6wRQo%2BS1wYa%2Fs%2BeP9uDuHRvDsPLjs1gzVK4srYa2YOjeVeRX97mUQwXWMbkjecb7YK7ye%2BThVT%2B0x%2BF3oMAtEVhpJx2eg9XxSuShq3QuRNnzaW%2B2c9s1PIDbJe3ULV5ysz59Cv6hpJ0uYqbQ8qgvJ%2BsKcskME%2FhaY6Lz85hW0rQuo7uWDBP7hUid%2Bf5ToyubKCnPssCCfKXUgkCbfJ1WXwyR%2Fm7eW4PT%2Bu02PuOHBZ4DnwtOE63adEYslzZqAppCRytGXAUFCoaWK7kdoSjmoeNRKGwperMmZJbrIHVcQcVB2nx8oLBc%2BQdQcxT6vTSchB0KeNJgzLT3pbECXW1vZbDR2YmqxZuMHm2mf2fjZg0H%2FSXwxjFkjncoMEaN4oSK4m5zITQqAX9ZkhK4NJ75E749goOtsfV7vpAqLERAmskGRYEjE372tvex9c%2FyAqkc576f6JAcP3vz2I4wUgDKq1plJ8EsWr%2FYUTQvNSnLWybZmHV9VhlNfPwtLAQjNDlzFu8CHesBxQHxU5Or0akMOKejr0GOqUBrAFhyYMmXBEPWU3bu2r2kxAHihr9hg8HCZ3TrxkxeW%2B2nGBCWaBxvwvu3JWD1QJ3ncwxtotvbVkitsUS%2B83KfbmIcr4DoRoB580q%2Bxz%2BdLWxSjmx%2BIUeSKyvVC%2FPL6rT1IvN4xtrz9iTb%2B6k7LkZ113hqayWPb7o03KjcXJV27fjZ%2F7LEWgnYIM9vH39bJP24NKpuZEUlRUeeN1dq4S%2FpiSG2oT2&X-Amz-Signature=b536676a292ceb079e493c5ccf283712787ee36673bed3c788600f4f30bde4b2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667H4BSJPA%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162933Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJIMEYCIQDzeUzHAX9Hz0ieJLwaHCwy5NZ84WIpPFmMIAHGMnJcjQIhAPsGiCvWoYxMHb38ybqMNcf0zyG6%2FXfEgTypEecRlSzPKv8DCEkQABoMNjM3NDIzMTgzODA1Igz23POvsUSAwID5Qscq3APK862VAYwPNwLqVIDPP85WcBhhQ67i6zPxZ2kIDMYAoX2nGIL0fAcAEESJGxGdMMjYwWdCNQVgJCvGqPoxsEjOUbgjYL2EmwITP11l%2BmNLOp%2F17h%2BOH4Sz9kpDoPl%2FqoOBl3wk9hwQBSzd9jbf8w0WovBzV%2B8%2Ff06%2FU0Sf0SpBg1BghHtOI2kN%2F8ZgULwmibOOnsOvEOGTM%2Bzhx93olo49rOkqlMyiRlZ5PyBJxTKcXiyDSBamLsQ%2FuVLarNhB97YYvV1Y35E4l%2BuL3x7Lhj1Ha8Bd2%2F9kUit6w86Xi%2Bcltdr00e5u8P9Hf6rNn8BZ99qRYx4Jk6wU256Q3qjFYY9M98xX1RTOegguWjbg4njEs0%2BdFMEThSbBGJk%2FV4rUmwAq5DHILfkosnLaiREctWY9VphwwPF9ywUNCU2Bj3tbO1fnXPWRwohHpdcdSXfig74OrSjvssMcKRcK%2B5K5x5BZ%2FtZg41fGiAVSVS8QiyASoORtH%2F3RmSCz5gZ4agO0tRgNSkAnROzQKVNPsF%2FnOdHTej9rpZ5%2BNrH9Hu18%2Fd7HFFXl%2BUzYg3ZqC74j5%2BaoEevlmkhZBTvlfWp9bUjHDLs2IRKtXSYIYNmXcMGJZ5yDTzvmteFbHpc0nFBDlzC1n469BjqkATGYWovuQ0VdmXKOc3xYj8uRmI3QmvyMDv1HaPgIVs9R2sDtexXNquoacDcvfio7w6XMOurfu8LWIgxyw9v0CA%2BGqAe0B%2FiZASn%2B7SH4%2FkUFwT7naoc6ZMWdaxrOhhT2vOe4%2Bx3d5AwthhksahzovuaivlAhGE8SlBFOSWT7119TUe7%2BAwKDpQ2bxEqF3%2B6U28%2BmvBRi1P5%2BSLIkIVPwgwKbRM4V&X-Amz-Signature=06bb1bb03359c3d20f51d49f856095b15447b4c7fa9c3afe425f1d554d9b0ec9&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=81be1b267f773346dc911695df08b6d56b22340b80d4c279556196a773b3a92d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=db15e22eb18856401d0d5ccd0847266c7a12674cc58b1ddd61371cc42ea76f48&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL5O2LAP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T162931Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDEaCXVzLXdlc3QtMiJHMEUCIBLRb6s2c%2BCV3cVYYMggG4yIaQXnSGwWB7MCS2vC4nVUAiEAllzmNITwKpAruwvX%2Beiu0LmKiDNuzLkOu4GMgP4zNyAq%2FwMISRAAGgw2Mzc0MjMxODM4MDUiDGWW8IoAdtBqV95MEircA7n6YN%2F4Fshl184WqqAxyGC8ZSI3HhUpa4r%2Bxs%2Fq27mBO6GbcVGf4ifhQ6K%2FQW0qJg1AwW8I6iShtgZlQe2QhbeQidAEN3Y3hR7amRMnqIZSWwZuMowheE%2BervKNmaXaj7lBI08Kl%2FM8rHQ5ycKleIWpGhevtx3bNBzRZyapobFAwKieCU2OdIv8qf5sS%2FIdN67ZhvPPItCCGQrzs40ZmHvbl0BVivU02K0Ve64rPRgDtekK6sdiROUxZrtoIupki7GWlYM%2BlTQbUbBmAOYQB6qCjMYp2Yim%2FwAal368rbxeNCnltfBwL0feI4L5b5F2iEjcQZZL7%2B7cTI%2FiELWSKl0%2BwYq6oowzxmVfgenDHEs2AQ69jSsOokIkLsKwt1HlkcnqdpVXB%2FwybMxV9dNuR4KF9IwcExHplSAbLSTiXLvjrmy2Ggxbe%2BrSujAORZzUlUHHG098pIFJ%2FRloq7ukgQmffkWzo5kf6tZ2QECKM0GAOLUHAIvcLTH%2FWgFF20D6xyapzYmFeahxHdj%2BAIZNJabNFYUEMnpzZXJM9GPUUxZqKvX9LoOssJfACHwEDfgIDueA49V35ggy03reC1jKzlayo1FJHZs7ZY%2BqNmdYczK6eq5gqhlliCvw3V96MPeejr0GOqUB3e7m6ClzKqcYXy023zhPeGcBk6D3yyuKfVEnJN78rvqft5rBnU10hC4cXsK8BfD1ufPlSxrKAMBZ%2FYBCKAshh70rZH%2BsWEuTS6z85cuab6L6fHkAiUWX1wdJ064RAlPEJt169gIeT%2BgIFmsih7gu83VcVtntBgwhCFArvFkhFLsiaZI9R6GWjv481NYEdwk%2FP8qhFrVOWoVfhB0FzZt5wEKrQpg4&X-Amz-Signature=00a3f0924e29b27c55c242441a383a72117d1dc687ff8554dd880b41b47c39db&X-Amz-SignedHeaders=host&x-id=GetObject)


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

