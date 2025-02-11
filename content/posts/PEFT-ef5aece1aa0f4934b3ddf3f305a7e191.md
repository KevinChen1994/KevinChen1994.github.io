---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WA4RJZYD%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T102622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFI0gj5nQJ86S7Xjh\
  BTo3899OJjFwgmFx0WVvXMEleiAIhAOMLZGZd4anfxwYJjagKsm%2FDoaEa2SP9QcIhN5XUyZe2Ko\
  gECNP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzNdYXsR2wVu9itMDA\
  q3AN9aCNQGvyiyaqKCD9L%2F8jQt2xbNQRxZXgxPD3nHE5VuZVn5YjxIZVs2zPy9kDkOgLXKJ1Q5G\
  Yshbn4ZFubE4PnXaWggJerxS5kBVrR7xjRj7vjUCoaDXOwi4Jw8X25hkCqDsmpVhz2gVBWXyS2hqX\
  4ECk%2BlsMquvepjYYczDiZSFnk8fL5JJ4NXOI8%2FMpSYGzl7sGbW%2BPexD1yKwoOM1c2K0DC1z\
  B7bvl0kHSExMdFnHjSRamq1vJSTOqMcPZj5ZsDLAubJmWg4Aq3yPDLncTMXDvuWrF7WszCkRKjJXy\
  CsMm3FF5aoA6%2FNXHwEJ9nVhw%2FG2eIs%2FhOX6Cblu1CbmHgpFlTliISeqR8qyGa9oBeefSOO0\
  spvCS65gvbBqY94%2FI1SxXR2mvq5xKuEU0azB8PITvcMdh2QDjyobiKsSWvsQl%2BgSZlmjQlhpb\
  tnGqCOYHi8EB09oPw4B6cgsRqr5wzqGPk8O6Gu9wr8D2pWhoNRJSA1HhvpbMHX8XmfR4HuTB3FHu%\
  2FFY2iHo0yxg3uK%2FuK9iGstVvQndNXAMMwub8vN5n9eyHDNxj9NR492q4I0iRsaFDSdUlh5%2Fz\
  xjg%2FhJHEgsbD2VA8OcGsNAcOYVuvHAHPpgvcBiTWV6M5GkzC%2Bt6y9BjqkAdx4fOXihGCQ2ja5\
  k%2FvpDFHu3LzghDgHATKOAOQsA5%2FbzawvBz5aPrkAYtoeh2Q2nSsHgQRMuGD%2Bqp5xKahOQoV\
  aoiPUDb9w%2Ffjvu7zIrfRh7DPY%2BdY5RmunQkJjDRVTK091%2FAi%2FliIR636ymUZhCLaKWIz2\
  cuLPDmoa7%2FCeqV6eJOsBLJbgTdf5S25cUIUT32Aho52QNQD2hAQFCsTb%2FIho0nH5&X-Amz-Si\
  gnature=9bd78c0e827d4f65627c298480283c504bfbc56885f5e3ab46715085987228ed&X-Am\
  z-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663WEQYCSR%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T102454Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDUlx0v3x6AfhtOg3QEmXGrgzb7nn3VcXUTOC7q1umbzAIgOPGAzlznK%2FNfQ%2BTr7O\
        kqi0RVoo6u56baUuwMIm6WjMUqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDFC2Hl4PxBOZkB5n1ircA5OwqUoA8E6orOI11MtbkOvfYGh%2BrFeN\
        zExFmPrh0WDN4tThpTfXkp7lB7qik8Jt7EYkeC9AKYFrAPa9O9QmUGQZKUrzfexF5lSqTUc\
        3Qx7YsOaWO51n9YpHpZh%2FeRsHGeQqo3LycgW0Kx8bvMqBicX8k%2B7of5Ogy0y5c2Q13L\
        VmS%2Fc4H8l3sGRYkdL6hJxEglOfJ9O3SLP4OBrcwMbDdOfMp2R2PPNiJtBtVNYVCUtArPK\
        AFDBFKCY5DOqtCU%2FByJUvbO6N6gOc9M0v0wJ1KGAumrOZNRyqlPYq%2B0VuqhVtoMPA1h\
        LwtpVv0PP5pARB3ymdG4co4bOeDHQaqakwQ%2BUJgXphAoI10K4g6TcR1veZSLM%2FeSCJv\
        WmzkkUv6gDBDosqL8mJm8QJ6Cm%2BF13AGupRjQ6znX7928mFM61P45D0bPDvAJKftpWxuh\
        25LhRxomJIUQy759NOcm%2BxjSyjXdi2JS0YjgHRAdqC7Y8U635WWTzUx2aWeQP3%2FApO3\
        8zbTLFKg6fkSiqk9AlpfPRz%2F%2BuPW71jN2Es3rHQOELFMKQy1xrnW8%2B4IwxBfPQmuG\
        tx5LOopqSHApWzjOS4EQ%2B4uycW%2BRYIhe71ob00H6U43HvWLENOHjG6qoJkm07GMLS3r\
        L0GOqUBtWMsxIVdziSqx0xtzQ6qFqAeh619w4LoHCyHceUkQkKvk5UU%2FpNz%2FWo4zKdG\
        pIZkbkdb7n8Sam%2FZVuMbCVlIcf6h6%2FvWxrNvfWTYt5aKAAk7ef8FMUqQF0PYwRda%2B\
        zXpeD0U%2F%2FglcuSOkZ6Y%2FR2BGgQKF18jweH%2FaZ4%2BAWieLKTWlP5Mdf%2BmZ0BG\
        Oy4xxjLlsMKgllHOXIuLrRYurGH%2FyGG6Cpv8&X-Amz-Signature=250bd6c7e19eb79a\
        b09e9379c9fedf9002660dc12db8c18c1632c0475c9bb095&X-Amz-SignedHeaders=ho\
        st&x-id=GetObject"
      expiry_time: "2025-02-11T11:24:54.223Z"
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
UPDATE_TIME: "2025-02-11T10:26:26.214Z"
EXPIRY_TIME: "2025-02-11T11:26:19.558Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=ef5e7d0d66efa9a9db5867d5ec0f32ac52e07b4edd0b6999f50b7c49bbd211be&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=51d841d2663c8971e729668e29771e8108015d0731ea6b76468842011ef139cb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=beb13dbb4ffdbffcf7f8e8d4586bf1183295d164e62f23feae7a03fa979a6c81&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=28df0c9c7a1d63a54433c2d69a55aeb4ef1f266d361a49013f3dee10b38d2ff5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=0bab09e08d39f0b89ba48b902304346d073c2300070b721066dabc5cf1376ea3&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SP2TNRJE%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102621Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBMymoITR0JgZgCXcm9LDVExnHS8dXRex6fYe2AI4LM9AiEAxaZNfiI4fk2WZoys6q2IYAPpM1wyrVhG2wgoKeKLLckqiAQI0%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBNBYetnxaNJIxq%2B4yrcA39ZcOvYZ%2B3uEQK0JsQolOH0ueRjylyTWdfXCxE053F3MdaRimM9tIwWEeBIOrpg5izeqfSYn4KOcZKXmQCcu%2BTkYj2Py4r7akDn2oXIJQMP1WwDwnU3I8LZbvD7XlIK872cwy3gy2yPWljdb%2FGj9nhw7ufoZUMWuwPB2N71hngYF5nmvDZrj5oYQvFWnlVuYI8fR0SO5x5j1y9%2Fl6igq24L%2BHNF3vgC1EJQucqqh3FpJaUNAs2BE%2FRmL8Xjed9KetLNAHwGjGFaOPxE2UGGBTNZ6B6sT%2BHZH7plndgixGJMkFo2nFdB1ZyCmibO3FofWk64X9HyFEKu%2F5R%2FF5LKueHd7iZ4zwFyUvuQBPhBLqpehfHrxugU9zwLqM7OuUWOLQ7VVgv0o0wvpLQdY9NKDrwyv5OpFWvwibG8K54xiS0fintkhKVpxM0YlTefqSPAUXyXoMvgiFmTlW9e7Cju%2Bh1xAKGeACwt3m6sHus2bHGqutXLhHdVYZofJbRBZbbBEtbQHFg9veEdcB%2FokUZMIJs0YE8ix1HAmiZNieoY9YyAO7M69XWTtys%2BEn1DsdhOJ9c15Cs7r5F9NU%2F8RzwnYRhKxNusynUjHjC4HGqYigrUyUWK3%2Fcy2TFYKD7TMMq3rL0GOqUBKrh3JVJ7ksTio%2B0iGpbnNZkL2SiJMk3iEfTDHlxGfsmzI5us5L5z1ql73eFwYGzih7JtYnAmUW%2BBzzlRK2qP3Oewmf3xwqJTlkgntusu2BRKNKuwJdq28wB3odE9kSiw%2BPuCbP7lpCf5gqMP8Z8pgVDjLPpBhHycV8IJ7Qz5B4wriINgEMwNfGpGAwLZbVRgLfRqm700Jxm163idA5X7lJY%2FFrVf&X-Amz-Signature=24541016e7da153d1196b81256afc535dcaea6a47e0095e4460dd61ede6bcf9a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z2YEA5ON%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102622Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICLmdc1fJGw%2Fcsskc%2BIwAk5v3q4aDYlrydMxyZvf8%2FQ8AiAcE16pH6HwxCGAamXy7cXWbRGVZbUU57W8vVOBUzDhsiqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMIz3OSAMnovlk10W1KtwDWahsSWVmoAiJEBxzg%2BCZAp4Vlc9nyEwk0ozFN1jPqSaGrH1xKzIVK6LsrMsDKocJh2C7KatmHm6lvzZnxORZLdsNJmRgpo3fwWjbQwLlp37XOKTxo%2BGB8h33kOGMWbvK5SJ0i9ST79LZhw1x%2BmeIy0kESi2V2pdoF7XGWwEglSLPsEfYAtHzw1JMZqpakfZd9gKZaeB9RyMcDoFnmPWpmkNvKhEI6aUjTjfMXn7tC6FlrE9SH5vCzIJ5IYkjO9fADXT82xOANxGsWu7T8oZ%2Bq7NzfGmejpYoE7yBmzaWXsrhq0986mHAvfyK4f1nvkM2ijdpHi%2F4tOQmXBhlnvT7%2BTuS4LF1xJ%2FX03KhKLykMCJGEmQItA%2BOQS1I1lhJeNYUCsQULnU3YwxnQrCZ0FDGNgKtxP3ilhf5RVn50K06EhlS47oOvKw03DSGyL2Gg0Aqb1makg1hXA76ZtN2JDiYhRpTb3ryph2v94Mu%2F9%2FKPkTwOHLOvHRbTDJ%2FvSmt4evzvNxV5Q56ZcvbehTsU%2Bh7%2Fdv5mpjaJmfMhhxCsE45w9fx%2BmH9Oz4prt0f8RC47VVjGCOUOePXIiEESxUtrkqeZyxlZYY2g6Vg%2FZzP0mDo43LS%2FrOXo3NR7a6EmbcwnresvQY6pgG1Fbo%2FCH9B65jub41mfBaJMZJ%2BZNCFl9VwBMBWGwY8U9ndRt6oNdrdK9MpKs3ED4exIW3tqJYfbYn5gvidmrU5Ax4DcwQerCuhOsNFtaNZ7%2BFeDjveHUSRwVI%2Bhe7OyGvgs3tveEpCnj%2F0t1Z3NXn2Hp8Nu7SRyXK0q7bQEPxKyr9f18PeJGn%2Fe2IrxXVIOGNIuCsipQeBAUN36fbyWDuG8QcHE3h9&X-Amz-Signature=3f6ffbef3696bc5fbda777d75967187e21f60c07d24af2214157085830b57230&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=4791079e5f57105fedc0bd125be7ec9f6db38c8a6d03c33da6b6d6636081723f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=d71b51f73ec1535da9c900fc6f39ea800b9fcf4c997396c58f257d0c490fbfea&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TDVZPWIP%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T102620Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICSHs2tS%2F7TKoXzCWgdWOGCx7Skag3TNw8rQwzHo%2BGbWAiA7eI93rbugUgXu9F7eQO56LGZySpcCaLTfP%2FoOo%2Fvc8CqIBAjT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMbecOcolgThVvbK09KtwDqc6dMs98A5NdTMBznxNaeOxDxKKFzhBanOxrmIYARnHX1df1yWd4ll%2FCS15xB4zuqxzvycjaKmP4SaqIxcOAKAsKc5CUOlM0BgZiyKvC%2FVVaYIziZ9SdhZKV3uLaP1JDp2tZjtguy%2BwRKwMYJ4rKWVrbgIfLgkBQtV%2FKWeErelZNbcAuerGbCFVTNpuw4%2FSSPo5TXvgHrx8vssHAHSpGV4r%2FxlglxrwnKwWvIc%2Fs%2BZu5gcheJ6dRdrKy8KT0RmJM%2BUc2Efr1aJV48meESfQ5qxW5Kx9lUEfx%2Bmz7K64l%2FZ9gDoidK5GfOdZtanyk7ExqBXA6XehLKW1Ffv7pu3FIbQW8sHCYsb1QBIzWIsSWA5lamxu%2FjQkFR7Z1GuPGqA8w4bRG7tPIIKUzkjas8%2Fegxqy%2FJqctgRv6pDAAMDg4BExhaDt%2Bg6wCc%2Fqx0MB56lHpxujuN7cuaJiqTjeaU51XcAh6%2B9rRmE%2F1PSJiuvhu%2FBh1VeWYUg9PBmi2OVMCn5wrCC%2Bg5Frv6oPKvFXI5%2FDGwuziuOreOSRn9xH9ZO0mlSYEnH2KrbYc902vkexU1dIltZm8pzI2qM%2BfGLAeFLhyOY4nG%2BkFuz2ckcBWaOHFHEsaRaFPPICdBJkYVk0wyLesvQY6pgFxQ7heacaKQJSnRUsRd6Q58ePge9zdc52Uzih7nUcuhE4M8VHk64VfW1fi9RXQjQCcWsjSgdtTwCzDsCxrAfH%2FVCs3K7pwQkeLoqNGta2%2BVDd3hG%2Fw0uWyZctV0UG7rE0%2BCQALJF1oE10ImJ7wKU4I2%2BjVBJvj0Y1gW21smsci1XYhbCtu%2BTotzcpjH3nMXwbn5a9%2F1hl2hz%2B3KUL%2FyPc%2FP6CgKMXr&X-Amz-Signature=0d8fc2b627da4cccd62b8e345c461cf29828fe6c19f34d1cf1ca3e3d5efdbf20&X-Amz-SignedHeaders=host&x-id=GetObject)


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

