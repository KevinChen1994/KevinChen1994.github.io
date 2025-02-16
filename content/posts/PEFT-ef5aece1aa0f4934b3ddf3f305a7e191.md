---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YFTNDF7K%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T182943Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDoaCXVzLXdlc3QtMiJIMEYCIQCsd2M4ciLiO29zQbUzqc46yaJ0BfTp0kQuKfCWDyXKrwIhALy\
  bYK%2FYpVvXG7urk0Zgvwjq1m%2FiVhkuvbJWRJ5pc8IBKv8DCGIQABoMNjM3NDIzMTgzODA1IgxT\
  ec8m4JqfGW9MP3Uq3AMegN%2FwiHCbk5lR3ecTb90otGOK%2B7%2B%2BUgyv3jTWuvLAV0Jx5%2BI\
  pq99X9LGEU%2FI%2FjCrfJHnNiOPyNTkNlyv0scItn%2F%2BV3MyMjllyhg7BHUsRzStPm3gDLrAq\
  5I%2FUsPg110U3ykX4%2Bse3Z988nRZk%2BpGLEjLcJUwHSKTSz2ZpqqZLcNSiKWQty%2Bxf61y1s\
  QIN2INB1qQLsG1ZwIu7iL4uL8NQ%2FExwYnbb1GOqeZBsgMNwjZC1AVxI31CyJgq3rXhVsMT%2B3o\
  uGbTfadfwlVHgU6Rlgy7nYMBVYsdPcqDJ0O%2BimIVMyRIlY7VggieLnhQ8Pf5%2BqRp5omZfjK8K\
  1iueu6uRqXs5DnXckcDsSvKn3hJqgxUfvogMjeV7xN1yvLEKrWjgPny%2FAs7unAlJ%2FX4BYpIAD\
  mNOscvFP%2FjWAUjZsAvXsAgaxcDWrbp4VVNKfkhsCAgWNz8yy%2FOTJrMQ1H2AunWCPhK3dPRtdB\
  fmGwLHTX6CU6u14CSY8ec2079m3L2ZV2fGGRLSakd5p9F7uNRsyP%2BVKW8gO7ZGy9pR4qaZeoGqz\
  2TUzer6gr4fmQXbWZXY3c0AsaGijh4mftU%2BxZH0dVMsiixa55qzSYG3%2FHZKcJfkQ697jraZHC\
  WhOO34snzCYwci9BjqkAZ0MzyvssVCNooNDwDK36EncvB%2F6%2FjHK9gJC3jsq6ExZEOypvqveub\
  fXJMi8Twxc7vA1VubfkR30OLsiPEOCCkh31TH9VOyxTAitzDO2FXLMGGnPYMZ6Y3jhC%2BG7JdYnI\
  C66iZTH2WHNRty1wXe2lQo%2FKrNKid3TkGob3qTD%2BTUhqLmyn7lRf1FzvUVwSdnvYw%2FRs9xB\
  OwVOdTdxzrVrqQAl%2Bn9c&X-Amz-Signature=ca859136cb2b7fb3423f97b0517b31206f3286\
  1d2e7aca459cb6b78c82ba9811&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WABQBY4O%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T182821Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJIMEYCIQD2%2BsYJy1Wm0tfzORuMibjLViH%2\
        FEx0yOaKhkyz5TTzrJgIhAJ8y7B%2BKg6I7bhdVzz93njQnGAwbSxhEHj3i3dFqpDXSKv8D\
        CGMQABoMNjM3NDIzMTgzODA1IgznQ8NZXiEGA2YQsZUq3ANT%2BcVfoKHogNhaIHJQ4ydE9\
        eidTe1WFyoruQiKSGy3YAyRzZ0XZ3twPxggaYixezo%2Bnk0KJZlPeC1nL%2BL5%2BUfrWH\
        s7g4938uMHtshnvJlEt2Zt6keUTMXeHf5%2BkIFU56XxskMs8D2OOhULMALuJvB2I2NVqXF\
        wPNQAQ7yVebbvilVGiLE6uEluXOuY0upCdCjR%2B%2Bwi4KDvzJrEErfpXsLUMuGL0uZzPf\
        pWuESkH306wjqN%2FjeJwkxUksjjDiakrXqMiOrkH5OOYPC5dZJ%2F32U4o%2FGmbVZSXpM\
        lSCmnaMl5tsEi5qp0xSqlrnuPOGFzSdNmnbhVflPgdKx52EeE8TUcedGXW%2FGCOg7NODiw\
        6Zxt%2FhzNAhpvVxfn8zSfIk7fHNjLEwOJ%2BTMY5mR9tnACAL0GzeelBaXqOwrL1Kp3LGZ\
        UO%2Bnka%2BP1CxteInYgZP%2F3mOFprCxs%2FqpTKT4tbrsCL20O%2B7xW07oGFoU1Wm0W\
        39pCp%2BDICRm9mbOywlzkJnvKsC2pZViNFUaF4uUL3JEtQW%2FWp6HwdvHQ8mF7R1nwIs0\
        SiRoiNCSaMOo1VFqPbp%2FLEPKTmkJV9YxogMjWC%2BsosyMi2RcRp1GpAWgXthsOLe3F5q\
        Mm897m0g1kNNkWhzC8wci9BjqkAcAknnwZG4mVGmRGBnC%2FuvhLLIhP2iMB2wbdcq5Qo8l\
        aJ51uY1bcaMiZi5ZOetG8wzeWrPI5rOn7ULkyn46zW6TBQtfDk68MuJg%2FAlNaWaHrPoWs\
        bHV0ECNvxjk2bG45sjCUPFtUTI35nbqvrGzV3LbNSwH%2FIsTGfzzbokLZy6ezdZAq5haHv\
        mkWVjTEizb6srptLme9r86GapHm%2FA8cgaH8YU1C&X-Amz-Signature=3e2204ee1b03e\
        b793349846cb5449059056a677348dc3c507166142016d0664c&X-Amz-SignedHeaders\
        =host&x-id=GetObject"
      expiry_time: "2025-02-16T19:28:21.126Z"
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
UPDATE_TIME: "2025-02-16T18:29:46.899Z"
EXPIRY_TIME: "2025-02-16T19:29:39.649Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182939Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=c3006c3587f78c14418ee1cbaa367a50ab89dee8a17b5d2913d07575fd4b1ad2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=234dcd0375e37c1d682d71be1f9b4d2b1554f8c656030cf3b1d85d371b8b55bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=8e6b04b5ec715f05ad850a3c8ea126402011d55a66083b1836e0a6a8732e4403&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=cd85269e819929b1bf997ca7ffc18567a634dead2c7b91e3bc7c0b181a3b4053&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=ecbc0998cded1cd0ad6844988d26d23d92c3045f3e73fe0a22efe8f49c09fbc7&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667LILCSXN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182941Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIDBQdkSI6DpGkKeRSCX%2Fe3oCdWBfoaBvyGcqyENKNv9lAiBVMP60bNk0cctZ8lB8JydzBfH23k%2FP5NRZLuD6iuD1Hir%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIMVg9U0XB%2BGTIWQOqiKtwD7XDgyTLDp%2BzGVOGmFe%2BxhL%2BFLGe7lf%2FjX4hg77X6cE7T1%2BJzYw26Nv9%2F8Aw%2FnaJhvKKhkLHcbE91ewOcUFZV6o%2B%2B09Iz8zjgeKQifIfLYvelOvSMYDPVSCqWPvF%2BB5fP%2Buio08dhOxdymOJp0aqMqchWBInKTNC9y7LXt%2FEQ1HOLZk6Ij61lw5us4sPRgQESMf07%2FrnBB4D1wdgYopwrLdo0WZmFGgGjskWOi5jBQ7PHJOx1TVYkH2dSwoytb9YyApBNy8QYwGEl39NSB%2BYqHm6XNfIf7vgM1uxng3JY7xHtXPYfxp8sYzJVDR%2FULIxUYkWujzpXGVlfhQMpntGJCNj%2FHVaWdFkJuaLoRcDD93y3%2FvRQh4XyLJfKqpGZKf%2BVOZehtqbUA1hBPLUqszLERy%2B%2FjFkHIjT4rhyqzFJ%2FU%2FSuGkWw80NWjX0D2ruB2UcOSz0geADF1prB1OrtcwvN1DmG1l31mLufX3CO%2FAKLX79ADXQSE3AXDM41VtQ3Sua7FSRb380O8HF8jvdJgCBkEZPy2Dc%2Fn8JRdqo%2FhPQnlIs78NxMDyAbgSFY9lUfffF1M6sqzYek18jw6ZQdD3CFscBR5n%2F5gf%2FzNEJXRL1tFfGFnbbNjxwcurgtLkgwisDIvQY6pgFZXqsZoix5ixGY%2BTL2RyqHUsO5TnLRbzBrK%2BqNWpjrEcocG%2BtAUMnI4rXsI8B7nqcL1rwWdiJr1fMc%2F%2Bzc90nC%2BP9SDtrSRldQ8Ic%2BmB%2FCeQq88Fd0cK7FnacYr9EWBYaizEQH5Fce6Kp8wSWVZH42aAX9aZovjRNtUxwQvSbLQLZ2xrD0p7ynlkrM1MkqgVMfLKnEc37m57Xeaqtk3aGNYwVd6Az%2F&X-Amz-Signature=18bffb13a02e921313ee3f7e9af32f6422670440cae385eef170cd170c3a8a8c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662HG4KBG5%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182942Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIBEI9riNekFRJG%2BVzW6jm2XpVag4tKc8axuBRsez2nLQAiA53nGeqI4JQUQLVkpnAdbYyBOxa6Whhq0IiNSa6dA1CCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIMTXri08VZz%2FMUJFcNKtwDyYD8YVRSyvu8AAnKat0HC3dTufkmfoAWZ3VrHCBvEyfyRsngXkcZLqZ6ILRXzMR9JsXZVasHFnsE6wZhccDINf2vnaGd8ZIhfrTnvX%2FiNKvvvgv%2FIJfMUGh%2FKlLlAdzRrKkpIHw%2BdWxUANcK05FVlRLlWIryCXuzhRpbFAN2vEbpRLZEAfEYwg%2Fhmcl%2BcAsV6w6EPif2n%2B0YYtCh3%2BxC%2FN4zvhV%2BvadE%2F6bTwErRH9r6saDJ5l%2FHgWz5M7EInzDEXV5aKnJKUkuIo5QHLY6tRQcboV2HGYEiztlYdQMDkOx0WJj9O9xa0QFAMR4oN8TsYrcbI%2BHT8aagF2XvBkldUu8SPWC%2B4QmX7hxb3d8hq1xr87C49X9IS7rtSaz72YdDKEtGmP4cU7W4nZHStPCsa0qssx1F%2FrZMhE%2FUTOB4QCxV33Cq1%2BBo%2FsCmj7kgIeFI9rcXjbjTYyb%2BKeVhsPJyYuQFiINk8SP13cbHKL%2F0Pu7SM%2Fxl7%2FHQQ8vS8%2BFgg2HJAwNQ8bPn%2F1%2BOl41FXATInedmHB9LEtGzpxROtQpi7vNVHQW7AGdEiL%2BDfBMsF9%2FtY71PA8MLgFoXpzveaexdnL5DSZv3NdDD8joqDRzpqSTqy7J1aRvsoLz8DrMw58DIvQY6pgELa%2BVop21rj605NucDCp7Q0Nmvaa%2FUb6ZEaafAHpJhBB88y3oLPD9Jba8vdZi9xCrfOp0BF6vFqRuW71HNWMXPCGTveNmvwUDVvDxE9DtT8MWsN79dNb%2BhbFVBysPF8ayo4fAY%2BokxG95TR0aIoHaUW2Uwau37wPhFgyNp8fOQCxNTlwuU3yEizVI5B%2BYPI5TlbY%2F407rHR9T12mlghyPzwrtTxB8o&X-Amz-Signature=2c4b16f38210ef7d5aa34a4448fe352876190924405376ffc0a96db173217e48&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=379872f4aa0a5dd303663573cad71f2f2e84119cb324021ee328775fee8f9d03&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=b60af2b149607a9cd01c667d2de5d1ef553a5360831a3163155ecfe549ee6e58&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667GE5WDCA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T182940Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDoaCXVzLXdlc3QtMiJGMEQCIHq8qUP2uILZwY5CfuoqY2IGs1OZZ3w%2FVlSOa%2BwvjrZ3AiA8uLSrzfWSzLLFEvCfXrlpEfPyDRE%2FGdbs0BbN%2FFxFnCr%2FAwhjEAAaDDYzNzQyMzE4MzgwNSIM1fTxCpwAQ3Yq2b%2BSKtwDCqJkF%2BnCI8SY7S0%2B3YgAm7B9CeC3qs35gXfTninaQ75D4QKhbAxbxO1cO%2BvRJP2Af7sXt7jNxEbNxPW007dIowIFpU8qwK2NBzsmFWJxXV%2B5mHkQxVdXgTzlGQvc3hawJz7a9raznHE6W7yDIVOgaWpxU3314hb8i2r7tdKDpc3zzfKTStBjy62gyQc%2Bq1fn3snwkX26qJTxMFgFrDucQb7ne1%2F5pF5d9JSh5u2Lo5G1tEmwD2hNYW%2FBTvkyuiPhsSadljGILn0I64QE6Myk%2Bi3r4gBOiK8bBgxB4VvKggz9DEFElLtAMYRtBAabdxX%2FYCtmPnQZfgR%2BWYPNelXKjE%2FbvmN1QP4xbv6BQADVd8AD5USY0wfsvGNX%2BDSf57olMqGfe0hn3KVr2%2FrHG8ImNhhLQFI32B5qwdGr1ZrcygO2heoNkSmtnhGACGIK96rDGrnlA6Jm%2F3I1WaYjDgIyyF%2B0DUK6s6siPBXYAn6Mxde6cbNWLKdM7se%2BdbUxvpuYA7NwpxhYtlAGuQqjBgvzX5%2BXa6%2BzyeiUHefaaHPytXiLUKaFs7XxM%2F1KRet7wMv%2FqkgTCYWU4sC1YPNQT85DCvF20J4nT4SHjYECQDYrKpy6r2biIv0XxKczV7cwiMDIvQY6pgF33FEdPgazJ9q%2BREMjBEPh6wGMyx3WieVWm65BfsCkvlHXtA%2Fj4c3lfRePvuCT8CYrT%2FDVZaleZd%2BzwS%2B1DaYJVQQInUHtsIpFvDWPLF8SbEiapClcRRh%2FaAi3Ag9U2Jidw1aMmf8i4cW3w4CneBC5UWjvbgvA8JPl1py7uSnOHD2Sv%2Br9brd3DFGqIopa4wjWy1SCYF%2FS1EWY6tWj0k%2ByONxv%2FQc1&X-Amz-Signature=32563a440a94a4c9f41b9dabf7ace7768ec09fe9b7da99688dfcddc82eff4db1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

