---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664FMWWTWT%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T092352Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEID%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD8XmCqIWLq%2FYdkz\
  DDGlM8dyB1F%2BQ5BEeIsZsPJ3eQ1EwIhAJgn9mfj4mXMJ2tNQ31u3mT3IFsuCe2fTWAHNfXBL8H8\
  KogECIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz08DfSWo43VIQbZ\
  Lkq3ANEK5cXVpJJJEpT3WDkwuMxb907yz%2FAsaTvYk5NeUgcoY4oLZCu2LQIlbOZSYEcdc8pxZMb\
  e4UhqBEom9IqvKFDjzsSfFuFZWy9z3BOcQs6nbgwO9BqQyF9NJdwMeAngostjXID%2BNvtcYBP8VE\
  J%2FeLkU5sAZGTxb3I02FD%2Fd9wKdSU111PJ99dUrQX3UCeQi%2BMOcKljs02F%2BsEiGBlgE1zM\
  P4dx9cNGkIb6YAaf%2FD18%2B2PcpGMgxjl1qBymyQXUTvdqu17dyabTWPk%2FZuWJfGbNmIx48E3\
  0X9DYRXBrx6E86N8X8GeSuldIUkuGdpq%2B%2BQStSNUeM0RYsGPH8y4MnRCTCcfRogvUjHvu6xWC\
  lR0KDgSVp2wF5oA3lsQP6laLI3VfftqtpB%2BzlidyRLW15SXuisB3tDA4d5sVCsD%2B28HO0jwu6\
  NtX2fyH1k3yUY31y9ME%2FY%2FDgL%2BPwgX4ceL%2BPV9A3ZmDwTIJlJoS2hCZGBiVoxOQuPtArD\
  %2B31oVNuA1PF1oYRY2SgiHCk1OKDyMsy2GcdWjURo4RQwXLbhmke6J6MnKymfrGh%2B7ZqiiXDEZ\
  G5vIOVT%2FgHT2KOtf0x2TLE389QcbsGzFZPnelSY3uYK5wyqF5xInFM6%2FKDRSlBTCpyOe8Bjqk\
  AddsLxet97j87ev6G2YoWHCq6PCjeY1Fv5MXod10MHRcWBFkPT92S8sfRrZXgxz05t5%2BQ5RgMYY\
  H5De%2BJv%2BBPgpzuOcCdEbjEhxB0Jzw4e2rCFnUnMS%2B5%2B2gXtwRcSu0N%2FM0jK0HSk6NKB\
  X12ia3dqBMSp2FWVF%2FCHqI6qJyfwYKz5I%2FyOige%2FELCOvmGxUYu841BpV8VobWfQUzck2VQ\
  t0DY8Bz&X-Amz-Signature=893546c897a12f4de86d2353ebaee1ef4e49756ef2735434c1011\
  c1cf04d931c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667NOZGIPU%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T092242Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEID%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CICLHwIlJ6yE%2Fstbf3HRO7BMxCu%2FsV73TYqAFD8aCADd3AiAYi7Howf807WbafH6RTl\
        U%2B74Jey%2F8e3U0s%2FCCxEkV%2FViqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BE\
        AAaDDYzNzQyMzE4MzgwNSIM3sxw8QNJ%2FA91frtCKtwDLrXyYq1rCV%2FnKJZ4wzikc7QX\
        afpfIU3ZMJ5DGvwx90J2qTQHD0aL7qaj8zPPMs65D8fqRV1Zj70cwQSY9nLzdqSfn0MCwH6\
        OpCkKb%2FDgo8njs1t6Hpk07TpuVp%2F9825GM0SpZH1%2BcriwDeiaG5UaFerkqvb0WO4d\
        dY4GywaBBN8JbPtxzSadPoPL90wlqwnGTmzDCKiY1wTr4Um8Rv84cHXe6tb3YdrygcfuOTL\
        8v6lqo7IM4VcMoSs2zg1cc3%2F9kkjm92N8jH2jJWfz8zjXPuy8cR5PfAMk0oODbiyA9pGT\
        w6ClCvluwjLFvVSAIB2dAtNub8jMOKj7%2FKyVB8JgM0O4IVROS%2FloX6ZVd5hTm1zERZl\
        %2FNxxglH%2BJrvvYs09D7SnvLOFrV13hpHi2kPb7dC15kNlI%2BAr1U00sRN2E5shHCU%2\
        FsZgyUTCi805tBNkRFIsNKmmofSF%2BMPlVpXvm3l9%2Fr90SVNUMVo6MH6%2Bz0kQExfLW\
        Vb6wVqFARFNTN9QXM311HH7C2eBkoiCOlIBwpF5iwrbsXwkcm3nmUn%2Brzdcn6O0PbVRP1\
        wxivSokTX%2B0z5xyyd4eMkqZWT06uW6P%2BTcy7tZeo55KumibemEDIp7RNh17rpJhwJt0\
        XcIkwmsjnvAY6pgGHJIRIX5TizUClwe4zkXcLx6AE0s0RgAU5I4xf5AUXDBGpbsguRjvxsD\
        cQEH6VEG18jv1%2FVkYwp9kQfzVxozHYyaD2ptbleJ5zuQP41%2BW0cFqMFVcXcSmfH8w5w\
        scAojsbyE6%2FdPc8ET1vZyDX4gooQgz0FRWENI12z%2FdcmcpDJVbt6VvVpiBlFm3CdqKn\
        XJvf1jXKyTRlA3W%2B2XyitqctpVHFob5N&X-Amz-Signature=6d8cd6511a7adc370d98\
        066c6a64657da976a8d646060b0e7532100969673925&X-Amz-SignedHeaders=host&x\
        -id=GetObject"
      expiry_time: "2025-01-29T10:22:42.140Z"
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
UPDATE_TIME: "2025-01-29T09:23:57.769Z"
EXPIRY_TIME: "2025-01-29T10:23:49.894Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=0dd1c536233c9d908fd11490bc4365cafa927ac1f23433f137c2ca18135922da&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=b1c09f4ef79f5ed0f4c7e731fd75636bb1ed01e934ecb860f6c2d12e36eb8f1b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=018a9c5904b83952a93b2cebc8626186aa6888b1b21c2e8eb91ff1df1fcdbeef&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=2fde9f776432890f38689ababc3b0f2564be125f92237ec63658c925b1e129bd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=1aca62dcd59f613adac3c81a5047eb47d12d1fc59907cae0ac860a1a00fb44d4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VQNRMVJV%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092351Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIChQFhCzsDuqYAMI889e04Z9OIiEnpKY3qYvqZ2lp3V4AiEAkZoK9aJ5Bi%2Fu9giRGQAc2aOPZo3dedFg2XL%2F%2B2MU%2BDYqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMDQHkjMp5Xes%2BpsBCrcA84%2BpLKnuWvjjAJCLwxZAtibtRKy3WHiE0PWC9wUSKHbeAiNu5SOlWVz7PrkqD2NGeuS%2B6U40WeDYdKTz3ZKP6qtZO%2FfZrc2R%2FoVXJG%2BqK5C%2B85WUksRks7zSWSWMjBvFgZsBX6kTw53LBxjenw1jgH4Y6TxZ9cNS7flZPDG7e7FuSb3XHhNpyvMd1G5ZCP5Ohta5ZO48KgrIAsu%2BdeIrPKaIn6DbE6%2FeRun4aZ44PNuc%2BxI3lZBobinymdF0fgAyQtVzexjvyofxmOmFn6a6fp6jUWH%2F0XaKB6F%2F8yKtOTgFEy0Gc%2BIJa6RC%2BJAnzy2qriI%2BVl%2Busiud11CMZzJ49TVk4DeWozzWN6mFuTBLzgNAtcfZIcuA%2FfcePzzbm%2Fa5ekZUxXJ82ONbiw%2FviQkR07Baa1UXR3pgPr21gDR%2FMF1eQ2WmEtz6Ak4H5%2BY7Ik9aFnmq4DnJwPVUX3siu%2FJhXbp4cHxm0xnCDYsZgLiE8LZQ53A5yqG9I7YJMpU15nI%2F0wK3iDRev3WfEXFW4Ql1CfNmdPHBGjL13xaYfwdwP1mbI53LVM7ks23Xtr5O8MS30NPIbzxUn309tqgjnqYdZK2lQvZFNTr4XHOXPyWNTM68TeCEsicNw5fdnHoMNLl57wGOqUB9joxy%2Fc%2FDZUg48750tLGe4DruyJDMc2d2Liaiiv%2FdNkkHODlh8fy9xz4cVQuA7gvsu9V32x6aVXKjoUOddcFkH903j34e65E3gWNDtBkja1zkFCA4xn%2BQBnWeIvpX4IdD5D5q3G2FKFcww1cbAGy7rrVWdQcjCBam7Pm9xQRDf%2Fu8X4hmkH9cvdJMPcWhSWCQiOYaUG4sHV6yLVw4FWSxmhRCikG&X-Amz-Signature=0cd80a776cd1e01dbe77a38d56f51b2de7788455467759f5f521525c514bc022&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YNS5TUGR%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092352Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC8dML4a7qWm%2B%2B3bKg4Bwx7HwZ3a6BTkikxYsylx7A13QIgIwL7QsX6iEuQYdUQ2UJwx8DZ8fU4%2BGPzQuUJYD1mRlgqiAQIiv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAirIJevJDk3RqXeEyrcA%2FoclXC2qrq6GvjeIHExScSSHgnuImlu%2FYRjrnspbROfl1s%2B8mZxuHinhrx1NmM%2FtKqxI%2Fiz2F%2BQs9t%2FZf83v9DIs8vTxrFvqSNj%2BDLTpJKKKqKaRUahKGjldV04D48Y8fngZKXvXkWX7roD64b%2F6DwiQZSj%2FgHrOypFn0wYlnmvdUrQtvk1qLh01QK7u3VJTNjf25gFTT9iY%2FCcZPmiqYX%2BlttVhAts4YH127XI%2FCan71zor5ZxfjZ42UEutDWhQbNz8QUFE1tyFPvkGf1KQqfM7gcIbOlDSCX73QIlqiFPMilhx2kkRymoJXaynvXW397JlqEfxDrpMF8j8Da3GrWjncZqW3QgwxddqccsHtsPFCf2xuwWavnm9Dw%2FdH1h1yDyUNFgy%2FRiH2%2BJgSGgx2j0kpmHNLeAQuaW2EJoq0sKO78jheW4HARjUEzIlxkf0eFyJZvOG6MVYYPMUm6gV8DOdpqtvZdnd5rcBSjOBz7ixUkBuG1dcZ2zyXMHvB9Gn8D0ID6Gh6fToTYb%2BahFIJCg0l0EM74kWvbx1wFhN0u2xdI%2Bga5tIZL8Py3foaIP7G1%2Bx%2Fr0T3Mvx%2BoNeAx1zuxavn6A5SF39SPOob7JBpp32TdSvMi3AaZXG394MLXl57wGOqUBE%2B13tVG1xOVjQ4kAAu0D%2B5FmcBhm1hKOAQxlFlcRH26QIuoj%2FDlEiFOhXuu%2BpPeduNH1lCZMwXwXxzJnKVLDAQDzN%2FqeW2NkXYFoFjOiqCqBdO0VTvNYnq9EeZZEd9db4i%2FGJZWa2eePq6D3Dj5J1CGh8F7aHIIIEmnCOAbXLbeMrCXm%2FGrdqbJ5YVm21b00TJyn2mRNX2xwhJxvnfUGnxxFZBnc&X-Amz-Signature=60b7cc3b65ff37b93ef4caba0a427b656ff6a3ca8a900ad5426cb403a96421eb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=aadb9a72b87d809357b8c2ee67d4026be70ad6f131d2a03944af9523962e0595&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=f528765567287aedb3e02b68f86dae1c57c19c56e7972a60e14219b6034502a9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QYMFKYFJ%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T092350Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCTzHEXsourlpawK3Nhbu40DbVOJRdN%2FizQQPnnbsuBRgIhAMUtNpR0veUcLspeRlyRdZI%2FalYX2YjtyVdpa7S814FWKogECIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzgG3QIFHWtEJ2bMiUq3ANRbLjvQXCP%2FLHm3wgFVy%2Bq9t2a%2BcPolhkbznnYC%2BT6CmLsfn31xSEtO6iiA%2FJT8t1wt3PPcYw6UerHlsSLs3mZPrFXqucqmIeDfyd7geAqq6jxffj%2BZxWB62Se7XRECuFRU6UYssgZv7wwrUi4xubAW%2FFM8r1JtFXdqd%2BKK9v3K4bTMLIXlgXG2lfh4u0swanyB4Ijq%2BepWd1aypVJHQyP6JWsYbqK2tVEz9U%2FgsX5iiDW64Mm4mNicYg52p04kuYDqBFsuL5umJWfPpEej%2Bv4bLlYPSh586L1n7anSpfbKeBT1pp9vRo7MnAOBmZS1vqLq6EWSvQqVGJsdGxnRIXZa4G9ZHb41o8ri8M3mkYZe7VoompMPOZ7D0hkG8y9dljwyWZTbgQSGNiMZVGVR6MHyXlx5eS9B%2FpJA4dtoEN%2BWsVDno%2BkkzVBs4%2BJIukVWYcGr2KeOVqmr8wMbnryh9%2BjYKcqWMu0ApUXZNRrCcgBP2glGThl%2BjvDPUv1cZQKc1VR679d3x3b%2BCqxGafeuOrw8dZVraWgHjTgnmevy4CodNgenxI9IeZvB%2BOinbaqm4qVYY%2BCHG8m674UycB8cWM13s0PLWpUa9bCyMDQ6%2Bxx%2B4PwAuce%2BiXejBfmcjCD5ue8BjqkAa8V%2FiaUGAzr%2BWPxp8sQ8G5439bZuwFmB9ROayEf5x1bk8MSFz6PRr7NSTo6cqfulOLp9DIyzfK2ykyu%2BTFIL062dIeukXoV39DXDsjIdEzX0%2B4k51X1BRzd%2Bn0SajrkmULNsmqaW3iQGEsZ4WXGC3Fw9vissa9r4d7lprswe6VH1HfeVDAxJFMpUX4VrJ8mRZqOyhEEOXyTpTbEx35I9m7hG9Fd&X-Amz-Signature=6151be1dcb03bfaa4e64735bc2c31286063944bfcc524ae4907ad9de6e27275d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

