---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VGX4MPWS%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T232239Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEH4aCXVzLXdlc3QtMiJIMEYCIQC78j2hcRBvNIn4GKdAhjUP%2FqM%2FbKAPsEuqzIJTFK53qwI\
  hALY24JFJxprr56upGOyUvlnDAgj2Yfo8KwISU8maLilMKogECJf%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F%2FwEQABoMNjM3NDIzMTgzODA1IgzQDPlXmaQfTxmDDVkq3AOuZcrsL3L7cNDKAtl8aG1O3HkeR\
  2WhcLB7SIvJETmW0upOmrVhcmdDyAFCcHkbQcTJQvH859jnHs1cBUhhv63BWwfDBSS1axLLqKagUr\
  3vqyXbqCTfh3Y3Tc8bC57ZEDJPCcdDCGi1zqtWnJ1fvIYiEP1UOwVMf34tgYQOMcQdLQTbp8Eh%2F\
  GMg5qZnUgbZzjAq0%2FaeXpcryhrU7EUnoIS2PHV1HUUHmpoJ91Ri7o19AiGcA4yaAVI%2FUck0Pz\
  gu14qT1HzIQitsCEgXuhd9hRuoA2%2FIgMPp%2FokT4kA0cwfQ%2FwKwbZt6XDvu5pm5zDVMlAvVk\
  7XN9lqq6g415Ona7mANykOgUoFX2jJVwYvAYvcpjJ9cMi%2FM%2FRhEIdBujBk%2FHNSLp3lrSp9R\
  h0zEZdbO5tQCkMjuK8bbiqnrizXqv31Cdy8Tf2YytEDY65%2FtUKeOji39dsL60H5wjfqXR%2FI9O\
  d6GXkkEBLOvSGsOhvQCB10B6505wSrvmZ2hXnrBK6YgN%2BYkO4xkrG4DQFUw7C%2BCLV9mCi3kQR\
  yV9a0T67uJW1sbZ6BTRE%2FqKlFYyL6n77n80Ch%2ByeLpQtDsy4Q4X3dz7%2BosZQwl0T4Ow2%2F\
  qXO987%2FaJhlktDjm0j8Rksj1msTDAmJ%2B9BjqkAYjHgMo1enOyFd9dnj%2FOYo2WhF9QLNpAFr\
  FnbvnGqT807CVe%2BZo1zkNJdnTflSkRn4KK2DAvK1GTo%2B4Qk0QqglWNIdcbErbFcZsGFX4gUWm\
  0FjVrQgPw6UTIrHXU0T5KKJgoY2hMM%2BfzgBo8CAyfOBwtiBsSgspq%2FEZIvJNETCTQLc%2BDZ0\
  rsYyWLR%2FlAmIlEyxq03WErUIKzd%2FU6ikuTwi4qJkT4&X-Amz-Signature=1d5904ad42766c\
  c5d03680a5bfac4b0c33af2fbadf4c0f654e8b9ca8ac93b291&X-Amz-SignedHeaders=host&x\
  -id=GetObject"
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
        redential=ASIAZI2LB466XDOWTERP%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T232132Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIA5zwfb%2Bhy5qGDSHPA5jO6w9miIBY\
        w5XE8cJm%2FXCyM0QAiAdbrf5ZudwBQaReXDfgwRSs83hds7PjZGFGhryzGgrhSqIBAiW%2\
        F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMkMfAAH59VRrMGEDWK\
        twDUuRr5U39N%2BiP%2BXElNcP19OXlmayPTehQMFNq0rKweON831Zwva%2FXfsOxwsGrvx\
        BgSjM053oGX24ZPnOC937d2WKRE4%2FfmiCpT0QWZw40Oy6%2FDYMtWo6IbDvAFtku6UwgX\
        H0jrRitSMaaMYtRoSdSRu6Tfp0wZxsXZnHiT56%2FXLgumreV98cnjnDowyw5%2B4CXWcJ%\
        2FvBHCjwbpxtH5ubvmsRlgPQTbXR%2BAzftR9v0YssgmP6%2BD%2Fxl6ChgGqx8NDnvc8bZ\
        %2B5Skm39f7T30GgvKMQt6todMF1peFX6UQZydT%2BnCg2AmqQZIAFuXLigwgnesweirmUp\
        rqfyhJCKYujZfNhw9%2FLZiICx1t2SkuAf%2BuAq9%2Bn%2FvacfsFwzSwQw0rIkQ0ALE%2\
        B0IjZgC48enpbadyvSo5zlHmpcWmPlkbAGtVFQCosonr38egfvXTjwZmaq5dGmsULxIcz6E\
        JK6AyI20AQYFX8WFO%2BSmofDPNnL22u6xTTWtyuQdKSEg5X2dfEPtY7FHS75rtZmLY70kH\
        V8sullPB6nsJx2j1gKchKrNt3vOT9J5p53GFnDNFU4%2F47PCTp0Yj4JV2SA%2BFabWITo2\
        LUsBHwwfDPZvr5V7krxJ0WScpvFPUNQhx1ctUE%2BxIwmJmfvQY6pgHQ2A2kW36kQ2cqK41\
        hU731Cic6tp1soSWCOc17JhXk6ak7OrhOr61%2BG3ToxumMrT3M5xRqVsbQYmV1mNlufJYB\
        Mr4eo23o%2FPYReXJQKtCY26fSGfCTA1gt1vgaZwwAV%2FAO5FPcdZlkyU0eTujmCyJT1nz\
        mav5E9XH1cwdmORRKyMLtJkeFZUSOxJcRzQDXegpkwxaiSki94%2BWN3p43rAVq6vq7Xwsu\
        &X-Amz-Signature=41f74d879a9879dc48491dae3b6ec5e91cb17d577945ea5cf04ee8\
        5601de6a40&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-09T00:21:32.080Z"
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
UPDATE_TIME: "2025-02-08T23:22:43.777Z"
EXPIRY_TIME: "2025-02-09T00:22:37.554Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=f74d2f9b80ea2b92a5efe9c721eb1454a643bedd2daac50b3a9beb8765793878&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=27eae5204156b1886c5ffbc06de64d851e4c05d23dee7bd2deb9314b92b8f990&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=6bc9b097a6d9c9af5f2950bdf7248e50b4a3440e9182b4dbdc9b4743f6978e2a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=ea6c17ea43d7640b0720353df21680ca282b3ce602c9c6913c619445d898934c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=6f4e8864f7fade192e40e168323407181d3bf083fa37e70b7a9f520e22e9241c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UEP3ISLO%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJIMEYCIQC88aI2YFYsGCNYEfGKJnh85IuF5q8TLHKvCKxBGSotEQIhAMp0mJcOXLSvbwPg682r9pwDFQxulPHQ2BgYpWjSjHWXKogECJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz9UPzWQcWqHjlvxlcq3AOi9Ukk4cUUCLU2vV7XrWl25%2FsegFrCH%2BWx9jP1OldHwhcaGJd8LBaerRILljifkjyUxD1BRZJwxofcxTm9jjZO%2FUUeDJPHZNkVrs5dvdP1DsIFgzjBOQ2D2FP1zshwEgBlvQTyKnvSZV0ZiLarskggtCpwdvyj0%2FiLf3RJbM9q1601UbIJ8fue0WYjnGQRT2jdHJZIvwOYHq9gKi3XaiuflTiFbd9niftqlAElR%2FrYIy53hUGxe7P%2FzCZ2qgWFyj3JpTlxRXQ%2Fly4R92cyQGjY%2B9ROSFdDBdgYjSqazEI91raqQfDvxMaLa6peovjgLvfDNll0nV2GBH7EOSxozUS9zjQ7182xO8HhFAH6wcADRDc%2BUjj5taQRbjmwLhnKET5AwV%2F6A5%2F8yp3M0Ye3sTi3uOiO85xA5RB%2BqFS2NNdEWfUkGdiH75iF%2F1xTdj5gLGVbYKE5uqu4nqX10ozWorZnXyH1qDNz8QF2xoOMFO7iJbXDWxkJEHy%2Bk55t49MJw8hSW1g2GDXZzYOas4f%2FnFz2BK4%2B4QHDPeXDKdTbz%2Bl4FcG7LY%2FgP49adeQ6eqEyspSxb3vbrCvULsTX73JHcLmLfZi2veYJEOrgCmiTHfkj5T5k8usBonOJ54fbVTCimJ%2B9BjqkAcIzwfTfQpyeQB0DwAUHo%2BtVbT0gu1TzVFA3T%2FPjxSUMYrZxrQzbCMvBZDtW4GqAP4qICFTKLcIxDst5kkbxX5QgYHKmr8BwlYii45t9otenlv8rOJ5aUFeqaepomaWi%2F0wzDI3GcVQ9X%2B7MVwXfbBNjB%2BdchimgiYqkONeFQSozHCF4KbrUKKM%2Fa6D%2FcgHdkHIoV39KJaBH2Z%2F737uUHtDTUXY4&X-Amz-Signature=2f250dfac33311a0c47c364b0351a52c68244aa230a917319236ef09ef8b57fb&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z767FVA4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232239Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGsGY2Mn%2Bxu8tN5X%2FIxkVe%2F7NT6OqYFjWwHg0Ylx%2BE%2F%2FAiAYWF5LQjNMNZzk3WEkH%2Faaq3gP1aEfr9wlxplVEY%2Fo8SqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMBuLE7h5aXn9gaB5gKtwDFSrul4WS2rHQo3O0iBgA75fPy3ObXcQc0JP3Iwzz4Oafkk28NJEaq4X%2B2%2BpEHmyhxiPLiz87TilEvCOHWP5d1aY9Z%2B39vV%2FVZpatgPOK9bPl5XnsJNSWEsl756enKYWlM6X1IVCl6xgG1ch4LoGS7IrquJM4VUrLzoYiGYpqx7Q5AXIiy6IkryH9At0U%2BbCOCn96Zexdx7fQfBPPDX6yz5NzbgClqNXoWGlTPYmMqTX90hedd89QMIW9lfYEqgvewmtey4%2BRMRGrkiZCt1A997h81st6dhtQ3hP%2ByMC%2BeK39XXe%2BoJ7oqf8ptJAhBuqb%2BhZOB1djyshaXLK%2Bmy7G9aSp8KoksvpgDsyHCx7kaPJdfB%2FOp4F4uGKhCyyqmu9zLcbqeoTJ8O7J3oluArH%2BnlavZzMwXemwVGWI7gGI4Ic7C%2FyGgNu5ybm8YfvfYq6nndvtpyjny5CpbACsl9meHorRaWE66XjlNF%2BXYmPpDH7093NK15k8SRAsobvNOFpRSZ%2F2oN%2B4XK%2FxQr4Zyu7rXTGY9ARY0v4mENhD1B5Y4tw45kJgtal4hEI%2FD5d%2FQceCIqm3DYKSq7eGbHTt8pCdRf8BB1c8JgAmVmBLjrBbMQh40eIdtjA5LI%2FITXkw55ifvQY6pgH48dqIpfLPXKezdS4yZeR9RnDzgtf9iVQnrPtOHm8ZealICv84iwKF3JQgWijFnlAVYjlDhUtkNPm%2F9wjtQw9tEPeL%2FVDIr8o2flzoMWAuF2UgRaUsltvGXFEZKkXzk2nk8vEp%2BuwIZzpfFHe4CxwxU52PXqMpaNug2tOjW9Dn3BuI5LsGl8YcnSTLSX86QuxGZ0OVQZ1cBztgebvmEDr2%2BKJcu1%2BD&X-Amz-Signature=04fb53000561e9df09243100c00e5a1b5284c428a0e7b55941519fe18d7a1a1e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=1d5d6f68fae0a819e54353ef35e2c916b7a0ad0b579253d61d37f4298e8f62f5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=aad11477b9d782e96601c347267ab721af8b4cd3aaae1ff1c0201261f6048f25&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667FWLCHYC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T232238Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLXdlc3QtMiJGMEQCIGZNFB4Z%2FDizsER0L41I0MEE43vgZSsbQP37b%2Fes5DtdAiBUmxbQ2HpGH0B6q%2BUuZCmCj0epByv0aXvQVSVe%2BylcDSqIBAiX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMn8Gsjer4CrvfTTfvKtwDj%2BjG6YtDA84dsZ%2BP0nVDU%2B9YHcnB8cteob5wvwve8O9q9%2F3bCzmM%2F23gnbVDKCXO0rtZT0XlZg3to7Ky3tG0ObyGl9R8R01bi8R5yk7xBKToqRi6GgtRwuA2NNvV5W7dUWdcWnXTKZaGNxM29Vh4GUtk0f919Jki7NzdCNTAPuVIs6kxz1KffaUh%2B8zc3b1ia25rdKiPXLEdsNpqP%2B8zBkbMnyuuAJhE1f4ELWJzWSi6iBzdVMplbSma0tmebsbqhScGadC%2BFFle9lhXZBloq%2BPc3cIg9cUimB8kra3jQjCKBScbPaFaKn1PLrUpRyJSnVvbnoPgeo4A3drAMJbNrevdAmSuMWAeIpYM9nllwiAKhWzv3Is3c8okbWwRkgS%2Fs7IYti3YErSKHba2dGlLohnp8qMPCdyfWJfNHUJCMTcZRpkHVFnOJdrx5U%2B4hTQBF006pABe7S8tYkhdVE1sM0TK%2Fb0MPn4A1Yu2yRwLDk1XRPNUzjdIhN1XrptXbNfbr0nem9MvMZ7Du%2FTW689793p2Lsb0ljAd6l4uHzTK0nWaMhC2KkNlvCFNDLg8T%2FN9he4XJmdLPMJCfrLVRxJT9PULNmYRT0oqotJe452EQbfTERKaWg2NDNUSYokwwpifvQY6pgGqzyPsHabWyaPjOHcHnudzMnrr2UXgY8RE1IophzFFzB%2Bh4%2FNLqjFS7bbL6UwfTQROLRxvD6ZEtHMAAGN3MHNoUlwYA87YeVY%2BiaXXyKk6RPZ4r5MImz2N5uzqiMVnk5zcM%2F67Kqcwt4tdtgfQE6JA7xdnG%2B%2F7T%2FOK5C%2Bu1E127kUpHRV6dCZWGFG%2FhUdtSd%2F2obc%2FjKcup%2BSbmmCwl7OQyGmeBbcx&X-Amz-Signature=7b426b2f8ff60f54f62623fd32e9d25a28eefb67a0dd63c9038334d5233098d5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

