---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4667UDUSZ6C%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250207T142159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEF0aCXVzLXdlc3QtMiJGMEQCIDhDazulgu%2FAKXdSaWuLwP%2Fo0Vyt3%2FAFGt9Ns1PtQ9LdA\
  iBrKYgIs2VXv2nAJkOlgKgjDEvUosOZFp7CK96StZlagSr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIM\
  fPt022VUTayESfCLKtwDPZo964C%2F6PHphttdDjRYGscdfBwU4ZsO%2BDer3rDl3gAVEJRP6ITZL\
  cTfHQl2I7aqrU4LNakk%2BO7f%2F2EtOgEypmrYNz4ydwRS5hjuNRkuAkSs4Hp9xq3b0XHfIrE1vn\
  obMIZGFKghhAkiRO%2FaZOMpfjEcVB8AgyKyvmY7t1ftcxcf1FQo81B4nf8Q7Wi84325pNol7%2BA\
  jVE1Zl%2FZKuWwtD6T11PfmtdjYx1u5Z9qy0Uu5W%2BUMrWypwhCt%2FMrjdfe3aTbhN%2FpC0DAf\
  dzVm1gvoBtvMrcHRAe2OFWPwPlt%2FWTRDbWfBgEOA%2BDrS%2BJiCK%2BrKSH4xyr48JnigaZm2T\
  rtvub5MH8x8vZiD%2BrYYvrgVw2KypL4zJgQODcMNrn5a97n2Gfv1IkZOqOq%2FPwkM59rBYN6xl%\
  2B3ccQlGj2DFvpqXBEnGj7I89YdVyqCUl41ETakSRTFWPW7WAaKePBJBjpM9pY9uWJMmeVvyXZzgm\
  8NtAuNLjV7%2BRTSyxj4yhvCAL23bzotHYPDFGasK9PwN2KxJdX2oD4OG4cCJ4w8FneW7HmlGu6ZP\
  RRwhxpWm2X7tL9xP3lZhXNWu372v%2Ff2Rem%2BsHdji7KW5TehWlYDUr2PgfLBEMcsX46D99oMhB\
  0wwpIyYvQY6pgGHJ5B67tKDO%2Fu0OcJqhfWl4zMDWgpho5vMLfwqjA9POqKoUodEGENPJ6FP8G6p\
  RmcVbPC%2FVNgW%2FNrBjt%2BzJFrbs3vB6eE71rB5T8FIj7A4MYCznB4ydb3kaMw%2Fk0BcJyboP\
  9dWmTSUWzT5uMP%2BXwKUofWrGZ5KYMMBgth%2FRnpaC7JlhQRzsABIF47ex5lEGzyg%2BEVj46Kl\
  0TppfpPskAVwEfuZ3C9P&X-Amz-Signature=5260c76b821a6431eb1913dd1103deff76938ddd\
  5b7bc15bf93cd1b44fa29dd3&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663AXXPQPM%2F20250207%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250207T142052Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJIMEYCIQCSZtadTtYu39pMB4PGAE33EPCdtli\
        V5bYR%2FoqYVmXTfwIhAKzABTMZoQoXy5TnJMcd%2FKXViv7%2F3ugeJTwMqR4GmixlKv8D\
        CHYQABoMNjM3NDIzMTgzODA1IgwjyX9uGX0fu5ycCjgq3AMqHeCTA13jA8ZOQjeTb15BMkS\
        CafTQD4zwkMhky7aBUJuvSAWDTpU%2Bgu1kQNRiNFtcz0nmUob8A6TOKBKnd3pSI2TEzp9%\
        2F7TC50CMubopUyVI4BEaqfTuzGMbSwGDiNNfBwcjl7E4XxIQIKSwnT3iaL50RLggUv9Dv5\
        4VGeuO%2FG6lSM2wfE7s9HtTaN5pvNH1l3NFG2ZROcDpMdhxyhBCl0fcCTLW2qQ5irUk5fp\
        fdjDytCuEZ6I4%2F%2BbImhMpbVZk%2FlzwhT9rLn8A%2FcBXsQa1rSbjtQySs8dMZlbNs6\
        kSqaxC62P9RFTL0ex0rTg5PdRDCz5SB1WV18GsdI8QqldYGCLRy6%2BUs49LTQiuywMyVNY\
        0Q14NQ%2FBcW1ZidyPzzGjncNcnKcXT2hrt%2Fkgdtl0YwThKgqjvBs2eZek18A8dS3WKzd\
        f601OwIoLYLCIsME9s%2BLZqmr4aMMHIYe%2BCAE9%2FSVBBR%2BFv6C0jJ6BrbV5BxaMDY\
        gw%2BHI5NPlpGgujgun6xVWTpwMUSFq2NubmSgr4kJ%2FwZhumFoWc1%2BJ7Bk4O1uDS%2F\
        P0VmDs4ksN14nMvA1L33J0eQr6TA11X%2BLjNQEJjfoRSOCmhVpUSgBFqKhaSi9W4iTn2Z%\
        2BDAnzeigunTD%2BjJi9BjqkATiT0oKVXlT%2FxmrPVR7DtanjA%2BQcjSDUE%2B8APRlav\
        EVK0Pmu2JJWY0HcwZd%2BTpRRgxrgP7O%2BdDUiv%2BliPP%2BauKe1tZt4zIetqjCgsy0k\
        4EQfsVuLUIe2XMjN2x8Eveky%2FAG%2Fme8gQNhcd5CjavIE7CKj5wT5o16GuAVZVGVZPoM\
        F5ncP9egRuKxMivoWsv7MzKsv%2F9nUqaM8OyjSWUPh9TTu6EKw&X-Amz-Signature=5ea\
        97788116bdfc5611525c2fb077ab7c294cce2c3c7c3e03b3534020b99f2fb&X-Amz-Sig\
        nedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-07T15:20:51.952Z"
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
UPDATE_TIME: "2025-02-07T14:22:02.481Z"
EXPIRY_TIME: "2025-02-07T15:21:57.350Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=846395b83c0f09fd4fe76bf23b87b83e098ca2c959e05d27680cc6ab6517846e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=c884785ce85599f03b414031d99727027d880d0812bb5efde19951c272f9dc59&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=3f6681e42ea20c7062cab78c123768c834ad68eaccc0368ff94b9aeead49f143&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=c0b66fb7ab6d505131248f6bf461bde46d72ac40e0c9e3ed2c19caa7e47ef2e9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=1539924de78bae7164df1cb9160d24a5972c1f75504a726c46bb6498137ccc4f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664PMGQINZ%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJHMEUCIFFyu5PwrQkmo%2FxLwewRSJkyR0YiKvc9aTNau6Y%2BeMUJAiEAuI58agiD7n03VunQv%2Beeg%2Blb5nyHscuiFLJL7whGudoq%2FwMIdhAAGgw2Mzc0MjMxODM4MDUiDABKN9%2Fau43TiTkcISrcAyeaR0WTFaCQXWCQVFU4OzBVgit80R84Dk6jCVHw6Tqy%2FBAuUzkQebFp2F3MgRTsPDuJtW58Hgdz1XMtInxDVguf2f05JDNuk51jjNmNEvJK82xjB44bR1sU5f2jJvRMI4OzuaEEtrP%2ByRF%2F0qb3XZVVQe%2BowsvtOER%2BJkbnod9hV9wBkZ60zcYewYRKlAunBOU2f5f6WFn20hZ40sqaTxocLN9fxld2JW8TrDU0FrW4kvGRitz%2FQSQ02OkV2sxjjRpN7AgzfzSu30GrjmhIYq9ysM41DLEjJ4pxyaWjAmF1%2FJeKsp1KEBxm538%2FEekOvpU7yNEcItnxzirgAhJMiHdPIEGTIga78gOw0a3N3a%2BTq%2Bnupgb6GEhjcBFL%2B519q18VM1OY%2F1HXBJHpYq44x5u40QWy0J5gNRTnaRlwl%2FQ8o49rR9kvL3IANLkyuNEuhDVrHd0FTRL8qHKK7T0s4PymXL4OwMDFb67CEGDc4gR%2B%2Fbst892TErxs1WeSMUYeIW23j5t0Go4CaDcZs0TK9sNYlcMDfuEX3Nz6JS%2FPFeZPFDiNeXOzqt%2BK5yZj4%2FkDb1UcMnbUUtKWFzXBbOBCNF31df9P%2BWZ4DZjyWevSMdr38DVCkOHePAFRJ%2BGGMOiMmL0GOqUBjt7Iy7FM1pG6Rg6qOALga8zl6J2JiXRZ0jWYk%2B4gh9sl0%2BZzQRoEd%2BRlsF0%2B%2BgCWKU5G7zen2tzj7UuEQMkSA2iWi8u%2FLCu%2BaAkAZotr%2FWzgzuCxkGPgwGG3EbG7CsSDAgRWFvrZ3u4OGoAQQMzKU6h4JPYG6vlkXKLvgWalc34N2dCrHghQNeACiG9ryiiI8Qk9P4gBAksNaEJSSU6xZ1smvgLy&X-Amz-Signature=194b65ac5f351e60287f8fb942f78317d987c6dc3c49dec120d63f716f2af14d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q3UXZAM7%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIDBp0%2F22%2BhH0TJg1Sy9bcdxjQmpaF1WYjpHP9GzST9iVAiAxd0WjDvN0%2BHsEY51lnybBUrRmKzIcysZxoYikr5MQFir%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMCoey8gCbG5ml7Th7KtwDceCJvf1oJ5jg4AjacA2ln1JpCPf4THNzT%2FkXX5yItvbFFiu8og3%2B5ZKEQueugDn0YBpFVkrZats4onP2HzDU77M2eTmDgJKpnuaM0h1YGgdmzWzjq6Nws7j392Go6%2BYn1rLJ0K7hls3rq9Ui3eUN80JRsmGxcZHCAPqaIWMmukRtNwyqK69tccRrFHnTRkqf6CV9ZdqZ%2BzTNhXGrDqfan3ppdGtZXIHssTg7vYKEo23rornKCeDl1ydLKeRZ4caz6tzL%2FBTqPXPp3M%2B4yPMVkaWUpb%2F2A0Q%2FgZZk%2Bk%2BoNwECh1E89s4CiJNvMEVHFn6VAChdbySzFSqOfKe7gVReDmw7lP6luduX%2BpQmcoE%2F%2Bubvzbo7G9xW%2BzUUlSAJsOMC7Ai4i0oTpvbm5HCRHpjFiyq%2FFNNkTh9Ww1fYN4XaWavb5XHPQigjkEBBjlBuimXEm2SRuUGyA1s7hKLRVQgMMTR0kAIrP9NpgRT36FL9btdZpNw%2BEJ2RS4g%2F84t1Y61xF3Ut4GnxLbYZxX9cxl0e0UZVeu%2BP6WJAR7%2FEAOUBluYFQ5%2FpaLnWbsB0zQ9oqCl2PQSRNsBMl6q8bfkwEgCdqT9DK31bj%2F9JA7VTuCD5Zdn52rnv3xc3EJbMJ%2F0wxIyYvQY6pgGKw%2F0%2BNW9WfdQkceFzRj9u0iHyib036JG7yfpneyErQlS5VXtFsZ4kk64hSmpQZchoWnNAxPxAc3RJ9n2tHuWEJEr7%2BhcbhqqIBDT1EOB98fJIiQ3lF%2Bwd84zdkPtJNyxL%2FZusmv0rlS5nrY%2FiFWI8I2rWfrBAKS7KZtVJNJ2RlB3Eicdy%2FSB9CwI6mohTgbWSEEp6cQ%2BCjD6rztdjsqn59eyo4jsG&X-Amz-Signature=62238297fc7a0e42b32f0d8e56ab10e45bcfd89157e43f9944d31bf8bce4b905&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=317b959adbb0cce0e3a261a1f12f9afa5f3660dc5178a5a4c093c35907eecf93&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=5a16c301e399c179c1d0105aba52d8bc5340c4f1b14d3da1ceced5e00766d589&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664P5MRAGO%2F20250207%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250207T142157Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEF0aCXVzLXdlc3QtMiJGMEQCIGFpw8q1kvX6Qv00Lrd5e8Xf4tHGU%2By%2FN4DgLhPShkG5AiBQ4aWFvjNhPeYHBr7M6yHlQ0s4EUBFJzHVrS6a27rl8Sr%2FAwh2EAAaDDYzNzQyMzE4MzgwNSIMmMHToZy3Yhm5wNjqKtwD7dnI4cgK3zfBSUuIaOaz7dManhwhagyahKTKwc8AOOEy4SmTk4%2B64pkC85RdH5OggaMKG7I0sltjbhBgNiRVavZh6FHFKaX0%2BM1aAnIB1EoUf2j2szww4x%2B9v%2FY9aPv9MuoK587uIMBtraunwHb%2Bq2VBV9WcgdjDQJXTgsv7OcDIwVQjmUuLuIVMzAYC3tVWGHkYG4F5UyAjl%2BmQ6ZUAGChZjBBZQC37aciqn%2F9sgQSD82naHtz5UgIyleVxzVBH812h2kFU4PxRVwLoAnYco3hHAuvaZnKUUKEk9nRM8ES5q6AgGuKLbAOK9jK5gCm69n%2F68%2BQA73aROxdbmPHjxgknKa1rVKlxNXOPGBJyWQGM9FkeI0bMtupPcUxKilrMUC%2BA2dyp5oQ6iaFpeEzTvE8rWubtxpLCiJzZRzJQseE6N8cXCkKDdgxnGgXSgbnoMvCOnKvT6beR9wUM1d7sRHlLOK8Zm5GaNHr%2FtukQfa8yZ0azEgT4A7sZdCupZJE%2F5byo3nNbtPy7YW1qgA62zxptdHUZ2tmW1Kww8MWXThDnZs8sreQGkV%2Bh2FzYm32H3gqMU%2BwxP9mjqbPxJrHoDoUEeBb8OUr0qFOjuzHS7ipPd3AUGHKaNGfYKz4wroyYvQY6pgGcP4VWL5k4cv%2FlvmnIH%2BMu5MiOAGy05DBpalbjnUWiSFa6FFLAtqD%2FsCEq3G9oPOyJJ4U1gwQUmcjbv8nTDjXU8siyDgVXCHbP64Hc8WWe0YTnABUseesZcvbzd8lz%2F1SW%2F%2BqMeu6tUCUacz9cb1tkusDYbixSPYc4xLw9m0xoERAHHPjuwsuoVtBEy10FMFrkhKejYSmaLTxUCLpZodZNbOkh0BJM&X-Amz-Signature=06e58439d38b23e47963cdb8192c632e7c07a50beddd8441668a24e182ae15c7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

