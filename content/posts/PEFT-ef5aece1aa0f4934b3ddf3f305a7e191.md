---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662CQPRUHH%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T212140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFpX170PuIlN4ayUn\
  3vV%2FMnR2tU52yck3uUwTmxtu9rQIhAMkffG3Vo%2FV1KUlm80XwKY2gjsMsE5wS06EeuTsCQ0yb\
  KogECJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz2PfpZfxjIoZoBj\
  VQq3AOwTTaqFGdzKXSf4i3KJsCLFVGcG6p10kC33YfWuSICwEYxTX7jEEOvd7OYlghh%2BoYkW8FB\
  A%2Bq0ISjU8Jql5zXmCRgMqVmwx4GQzjRZcGv38boKQ05zMUqclpUPDHmhXcQ7CxsFBfO1Chm%2F9\
  LJvZNjNh4HRuzIF58U3xZoqkT1Pl1tG4UXcLbxzWX%2F8NM7I8WMfImF8I4CBXGPzjb9fT4dQOPyy\
  djhaeUQuqi2VaqRFx1jBLSqjIoe5iBMle7IuHlaXsmAoTyU3awmifpgtFC13xv6WQMcn5K49Np%2B\
  yQoc%2BQriJPbUkk6gBmgZOOOi6uZPmODOQh64dMUWvKSkpJOfOv1BmtFsPPY4au9dplK5J55MfcC\
  JJweAlLmlyKpXxN6Iu5H25uTIF%2Bo5ykHdMjA9Th20%2BlSgYcHPE5Y69pLclspJeQEogGUHieli\
  IcceoOKjGlx1o7diihK0%2FnP4xlWXGZeT4P%2F5lf3uMIKcAzuWJ3ErldnWtiqCwbgkKUGvkf3ft\
  as2ePPn4dApG0RCYncc93%2F9BaHwFodaHc4hKkqWHC0%2Bk7RijjNX%2BY1weXVEsRZt9%2By0bZ\
  7oiStwkdNHcgXzVpPThCSb7UsmhTXrWtCz9E668ooxEl%2BBq1Z7JJDDsqeq8BjqkAVP1XDodDV74\
  k3TZI1cvW%2FgDryrO%2Beo6MDxIbcjXTdyVB%2BpGbgiQSCFfrIxejuTXwa00BUhP5XkvPS5%2BV\
  M0QhSap97G%2B%2FPncSV5H1h%2Fmu3hDY1Ol%2F3ame7T0KyxBzXo8vFgldlHdkLVDo5bxjHA44z\
  w3S3BEp7u%2Bjeq0fwoGlbUhufG7xd6rvXXXirYXyJrRjD1cZdsUiwccB7JB0RZNYnN34MVo&X-Am\
  z-Signature=963a79fb30fa9590a95089001d01541e49219f4fd411a398076ee44c7c3d75f6&\
  X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664GSLGAPL%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T212009Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCVuwjT3Kk80cW%2B2HXK8qFLEptSLRDOZiVSzuPGeNIdEQIhAI2g%2Fgf1gEx6cs52GB\
        3HtWsPhfUWBoq8DZL7cNz6fvAxKogECJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1Igw4EJ0GsExUSloMAqEq3AMlPHwpGb14B170zzTfJyXAEcfmKiKyP%2F\
        siPfFAaJYErLt%2BWzc9iwrOxZBkKuXsdFMv5Msdxru%2FCShmPhgCr4uZxT8CqJnATacDE\
        O%2Bgs1JX4f2PHkQj37EqCKt4NGlnP%2BleJp3EndSo5QeIvtpBv8127eDpJJgdTmAvo2tT\
        D5A8XzdetxlNWfi5W7wlWm2dH%2BEwc8xNP8LAko3Ef1cx5jLIymWURqp6j%2F0i2b%2BjU\
        gGxghuJI8zhzzUGL1mCAmvN%2BxNtEX6XKYy3c%2Fvb7wOS43mCDzSKrB4Nd2mcze8FGnx%\
        2B5qdI74vqwuswM0uZBXTHSseJaK%2BraeMpVSpB%2FZGs7GEYNANLzsLX8qlqZwvt8FFg8\
        Zqza71Lq4QMETjkg86gj%2F4WwQPPn6LUpFVsql6bawyW7fQcPkY89LpNoQ1vQNDV4ivkMV\
        YGdRB3nKgdv06qtB4pkJYbxq1Dcnh7hl4KOHGYojYq%2BTy9uP6%2BrrrRQJyyX9m3QYTtI\
        LraHrMmVEEM%2BJjnKduAsSMlLcNDamnlqGEvybin9naIr%2FakM4p7GbCt1hzU2lgX8alB\
        R6aj%2FlBxuFtTBHX0V74YOTuBfXgqkzk0KzxFKqU12L9MQ8POEoH5jfKkZz6zEiitDpBGD\
        zDNquq8BjqkAegSArgVwkysi4%2B4geLzWkCKiPC7rsjrEcPW0aQAFYU5zJPNhx4%2BZsIj\
        tUZd6jXUPyiJzdQl9pK1Y79dNfCdzRg2TdjRS1skHnGcWbqn3SnUDWeT2SZ11FZ5ehy9f7T\
        TBX2WNk%2B0gP%2FaessbAxqapem9oZvneEFt7RU9SlaVAldcRY3YXGpO6zIO8VQghmgaB6\
        RMQx3rAh%2BehHayEjUUEY9Vm9hN&X-Amz-Signature=0c85faa800fa7dcd8c9a1fe3d7\
        8451ad9ecaed5db16424cc3455c9b025d4f72c&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-01-29T22:20:09.043Z"
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
UPDATE_TIME: "2025-01-29T21:21:45.370Z"
EXPIRY_TIME: "2025-01-29T22:21:33.904Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=14b3cf86c427a216cc2461ce9dee39c15f4ea34ed3857b06484559040a3b984f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=87ebd678adae293f0d234597903e4f28b231004111dbeb2c58f01736f7119595&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=d2db082878327a5a8f5c200b217183bebfdb7bd133540b68dd4cb491d09a3e53&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=15e24858368a08472b24c3257f29705d813c5b7a80a25935924b2a83b98344dd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=a4f4a02c8efacb95f8f41acebdb0bc54b39d99884cb0a00998fee697a12ae9e5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663R5YRJMH%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH7pSoDr0x4s9g%2B%2Fvo0WQgH%2BWrQaHKDcm%2FBvNZLRMw%2FkAiBccm1pvfAyGKBA%2BW%2BEtj9wwKPB3TNoacB55cmldbYcriqIBAiW%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMw5499kWLrq1W%2BeU6KtwD0wR7jId5DVh%2FsFuelNMtjvrEZCWHzIbpRTbh9md%2F5r95XjP99XwRngw%2Bodb2dyhMR5lrHRrnXIh%2FydAOy8EThqCfwSkp8rxw8ji9tPKoQ6R82cfhP5k8wzq17vAtHc05TR3d3VkS9G%2F1L1J8dkISlINCaUX%2F0p8ViLfhwiTRS1pf%2B%2B6caSpEasihPBfRUXNjNchdjprA8KrBhY%2FOAvJMKa9UUqUx1DyXk7k1LABdFaya813kOIBeHUrARpVws2BkUH9V%2FzUSo6gQ%2FgMQX3yNegQ%2BrLczt0q6rxmVimkWvqlZUa%2Fk2s1CmPZMjJ1n%2Fwfp4jC4KYq1gklZkLdxQo%2Bth6UQ7325FEVYfapWV43%2F8zi8VjHb6gBT8fvsPY6IJ67clKdCWlPl%2B5juB6MeUA26WFM84mOwtoFELr1Rgm%2Fm%2FjjyItcZoULJAqwS4KtS8qJcJZQhP7QM4pNR7AO%2Bc36EAKcy5Cap7uH9%2FaSr2QWKF6qHzXk8zhRSKDwxwytSf6LeXMgyFH45uxweofS7Tv55861wN3PtsU7%2F%2B2dMvrzjyatmadCT3PrPu%2BZJUgD%2F9jKUQNK7j1bLYV9ZdPOWh7eFRkwixmLhW2rqPcQExzMghKu4V2L6VT7ALD7SeJkwwqrqvAY6pgGkhyutRQoHSEyZktneLr1JXnxvgFJPeLDqex5UW1p6wbKxm19ezg%2FAf65il8qhXi6ZzOCtLzBDWXZERgpgyRezgvliqDQ59fXPwFUoqrZaBJ8JjQsWPpogFExxjXPEILEt0EeQsnBQ6mkksKb4PmTQC09%2FT%2FSIm%2Bs0wBGunqNNWIPVhpT0HkrQM%2FazWqb4Io5GMy1Xvec30iAjikOyHTj4%2BV8H0ejX&X-Amz-Signature=d5a340756b385baf3342fbe4a9c7362bb62ab83cb4ca3c72b09171d6ec624f3b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667MBUZGVZ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212140Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZwvvjoxLqu%2BZom15%2BpU2MS3oHu5cx5H6S2B1cKp0WsQIhAIMVl5ZTJizCZdlKgnJI5hKS9N308FwP5ufomQZcbI0WKogECJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igx875aCemUJcw0YNNEq3AMiJDvxRAY7VumWgX9GSAbO9CiSID%2FfsRKbX6Udh1bPGjAc5KoopLEB604%2B9B8I0PmbRNld8b038j59tL4i4vvKGDIU6Wzluh5Pd%2FhGP1Vga0LYWkPG4uyOTBa2xLnAe8uelN9xhjEVacPW7%2F9%2Fsve4bS1hdnn1gogkv%2B1c5uHjO8r1RlggAHbJHNAPA0XHaMCw6CZPpVEoE6N7Xq21%2FrXd58k0%2F3B%2BPrbF%2FMeazdgj1jNl32uXKtVeTaiYdQUV2rnC92nd4XyygOoiXLPCMcLsbjalSIA5QWYrVrkh6av1S6c%2Fbc6SkIxIGc0o44hYU123CUxtMJIVN4Lw8tmfFMZn1SMMklmzK1PP1d3yvxTP8G1zJc7XZ6j7h0VbEY4GfjVTEUZgWeSTETddA%2FbhDwflQGXszYOoxUkvSjIImbAAiMZyIoKnoOKwhriIYw0aG%2B9JLwBRzonf2ZsGppp%2FhYgNRf79CqtuvRkO9WN50T5VRqXfydZodI%2B9Lv17vkPnfGthK%2FiVYgDVAOGyVEbtiBjN%2FfiiT9cn%2FeOtQr17toDMcy%2BUNAl5n3deHka2ErhKWibmgB1SQkfAklZEbUCTDi8VEJ0OAhCs3Jxw08Bee4j9klelibQO%2F8zadCytwzCtquq8BjqkAdFMU%2BydyCU%2Fa060OqHeevvlWikL16o3gnjAVOo69CYLER5gWG3YHIu097gMMpPQyWHdHOQS63YYPKHQTmVf%2BwfKCNv2baYOjykWSSdoGoN8ioZva9EjHUb%2BNHkXr6FylADaGinYCdNubywMH2AcXcUPgXVTQdmidiUjivSrLaSxlTslGeC4omjAoikbCXuQ4Vn0keVceQ%2Bk%2FZ%2FhP5xyJIbfC7Ik&X-Amz-Signature=f25c0e5f18ee95a33d64b85e05fe05e0e639abb4f808d290bda1948397f43c7b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=be8450f06b63e6f8258ce7e0ddfa3865d9a3c47fc84ca2b676457c0844ab1e4c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=33603766895b1b2784d9d4af6a3f01278b7a43de1eb6fe4e3f1422362a9c31a3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YR6TN2X5%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T212138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfeRVnQlx6M1%2F3nUp%2Bg0YFfNCv9%2FLEkVD5BldYkfUQAQIga8fpQrkvtrI9qGpfHb38vVFm6YHjyGhxWjXepDprp6oqiAQIlv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDB9dClKMrX9Q6EobZircAyceoR0u8YKsL%2FJGZ%2Fzv6pBHpOX9J%2BiY6mgS4MccS7xGjwcVL%2BBJQ%2FgSsrbgKBcgqC9RCoqORtmlQF%2BpyPu3deIq9pqxbZ%2F%2Bmcc5vWy76VGBf1%2B28lAmmcnIEGLUnKn%2F3%2FgKo%2FVDZXHl8V468tz4JNFlnP10QHZFcZmu3xUT4VcKDBoJVwv9h%2BCTDk8h0zvtr5u8klYfWkZXuSItz3X7%2FXWBazVQAIU8xfkyOhLFH3ar6zD4zSgo1VgWEnTER61kVKaaWAFlEpRNF%2Ft85%2FTJso4g6tCh%2BB9Z0oeDi3hG9Ju4YZ9OK1pGDEy00rYCjAMXQ3q%2B0nbHk7jTR0%2FVZSnECZ4mWvG%2FXuneOi%2Be%2Bf%2BYvBT4Vg7jOnNuBddpFzaBf0QbKhx6Sfm8cyNQGB56NASFa%2FWa7n9%2BZWd1LyXDEe5oSuf2f1figIHFbE20st3npy14HWniz4eODpMLX167lUSkRQf2KxLbsWZbxea%2Bh26o4kqzHqZZCpAVm%2FbDqwdG8V%2Fzy%2BvwpMlM3a%2FN7RB80vt0qmyphEvUuGm%2FbKidEAHrUU7Vl4GlHWU60Mo9LAJfBQ%2BQrBJsgti0OquWkXbHcCfDFXlAWqY4Cf5bJHZfMV%2F%2FUB%2BuILghQM0MH4C4FWf5MNyq6rwGOqUBFmiry6cUzYQwvhF199B5JZOPoPdp%2FdLVQgT58mPel0tOBkyLL84MrqzAyRvUULxZdA3L3q1A50fTcJKywv15xxy1x8zH8K6mgLdKTtMjDMfBCKUIIP2WLNa8Ftc2sGybltCBBtEu0S5F%2F3OHpeubI8g%2F6xaslwuZcurUqpu5D57E0%2FKiy6OFk8v0IpSkZgR2mYFjoIzmqiqGA4eQEFU87Jxwkxff&X-Amz-Signature=56688ec233264e0ec93be74c59471fd02ef3ec0f551020cb7728234333224a0f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

