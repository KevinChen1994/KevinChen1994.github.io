---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZPLKIC5V%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T072122Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCQUsuCzX4GaoT0N\
  VTiR3lnMaiQsmuUSQd7%2Bebd%2B3qkuwIgK3sBuMAbjoUY7nNj8v8vVIEfUG0P3nrUksqTkJTl0n\
  Eq%2FwMIJxAAGgw2Mzc0MjMxODM4MDUiDNZHIrX3e1ypP%2FmqYyrcA5AIBSpGL5b7qyE0bNSwtHb\
  IgCX5RQ%2B%2F9kenWNN8UTOwDRb2BEND2TAHQfbalaL8%2Bd%2FNG4pZLXdz7yau7geNHyd1SwMR\
  o2N85vHqI10yDTMiOnIAGHxVtQd8R41Ve3AP5jFbX1v2pe%2FkbruphEi%2FjhnXlxQ%2FGjlRwFy\
  ceHYSrh7%2BEiCbZ8G64ZrkE%2Be8NOEnJbTNdd8bC%2FudzIUy7UBP1FtfnKviwqOmrOpcd%2FQZ\
  rqM58ndfefELIzhCtsE%2FMhtH0GOkNa3UuXKSkwZkedd%2B5etxPZwNh7yFubwrETkS58ZC9vAEt\
  WzNPg81%2FDTSRBecwgWSNwA8RbsLM45sQJFcTHXK2Tkj6m%2Fu1vuVY5LyWMJK4QxMoxKgJCIwGf\
  q6RhA%2B%2BmuCYi5VW9pON%2FyM3Kfuhsw77GEUzaH50V95x11%2FMExiOF615zs%2BvCSi2clMl\
  n5c7W%2F1%2BP1sfyUL%2FMPRmN%2BNEnUxptOuavnQli8lyxzNVd9XE%2FCd7OZc5XREcGWmHTC4\
  VTNz7i65zDoFV3LFE%2BA2f5wKh%2B%2FHCku6rqU0vLTcddW2TT%2B%2FHt9YPhdL%2BZ1Uy9di%\
  2FrKpTLXhauvtZYDO%2FaLrxmKMkCXraDntFdKNL5efqgfaFYJsx%2Bk9rbzzCQOMMO7Au70GOqUB\
  ewMmbGwesRsnfk7BTis8l9d6WMvxOHMCKkR8LqQxk1xYTFbDw%2BNXkUDVKD0NDC1NSONmC3Px%2F\
  saI7e4d4m3uKmr%2Fh59%2F6J9bsYE14jCe0H1VdW52VkMtlgkeLOG6V5XKwh4oIcV4rA3ocqf4IK\
  qR37JgRRCHOC%2BCFI55yoLduZBtCTZOYSqKmC0nnRCCpZNdr8sVhMGZrV0%2BlVHrNv%2FWrxo6w\
  yHu&X-Amz-Signature=babddf2db972ca2595e6318662ad2a3846cafd5b81076992c58f7b7bf\
  7783813&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667LNPONFX%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T072015Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIM\
        EYCIQD6YE8CV%2F9bRWx4Oeh0tccqNsVkWox3WakLNe%2FJJWpi3QIhAKcF6Bgop%2B1771\
        ytZ2McYsBwPTaDse2a00Nh%2BXXXduqRKv8DCCcQABoMNjM3NDIzMTgzODA1IgxLUYd6Al2\
        spCEUm2Yq3AOD6EylwXX3tzUl%2BHhq46W7kErjxk3OJHQYyb9YzUQgkLdrvHNdjFm9CCVA\
        XiwMXvuf3atB12NZhJ%2FTt9%2BPRq6vzC1FQyv8SEqrx1rvLMGbL4L8uni7gvsETcDFO3B\
        eaYBuEwq70ys%2FP1w%2BB5GaFVWYi%2FgByAalwG4esjeq79w7ML0EkYtZKklyKot%2BOv\
        5T50EgSXR4qRk5EGDJkeV2sbu56E27SLY1iuS5Jj7WlgTxsp1LPSbPziB695z%2BHxVNchk\
        VWJGVuiNsVQtEK%2BiFwSYSJHdC2CbzmKqN0VOH8ccxklgy%2BgihpcaOfVeZKo42z9rm%2\
        FOEvUKq2UT8tL2msa%2FRgVw4dz3uaK4o5JOAtzo6MFeFXacewyzSeD7CaQzQYYV%2BN2nj\
        YKdLYoQPs0C47C4ljh0ucT9SFFMn0tf%2B1816T8ZsoNE0H704uLoY%2BYvG0P%2FeZo8mX\
        SBeEUoAQyUpWEvxC9s1BPTVx6istAVpmumsKk1udE1v3uWDPtRzLvv2dN%2Bn1bq3auvpJt\
        R2kTuxNhi9ameZ2eRMGfE%2FdGdqdtNU5FcE8R8FAL7S1KLmsBq9ljNYS3aSptp1wrcFfAx\
        Bkz0F%2Bc%2BZg4QkVgiXgWiwEvcnuKc%2BQT5EMPbQSY76MWzD4wLu9BjqkARE5ExEKg4y\
        eNH%2F6U%2FkkL5gS7Ow187W5iONpkS6POqaUSzCH4uhemAsgLgaQWedHLMB%2B5AARve5v\
        %2BzCCMOcA7q9Ez0fFP5yG%2BT62WnP6UFxdFjxw6vuK%2FbCTwzsWlEzjUxULXMH8KA0Ss\
        9cU%2FwvT7atozrRmPJtpHV5j1n%2FGR8xWP3%2F7fQ4FFA5RycUUzTt%2Bl3gS7S5IH8HC\
        EpKnMVW3hrpa9jyg&X-Amz-Signature=0a49b77a0598c2160f9672200c139701056012\
        b5327a9f747d4fcd2e41e26bda&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T08:20:15.380Z"
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
UPDATE_TIME: "2025-02-14T07:21:27.087Z"
EXPIRY_TIME: "2025-02-14T08:21:20.767Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=ca5d4c9861520e7de923b35f0ef3f6a90907161ec4959477ecb9a1260b193829&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=18c76635f874deb46bed147863c4b1d977627eb5c3363d53749adf6021e94bff&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=ed0fd290f6d8e43892c25ca1aa5f14981a26ed592304ff9eb7d4914d480a8c17&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=6c260487bb0da620fb936bd56b79428f384ecfa6a87fadb18957b69f3b0056e5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=dc9bf4284ab9f1183331abc95152d8b84362f23b4ea6a337be6fbc1e751e6bfb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLP6KIFD%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072122Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJFMEMCHxzlS%2BwGbEl7BMd%2FMd5effWHzIoYRgF6Ds4oyQDWDVECIAH%2Bgq%2F%2BPB7XBY3EcysGh0oxBnlWM7%2FInIAp1rT24tQ4Kv8DCCcQABoMNjM3NDIzMTgzODA1IgzK%2BR8uqKeTFbJwmFsq3ANclUbqveL1gZOv80Q3U1GJHLzi6bWglySpu7%2FQwUruvrmUtXCkgG%2BGOOjqZ05OcD0rkKVLHiVZrIDlwcEO9EKProuDAQWHU4krsxCrEuy3BfjVskItrUGYSV1siZ2sJejJsaUsgZ%2Bw4%2FUea3V1o1jKxT8wJiaHRwutevmBBXJuEnrXImgIBlaHRQ9mw9NccXdSn0czl102BIddYD21hJFD0TzKZQ5JiEpbcorPAVSfbySf2XjzJMYedhqRm7CQN9xY%2Fi9kcIS3GdfjyrNE8%2FFYiR5kLRTeOs1kJi89Zp1%2B1dh0sTDVADcGLwgnoIpBHnV9opEA800C9nkT34cU%2BPOVrVe7TUXSycjcCCGwcjOuKxhH2gAvp74ZVaVvlSwCYxkaKq9VnLc2QAoJ1lSyPaY%2B9h%2FMcwhusNgutOyA6ONK3Tgf8LteFKS1oK2CWtMbxhwAWmMzHUMbyGlhvS0Nontl0qvRNKtLfKRZntmI%2Fw4QxwzRFWNoqhXtCcJ1aP3BYeaxVz2M1eg68knbqJzoOHcxjNsy0gqrFnXtuPYQUF8JqN45Jr7kOtbI1XHVIHBHj9TssQuWjesd6uG876i0eQvT2fHnniVmz55ljIGWRhBgMeOJvPCyw0WB0DAbODDZwLu9BjqnAVX0XQCw5DvlZJAcP6RfS4W4c4SdeB7T4Jmop%2FrY%2BYwAb4T5EdNTKfxlkKwkuG3MP3SriP%2B4U4ZJhszApFSqynJk93Diw52zCRNeslsAPpgfc0UkkwoTXpvPE4Q5S2uYrPi%2F%2Fz3ARjbfiHLq0xdowd9NZ3dwzh4x2Q%2FZzIr8WOLFSMRa0aM%2FeNZ2zNR1PCp2Q3%2BBr1ubq1Adj23Rs3Or8cthpsRlEDIH&X-Amz-Signature=efdce05f2b9e2d2bfa2f52abfe9e0f578ebe90b4238418e1486fc88146091756&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QCOHNTZP%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072122Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDzwN%2B3n5yOrM8NmhIaZLL93oDpY9sB7TkpgDkQKWJcxQIhAMi1XleC6gI7ldRCUSfzTcYO7sjwP%2FQhhVieM2P5TLqwKv8DCCcQABoMNjM3NDIzMTgzODA1Igy2iKLbQmSNmBStyRMq3APG6Dm6KzNPb%2BPJuxnBQE1hQGgwXaA9ggi4VgGv3o0cD8h0rV2azMh0ePQUWQ1xJ4%2F6ZKjSiR%2BwDUfF8wBtJkQ3E4AFzCMRRekxNKDE6BNBSSJrRbHHpyH7AGSoFMqnNvCtAk3U8MjlXtkik4zr5htAhVgzF8GwFKPymrotaizHYUAxUFfCVtgrNu5HVv8PXPz3CDq6JL%2BWkuFSUSme7uG186ZYzZhEk3bvYFQJzrM2tPMepNxuvzKfvaX29dkMkq6KQNfOFXjc2Y9JoggH4jVGm93%2F0o3GyJuHJKQeMkNPEu6JFEcFQjBUCPQxvBZTE0i2ESIy5m6sc6xFhZF1YrOzVnovZPJDw3Kip%2Frk7tCmpLt%2BYezwfzchaHIBMV2UenltkoR%2Br1ndKZWpYsdjoFu613xQTFDJNqvWlnbd8FYdwbEu590QPjcNuPX6j6RIFS2MnfI5i018ErrTeeqh3HTUSMuLg9TQtEPFFlihUKM1I0WqBG4ao3E%2BYi%2FaF0OvZiEjTBSrMJypAc74YtxziM8JfsJxNuXqlO6Jw9CT7doce0%2BdTdihVfMf26EX4mTCRRhEGw3XV9NFXybQhO8MsrraMDQR0UfLWof5GXhQ4Rkqsra6D2nGmN%2BF2f2IeDDvwLu9BjqkAYHP6oZR4VTl%2BlVWF26msBZHInHIxtgie37XpO3J86%2FiMhVfj6c9vXKvwloRPSbK8UIQirhn3MLdtXVVo57COdFMStls%2FSqwwPbmCdSSbjGWYtImEUl%2FL7liMK4fZzJbnLOQfPkgrLrTkAEN1xoPN3n4x1m4CpZBHj8F69S7Rdyg1nBcfXDHh8v3KCr7FpMmUhYscWVA0wOBeaVjE6K63ZcsZgFU&X-Amz-Signature=35c7efaadb151a9536aec22d9e5d0ab7c5287b20355ee38897d3e8381180a996&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=cce3a86efd52cfbf5e434561cf53bcdaed1d19a610c73ed84687f90a274c708a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=83fcbd9f58d196262b97bf30c310c00d747279cf47276713161d467abd2c8c25&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R4EB4ABW%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T072121Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHEX43TshhpFkwFWJzQq7cS%2Fa6moVYsGksFEH4v7MYJ2AiBJv4U2FZSuMEY2cz3EIQ1Ey9uzbBx0jIkDR3cxGFNT%2BCr%2FAwgnEAAaDDYzNzQyMzE4MzgwNSIM71Dy4dWDC8gwLRH6KtwDQts5krDpSBXS8lSiUOoW%2FWmr3yCCsJuZikN6VXyTgjxFwwWQQwqBLRNkaiW2HJnK1gObxDr3dC%2FhImrWu9mceTH7BBq0xwsDc9FolEuM8y66R5M1a5wfvl%2BVwfZpfLCI0wdjQ8NbPm6xGzcyHMzQcI97QvTDp%2F2mUQjnWdNiFu2CyzO6%2F%2FMcAS3nQM6Kx6ouAv%2B%2FPZgpySCXtfoUn5il9Y5i7QpkT%2FC81Gh%2FJt4hgkyVhk3GqoiapJNlQmSZZ2LCeTpsCJGGusZ4XUYHaVuVCrCyCfoY2QT3NHL%2BGBBhE6%2Bpi1NftUFeqMZDbKZx3WWM8DmylCczEEprE7d5z0K%2B5tqhS%2Bn1hWYuwCEjSDd7wZi4Vz5jpSD03nqVUcEbJgvjqRqKkGjBAxfxlvvxZULi8W3IjzwJOHORhl4G%2BAvZy4Evq2bMtXkgAZQHzA6P3Yog7v6divxxvRYvepEatMw96Maj76ZELhNvuNH3WFLJlR28PYc5LRXx9IxRoH7SiFiXFGa2jt6Wms1Z3AAwper2mewOOBJ23yw65Zes2s2nRmMF0ceSe%2FfUdcUYVLg9hhJ%2B%2F1OSPWin84%2Bc%2FScKl6i3pAeRqpiDrYFqUESD%2F44AoHetct8rsjdbwl%2FRq%2FIwzMC7vQY6pgEGHuIQvEJmXg9g8xdHVPLAItz%2FK6cW%2Byz5Xm8dZ88gYh4sjoJgs5x2LS1jiLphZipELgQBMApwvth7kdFXcCZ523rMr9XFuMjKaSlzRDhfg5ewEqgeJpLMRFcSkHVMC8QjwLkRrU1NfLd7EfQYEXQ7Z3Br4Xyk6%2FBBmpSqy3oFWom69URFM2K0HbMktqA0xwej7rtsL3SUBBSFFiYfho%2Fr32jNHW9f&X-Amz-Signature=2ae77ab5072e2f54acec9b519df910268bfefd015f167572dcaed21e4774b90d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

