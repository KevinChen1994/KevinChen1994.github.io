---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZMUQXDPO%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T042630Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGwaCXVzLXdlc3QtMiJIMEYCIQCAhNffydeWMEFfp8C0qrj60gdGtUwDU2aIF2ZEbWOboAIhALj\
  %2FtB0d9rEQVx8EBLyFAsB8NhMSQQWa0Akxhvc5%2BjFiKogECIX%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F%2FwEQABoMNjM3NDIzMTgzODA1Igy7eQyyr7M8bfTBCXMq3APfKTtvKrIauYUi2gu%2BaLuPWH2\
  hx%2BoUYLlyYa2ZzHq5hh2shwKfUC6dr8ut%2BA%2BKOMAbv4o1v49XzGs7uTk%2B3WglUL5isCBx\
  o4P77J73w1Wpi7OKM%2BjBTDmwbFxD2iDCuPuZ2r9t9%2FIrtM0Bh%2BcXkZQ4YfimCICy6L8lKIC\
  7c6AmWjMkr%2BRy6qn%2BCk291XdhsSBrRG%2FVNGKV%2FTu5VI31H7hKA13I8s9bh8P%2FONTrZP\
  PBxAgRfgNcrsuSt%2BEW6kExfPhqI25sk1Uo7tB4ssjE%2FU%2Bwci8k317gXqr3g%2Bs%2BXlvcl\
  8ADsThg9W4j83KySdnTpcY%2Fqon9YpCL2e7XFgsNwzmJfwh7hp%2Fe2hVtI8eUHhUojUTWiOfoqA\
  BCEbcKitGu3r4Mgfs7ycqwuJktwIUriaVOaVSN5ULeUAg7KlqFq5mNZOVkxed5T8Oht7%2F3a2FuX\
  4xQqFi2d6dB22ndSzDxNN%2FGmSqiXWvGa%2BORUXBwmgPjHzdBdWTIzetHYCKMkk%2ByZcUdzrCG\
  xRxV2FBNRoUsiFfUzuNuDGAoGCL23TcIHI5eXG4QlgiFaDXtRVqHAqHlPR2TYKUEXvEdlH0LVeMUr\
  LaphxV0B86PVOppM2WpkzxSfIhdgdAVHrkDVZRLYjDStJu9BjqkAdXdSJCbCfwz0gR1I6MtzJjasN\
  huNbhijX8OGk5ultSQ8TQtjubedY34adOIU8ooFgCMeJUT8gpcIBBxWXsB4fRnMCIVc1HchGko9jA\
  4I2hr6u3HB7sbOvSrvx8T6T0y%2BIl3JCH%2BkINwvgnwDpGucx6QModVHh5PAH0%2BqcPtJllLuW\
  ieXahtBPr6TH%2FAW3A%2B469PSCeq1kxMG%2FQ1J4MxIS7mDfDb&X-Amz-Signature=a402a914\
  059a2be32127f3e0402e1b02d1e46b091e2e35bb11dbc5eadca81fcc&X-Amz-SignedHeaders=\
  host&x-id=GetObject"
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
        redential=ASIAZI2LB466VHQ2F6MQ%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T042524Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJHMEUCIG6zt1qsL2Bt8FT6mUGq98joF%2Fdd6\
        aHeJ6xscy7Q972aAiEAqzJqdVPHuCnPZnQ5vvF2vWzQP0YNyG%2FDJhwBnxblicQqiAQIhf\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEmU%2FKcl3n%2F2U\
        fqbvyrcA23qNP9x44fI8vYfbx%2BOn2K%2FAFppJNo74zWOVMPKV7t4G1ZhNojLZJXeAW9d\
        6H4o6R94%2Bsf6ORdjPZ%2Fgmk6%2FR%2FzIzaFg516MCj%2FOY5HISvpno7suEssDV4cES\
        bC3KKf6JoxV3UKwZITOAMe7AR5ZRtz7EY%2FLuawq8vQYd8v8SwAVOmyW5OG4kbH9bg4x6C\
        v9wGo%2BWMErj22ah7ftL8DUV7T8kZh4EsHJG9YiVqdSK9LV7zUor0OylatcEYBPvNwFDrq\
        TypeQIJtK%2BPkw67chKwp228dIa4RBoIWMK4%2FnjFh9xtXnt0DQi7M5lCHIa8QFdFbwTA\
        GjHyIVL%2BgdwyF%2B3tVQ8dk4SACr9Qzem375mvYQf9gXQ0181gLtn%2Bko9TpkK8tLRok\
        ZH5aGmS2eoX4%2F8LU%2BarqcHrCkhMPpQk5CBO4mgM%2ByPnoLnjSAQQfYVu%2FkvBh3tT\
        huBW%2FsS5iO%2FBZwjNXea%2BVG41wSRKzi69XX6IQU%2FXJrHR%2F1GpaVYyuf2Gex8tK\
        8cuVnZDMxN9xsY2mpgXk%2FLqHpjUeaF7T%2BUL6XaPiLoMrzVat%2BH0nqiart%2B4ORtb\
        LwP8zKXJTpH8wnOtUTu0CXc5MdUJ%2BwkYrycugsQn7D%2Bf%2B%2FOzChOg2cYOkhMNqzm\
        70GOqUB2xgQhOmkEr%2FpD4iNACks7bhQt%2FIaLIYcAI0cug%2FcMWz0eeks1Z%2BGhM2u\
        g4SOU9DyhznL7axehRgW8ZaEAR9Sdo1GD0k2sa9PEh8vUuWRS3J0KfUs1DaMIgdIA8aH7qd\
        lvlwUY16CkYatMDAMID9chbwNKrZa70Igx5w3mGTlf08kLx7Hr4as5HoD5QGa%2BBUZtshk\
        U8%2BY6NaEYurttB%2BjWWLIjV8p&X-Amz-Signature=476412c311698a1d24af235a18\
        dd0b80d7f1f4041d2bf49b7d0317f6c3a9fcd5&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-08T05:25:24.631Z"
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
UPDATE_TIME: "2025-02-08T04:26:35.633Z"
EXPIRY_TIME: "2025-02-08T05:26:27.117Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=a591addeeb2cc6f959bb831474f13fb0ed85e03ab69542d355c8a3dfe2eafd86&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=ddb807ca1bf44c91288c7c9b50d0836deb4b7fb4e86a2a7940a8028ffe1fab96&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=43134af86feccefa48ef00eb54b64a9c6e929041435781abd6d924578397f65d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=7b0a8b7661930e9582ef7900147aa949508e254c775b1308e6c56b1583fe39e0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=57a52c8cdbbc42ceadf0d3f8e36f0c662e31dd19306449d7b2f2d9165e2e11a1&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662N4AGTRC%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042629Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQDEWzwEzAD8nXcaJ0yr8JTZfo4ANtoqYFcoT9K%2F514KZgIhAIAmlR6glR1PZ2zIVAfVKe9BXNCFVSpskgSL6yqePnKXKogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgylT8DxpBT7nplO3ekq3AP3Ua%2FI6tDIw10rpKN91T6r5zyIr5As8BcCzoHh%2B7lSgbLhYU5%2FofPJFfB0DEdHm94m6nre%2Bl8Onm8ucPv0jIWV4yjyhx0Gamr35vwqdtlCktIG1YZo1%2BCPCs7sEY%2FPDoxVEIX5DhbGa67n47cPXmTwEeT1YJmJPsGxij2MxbeXNrvYhSQevi%2B5VUBs8kEi%2FHnYc0hZdsEKwReBGdfW1Mhq6ALOqN3jnrfxQzvF9Ovb5wQWvz%2FV9%2FojmuzeWLcN5j3SNC3kmGbd4sbUhpDJCb6ObnqtsxFRUt0YIwQhAZXIUBW46a8MFvcNUXZy7Rn9kfsQPwdE3wFBpt%2BN59OmXnoqFUeScEm2Tz9KCd%2FHP0xor6OG062rJfs8wBrKdPHi79B7FcSzDf01n6E6RtQEuTL4CoHlgHUTNKMkUcUo%2B%2BlJwe%2FejP%2BZQQJaawpeFVNeoGzILI%2FVrr%2FPs9JA4TY5GYyBb%2FMn%2Bu98G%2BfAO3YWqNOoknf2gT3bDYUnY7xSx%2BRQ5%2BGBjeeNtbcv0NWFML7VB5MVV0aA%2B%2BeeRG%2B6RCW2VpjicyKsBF8NmHWnA1ABJj73%2F7I%2Fvgq7zKvZMlLl0KtvHvOBSV3XrvDao5rwCST9RQtjPGrOKb1%2BpoUshymCATCzs5u9BjqkAdBDGNLS0FcW0mXi7gcf04FCgNOQzKW14I7OadRkr7GPEzOCOb1nITzG0DakIy%2BznqPxEyYl3Fkz7jV9bB7KNavlLp9prQX3z5Ot%2BB%2B8v4kt%2FDeJ5EEmDdfEFdn0JD66XkUp8DYOwLR8SNNbSX%2Ba48GrcI%2FZSDsuVwcfB%2FlvlNExKhOlQw0ucDiKr9WtDzN3u5nSxdlCgZNf1A8wmnFOtYVMMSTv&X-Amz-Signature=d25f0081cb926c5a585747e051f22bfafe85603d611b1d646c10e49dcd03f111&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QG3A2MYF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042629Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJHMEUCIGGYLbQS1Yvu3Yp9hCCDZvHabpH%2BYe7B2wjEAdnTBceRAiEAnYWzEvgD6V85ZIMowVJRUWui1QGUND%2F6xoJeJFI6B8AqiAQIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFtwAxr7LshtItliUCrcAwXtly%2Bkf4VVlZ%2BF2JxOBfFIv7T0GSyPITaGkGXVoMHBG784bA0zHHcHIrj6I%2BcbBFt8qZl%2B9yHv%2F%2Be1Ed7D%2FsiOAtDWbz9QYpbXruJxnfRXRIjRQtEPGEAufogEC37SqwXuLf0nCpr2iWJe06xIqYnZegRxevF6ADE5ighfABc5y1jh89tPwnIDag3XR%2B9%2FQ3E3021j7950sEG53hq7Q9ArYtyFdvLHYXP2oXTD89HbQDbt7MvMI2iPJth0nhuqy4H8XoIWLRUpYJPIez4ofUYt362jh5XapqQWGUTbijcuhsgNLDw3QCixWuvc5aivpjBxA59C7ypmg2LH%2BdCRb5EbixapNeA6kswEwKuqLxG7OXcNj6q%2BWvLwUTQD%2Fcmq8mDXoicumOMDXmGJ0s%2B1CCe8dIUGFi9vh6%2BG2BkderMAFJNoHjzh6a6Ezvd5H%2FjLokaP1%2BH6X9PtENK77znBknnnx10sHL5bOxBhWlDySRoj4z12hBevDL8HaWH7aAIJEvwqebk2o49Qmo5zdj6PcbDyW3JfJNkFZzVFjb4OntJFAE6F9f1zaUm%2BNCLzWmkA4kvPB9CvQczA2OS%2BZ1ksTHcx07EMI2xjiKi1dQszn6MrYfnqg4qkN3xqhy78MNCzm70GOqUBXGgTEgeRmeUA8jybEZq0Ij3YGDehrSo1wAtTLoEfhVaeBFodvv2oDv6qXAscpG6C4VL1RUQzpxRoDnGL1MxqHH04O2UCxuRPi1kifQmHozrssovHz0SUKsqcqkrgQw%2B%2FiZ%2FH9niVq14aqIIACtw8Uq%2FL3dckI5wkm3afWntp6tMOHpi4blqB5ObpgIJaAlFfSNW%2F07AEO2yEB%2FEW4s%2B%2F3ebhiL8V&X-Amz-Signature=8c95b35d0f059bc492853110e4c908a3e7629c3b764d6a12a09e52d100270746&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=4201cc874bbde59e5ac6c2e1d0ba2b9b00d34d3ed7470b016ca8abafb9cc7aa9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=cfb1fd7917ef3c4b5c7a826b735e9ba5dac5dd8e28376a100817f6d7dadc136b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WRL2O336%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T042627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGwaCXVzLXdlc3QtMiJIMEYCIQC5KPvmXgcHbcYP61x1axHlgS1dcL8llSL3iy9LAtZXAAIhAJI%2BkavSVrmo4v1n1KFBNsP73gW90vG2FX0raffken93KogECIX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy2boDev%2FHQfosnGMkq3AMj1%2BKz0ukiVCFGmjEJfaim8BcH0b6LvDr%2BJB1OaiWoUG01QNHwvpNImXLb0aeN4aWPihXJzA7LkMLBcxW8yV3LSwlTjHbVapsPE0vFBWQSMAxP5JAdy6wDwuKKZsbLdcCf9iLyWoWIgSDlECjxQz5yDJv8jnwJkj9aNitLzTOSuPo%2B7qxH2tWPxBB7vXvV50%2BgYstiyOHbSM3tKOcYpYdWR5uvOOKkvT0z0oA%2FwDbsav%2BzKrWfsOsMyIR8WwQ1Tr7fVs1gNO4eYWCf9zxk3Y4MUVUKwb8NbqhiISpRh5I2ue0LCFiC1eUHJRBCdfmt2M7HWv6xB9kVWiEW5evYq5pTXWxYHADr6MkaxRspIK%2FYSgPRBAcPtftxhrTcFNrnuil5%2BqPN8NLVvLBe16GuUru%2FJhF5xlTySTkxHfdemcLvp9jDjWDm4XNgAoaocD5CZNcC49Da3uuLKWsIBk9hwIyzRsVd0FgQ0QmcGEGLh26Vs4Avt%2BcEIR9vLwk6Y9Z4wu9RXK03Naz3Pb3UrUbjvZoumRoR5fCKl7%2Bu0zJdqgzRtpCG20FfbmoFcv4j0zPJjzpgoxwzikqdexgPaQI0Lvl2CtOT4HfdvPoH9XYX8p%2BPBdNPgVJukfyK9X5tBzDatJu9BjqkAUftAQQXhfTkwhSu%2F2n%2BKwGHWZaiWIIefc1bbEwEqjdlTVJd0ufMwZNA3oxquQU3Yg47ktzsOen0V7uMMFD66zQcvUT0PXwZTiiEy6NVqWhBGcvFvLm1mNkfzkLr3eZ01iHVI2hc%2FHNP%2FAT2XGDUGHibKoZU1jzKMD%2F4937ruJUokvfDvMmppgqgiNqQ2LE5rIiqIt%2F8CxO7V6INEY2mur1ZdkOm&X-Amz-Signature=e04741c2b746cb4485fb1044eef9d324d2324a246c9ea63104f52c71bd4688e2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

