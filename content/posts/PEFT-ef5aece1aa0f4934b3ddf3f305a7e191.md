---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665HQKSMJN%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250217T102708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEkaCXVzLXdlc3QtMiJGMEQCIHh%2ByO6ZzBmYo2bqI0gUOULfPr3S5WBthDf%2FTnou9ExTAiB\
  Dijd7msshwBBNs4KDUDIqjNr%2FHoNVf2ihgOy%2BnI9sVir%2FAwhyEAAaDDYzNzQyMzE4MzgwNS\
  IMZLfvoziJBhVt4U0QKtwD%2FuX91GR%2F1n1EKNDvq77H41d7wtrEl4sKQcgodRxvT%2Bme8Vzuw\
  47aE%2B50d5bHHJN%2FpbUIgKkkqFkwXmkveKvly3iTBmHicqMJqDJ3t9WIBSAarnxu5ZToEUtx%2\
  BLJjodoi%2BtAu%2FPn37PmTBAbqfIwIrKyy2VCBx1tvZoQ8uvDY9R%2BPsAk0%2BMDwCsCBUHnyl\
  ddz0gHCCKTryGlyXGa%2B2nwRubB9KzVd7xGesRH8R%2FcBuQLI0DP4DD37KqwU7M2AvSa6rZ4ymz\
  dzmDLLWYsAasfAVtRn2sDP%2Bt3m0AEU9fiqlaVCjhiDjwwz1EOGSMENr4jkKLgKGb5zCWQyDRC4O\
  PluJandTAak7kbuNK4NBgx7RcIACQRISK2W5FIpyyhQysCYKrSW2JiaUCrkfKS0Dy63b5rUDcAdy4\
  8%2BtZasMQ0Y2Z7ZqbEhYRBiDpN%2FyvaszkneFtFnKBiUr24TKo4Xza1l9urhI7wPqivcC0jJFbe\
  r4E2r1%2FB0%2FttEK9b1SzHk8LCo8DsXRVUpW1nCuMTo0UD2CJMd8UBFpjxfy8Kiu9fTE2Z9y8Rf\
  57uzUMCXz9iIqIbNn5MM6rF%2FCPJJJmIY4MNysJE%2B3Et3Z7zWhzF8E8iuDSiV7Aa%2BFM%2B%2\
  FPMI2sGYwqenLvQY6pgGBDUgVbFiRBWDSlfn4SZZeE4OXvzMbvt7RfJrzlGFeDXEVucaFufnCQ8I0\
  9CsunbpxozHyK3sIlS%2FP5CS5insnh9eRGJIG%2F6p4zKf8lilMQe65HK4Dd5I9Dd7MKK%2F3r10\
  WvQ%2F8sYmCrUXKujGUhJ%2FjOVEUiTWNgYmySjNAQq7N7PxD0IlNgJ%2FuANEhlhdje2DMfK65dk\
  FOtI2%2BEnPaGGviFAolZ2yq&X-Amz-Signature=2dc6cc3d0ce43e32ea233daacfc8f9b9b51b\
  4f1b56c779f51a3afc52f03c4fd8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RINSESY2%2F20250217%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250217T102539Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJGMEQCIGGT0iYwOh4rDkigAp96fDdJBI8%2BE\
        6cX7PsD051tq%2FqVAiAxCye37NL2YTm8YH9v%2BdiVJ7u4mmfebIACfy1Ekj7P8ir%2FAw\
        hyEAAaDDYzNzQyMzE4MzgwNSIMfd%2Fn2JqBxloIO2PwKtwDBoylY2%2FzZOdqpyZcjCsqU\
        ESLxASvaJaU23u%2FGPTi2zJbLDlr5qDPPmLioePE1JmIIGj6iFr5WYVd6Py2mAC0Dr0bYh\
        Lcoy34ZUz1C29vbzJStNMSk7L9cy%2FxS0taEXOBiAgoOXmywdnkidSdu%2Bk04aRwpxmL4\
        vOyPaaZB3T%2BiueCPTppZmxFC5BiH2Q8pqEm3rX7JG37s%2F45%2BrNeohBpNGdgUZVr6U\
        Mohpw53rJv0p2VXg1F2fvwY6zLmhoQEpHORqgiwOay0LbedNp2Jiu99yvVZAMPV%2FKU6y6\
        j%2F1AZrkNQPU7h%2FBQSyBxhEMWHa33i4Vw7o47Dcb5yd35HyMegzYvsvQnzw%2BC2Yskw\
        upgHetZL4yvf7cujF66TZfIRihgGvqpJ7yaoWMSpifBs1VvtfrK%2F9Xva06IeJAu3SYA7v\
        jkYlBdoFf4Ls8%2FMWFYp7zqGjU8rOVfqpeFB4v6acxcQ8fWjQTXM8ryLPVH6gkkYDv84B0\
        dty2aj34JWQwWMgwJ0WAvbGFnbvwyIwA334CSnL5pP5K8y7FFvx4sRmXBbxRjdCe8UgMC48\
        ixtKXSLzhp56zKJrKtJreY%2Fg7%2BDaZkWcKj0A2p7R8IxDH7Hx1tuIZMYoPL26sbXzt7p\
        VtIwxOrLvQY6pgHUc09IljdGrECAnD51mXnn10BXI7Sw0gLZTzd8Hx3pYjQgQvTV05W2PkP\
        VK440aNH1eczkrl7EHGvO%2B1qMcprZh2uaWMqtk4oIpuJ%2Bvd3E70kgdnrs6yoPkqXytj\
        dp5dXvA3dhKTxCxbGsIV2x8hq%2BkywpTx2KblQXOMfJeLKQNpW3QX55x5SkrV0cXoFamLP\
        0w4zs6Dvv65EE61jz3Y356dLD2ALS&X-Amz-Signature=20bfe6f99989b979cc503bde2\
        6cb08c7b3ef379a51f69c12f82173d497f14869&X-Amz-SignedHeaders=host&x-id=G\
        etObject"
      expiry_time: "2025-02-17T11:25:39.254Z"
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
UPDATE_TIME: "2025-02-17T10:27:14.988Z"
EXPIRY_TIME: "2025-02-17T11:27:02.755Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=e42e75683f4bcc26c8aa85c6e9ac49aef356683323b58a4fa659803a5434b3a6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=c96375c18def8bb9aa7eac466c64fc4013b6e0e07c7fb443c27857facfbe4dd6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=cff6907776915a560d9e978165066b076051b919477b160748ba3b7991adcbc2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=2edbdc75334ff0c756e60675c50b795c9524866b384b9bc46bb5b5196a90baf9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=4a88328cd53045dc79785739b66c07d0154c8fd01b9309a314ea7ecaa3122e16&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TZ63DLWD%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102704Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQCvetVwWo7u5Q8mbXrd99B0H00ew6Rdn6UNuwxonv6y5gIgNCvh%2FDMs13Z1LK0b7snhxXE20dCgPkD8Ou0ZJ4qcxYcq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDFKFygfqnU2UX3U7YSrcAxqDIMCMslsOwqcr3%2BxzHNMyS%2B8fd8tKzMH1cggDFoAA3ZU7nqXijGNrbXoUQ1K%2BD0AzfISGWzS4EcThoQdEwAYdmrdOKpCD9ocm5fQbuKFRkFuM7ivbchwxDtTdO%2F8eCgQyDuRTruGkHJQp0vCd7tBGG%2Be6y6qbXzrnNDZit4QQAjNSK5kKG2Gj5zK6dlDBLVnQL5xrm6eiiKI1ht%2BdkxQ1OLkr5TEyAvGOPnEYf3XPsqDu3D7nav3pr2Fp%2Fjw5Z%2FXrH7kkPBo%2FxmoBlK46LDelxpQijtjMYaR1syKb2qaptF2PKbzkvrdhXlNoJCKxyDST7muqvTyfd86D7CfLy%2BCOWTKMwpcIusfVY8povN6R%2FxruVXbm%2FxjMxukkv4HXvhUwmBqvQ0NIIqgo7r2Fj5F8L4C6xyt9vIW6jeVma4p8WL1R86R7s0xcSoa7AJRSkEiSVUvx1Qmfljv7SOE0qb9aAo4L9W2LulyEF6UDGv2lO1YuTQaHJU%2FbYDaY51NIKSeOKfgl6TFqBRgaGHzm2o88OWIJg48jC8i2yPOda2L9Of%2FY2PpIHtLTOzXNBrAshwGhd5Z7QCgEgm2ANpUJI3BHtMr5y375mtuuX9yRcjPr4b%2BdNNqLa8m7VnB6MKzpy70GOqUBV7Cc3fI%2BSAVVafr85dLYRvu7CeYF3h5kLKKo6qxxSDLSCpt2x29t95xhdaj91TAlVTK9kdP3j0tsLxUyFXwQGz35BdS8fybPUDjwqWKSQ8qR9bp8HRTTf96evJlrjKIP9yxuWYhUtGdlZsmbKH0a5iPChmQo1Bx6KiAwOH0iYkJcvJRLgmmCbeHv0PHTjXh2QbHVfVgcDObIEvY1sjBWU5PfLdIl&X-Amz-Signature=429709fef523ac3fd68938e686d01f0a75d4b5f3acc8f72e132a55cca9c7e95c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TWQTCMZR%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102705Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJGMEQCIC%2F0R94IZO9Dc%2FK0EbLdA6lANB4XqcKcFinRvXKzWNdJAiAWsC0fG9AVtNh4UHSq1AJFug3BBDdS2GqVjgGweJgPjyr%2FAwhyEAAaDDYzNzQyMzE4MzgwNSIMt4b9j1kF1fOeg4qIKtwDVHzRxnlp%2FzU1%2BFN2vMxHnTfQ5LAcrPaTpiKZny7OyuooYRwbfO7V6oicXgFDpPQFxydswxjKXEWt43qLrt4HqUedZtsQ6xcMJ2%2BV1DfE40kgafINOnN0eDxoIasvhZjMtEqz5eNFaLNs03AOH4i2KOiKpDKu3JOwc4noOyfF3Ccg7dQQlrAl6dGhcq3LMRpM0urBkMPk7Epvm2SRz7JcT0smbfjVb7xTE2ouvn6RghD245nKXAwV0ARbicPrvo7UpZ1OUeQmFO6VHANXS6IkrAsR%2FWq5U03RrucMTjhJjSqkmkx9R5ZJCSMBArQHe%2FoyFWa0EYwXOWw5JZxkZB6ZMHPPxLz8KnhTg687lEWor4LRWp%2BMUjjXYK4J%2B7eUfOrKiHL%2BWgg%2FBu9JGisxsxZOljjvkCSp3wUmauBAYffdeP%2FjAhSIxZTlmP%2BSM9Uqhzh7B2AhCBNxorYj8KW3vUroY4PfpekD9i4ltP3hA%2B1OWHUFleIUC46D6l9MVNmRWBmAp9ETP1vBOkAxCNHUoQN1f8M7Z8AeQ8Oz9u3oH96iZDbhkwh6NFFeTkj3p81wLCnYia8fYZwU3a1onV8tzCwOcoW3jzmEoXcCmvt69oIBgsU0RsPe7sTP0BycWewwsunLvQY6pgEQ7KUUw9WoQceoSkzDrhUo%2FXDtXRUcOWlwTM9cdAU0DQ699DuJOu7q3bZ6KJZhyWFrPTdjGuqGLI%2FTpzKtS1QtQPsiBft6U4p1Q%2Bcd0pN9rKt8%2FE4xlL1YH0uixc1ymoRQjYx71YyLrliYUpsO9J94FyD3H7Ixv9BwWC9OerSIl4smwGnEtCTcGd1QM4ccMR9lsPf01FehWWLid9DMWmy9HFZzr5ku&X-Amz-Signature=4dc4d40bddc7c0203b262fd74414a008bbd17b151b5e6ab95357fe70500bbadb&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=d8a4b35d2cfc2fab9151fc6cc2195f5c0be380e55a7235dc69b6392a6ce20d6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=424459e8950f33118b96dcfe50a0262b69041c1dd0d609fbd8ace2b40a2a2cc9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UCQRINO5%2F20250217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250217T102703Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCICH1d%2BwZJby3EjePFAAnAH%2FQMI17NDArEnXuLYG1KzhrAiEArzQ2iPy8RSpDXwiYcKeSPmS1rnMAOWZJMQV0BieHNCgq%2FwMIchAAGgw2Mzc0MjMxODM4MDUiDCmVzqigKdG9swBGwircA1OmBmPAYBR7jvrTo6CGK0OWQ0rv5UE3Si8gimdG3mvNr4usW3OuHFiELj2spyLaTiVdwjijBY7%2Bxk0hNaAP8kp%2Bd2aknoaXrN5gq7IauVf%2Bll%2FYIyENMzo48cn3rWiaU1nQ0O4zaohlhf2xka0g7siJ8qKiJGmChNC6QcXWSlDvOxSmLlomx283M%2FFlgENlo%2F82xn1dHQx1Toj8miTeuPvxMzNjTkbHzQesd%2FyegVnEky%2B6qUb5UHwZpmCzcCx1yslgJ67ksvIoRp0O3PMfsYXGHEyH6SB8CKty%2BRJ2rK%2BGckKs7P1MgnGh2e%2FkGy6paJsXxzvGM6%2BAOEpxX6W0DFgIpfezaY5g%2BdY5k7zGsm3PtEY%2BM94n%2BzvYhDzzMC3ORxSqp6MeGKloSTvlZqDL%2BK16hr%2F99M8Pwdbrw4Qj%2FgthXNOXh6lauIx2PjkvTfQZJxs7lWZhy%2BOSE58sj2kByfWIcdRVT1NkYJX%2FOQmA8m88GpsO4Pd6TcfuiNsDnLNP4EJ0VC3OWl36uRm%2FZtmXH20LFtMTzwBTmyz0qfm59Bf0ICibKiijZgi73ZwEsacmLUeAC28M7sPzb4KdH6VGpLhng%2BSYPq2BF0s8BSNhizd3B3b3kuiG%2FE6Gg3N8MI3qy70GOqUBRCTob6jYNxpTjPFJPUialuUwVEGJLFv1tNzhDaw5mTykvTQsGFHFYkmfNoqch9rnOs5kiLVRo9REdAmKsKXJKo9zTVxsUJV8VxfAWv6WUu6semheV9eptNk5xvcgWmCIM4z%2FKHnx1XaeVG8ncgsKPMzy1XwMIHoPLgcDGFIDw25gFYMXlm%2BqhYMbLprAqwYZ2Tj2cRfta0Fa9adyq0llr4HZlv%2Bc&X-Amz-Signature=d1fe85f8d76cfef241a2562eba1fd0804e270fc27c17f0cd992e57bf81f73c4d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

