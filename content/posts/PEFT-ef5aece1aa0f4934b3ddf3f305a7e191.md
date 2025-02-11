---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664GX3D3KB%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T025325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDMadhKtRpmMy3KJvBd\
  rureR0VmD8zsADux%2FxPO2dvdCAiBmL1ehBcUR0xRcwbvVw%2FOx0tDgq5aLuBbS3%2FLxrZBYQC\
  qIBAjL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMRRL68IBYFn1kbdg\
  eKtwDXXTqUcMtOe%2BawFmxam17dAyx%2Bw5MAyw4VO8zwIWNZyUBka5%2Bo9juHF0eZOCmKaHB7z\
  AaIdxq5rf8AayxMWRy5XdsOrkIr25hL72CTzwt1QrRCgOxfG52K5277yfUyPGF3eWkr4O6j2VbnFJ\
  p6pknueEuflomxw1AouQj1UKb%2FQ3%2BXx1zucKppSe2fVR3rfNw1z2WE%2BJpuswlYb5xA1lKfZ\
  yg3LGsLFiddlEIwK2GtRXI4Ok4eu%2BAB6qqz5aj8%2B0QVkXEkrFhj7wYwx%2BSefXE3O4pUFrEd\
  oIx%2B0v%2FzoVFHJXi6sQvFf%2B%2FItRlQCPA5mM0p0rHK4rIYIhQvmlGEiZlZkoebVrgyWGdNh\
  ametuRF9mmbHqUsXr2REYkYaNS6kxsCovtLOBAhyk2U1d43pmmL9niaf9AY%2BaI3lBBnSrq1Nap0\
  lg0Ypb%2FpH3J7EqYMZRj943Fp3hChwryLzagoJ4O86sYGGCKd3MmxrFKG6%2FgTZWgf%2BrB5fdm\
  CKQffljJfhGf8Vh%2FCfxM0nlr%2BhuPOS3m360Z8uKAPhdBoQyqWFI7X3i5VkFyL5eW0LxijmKs8\
  vYuAursho33Ehc8yWmCKCWTvkZo91pF4Av9KLtshiaPjV5bCjNFuhGy8w35a0Mw%2FtuqvQY6pgFS\
  sWHp4QXK5zIl5MDMxwHDKu9Yw6pVWKNiJsZDG8SFRVyEwXHBWrX2bxptnRGNt95f6r52ixCcBURQl\
  mY8crzjNeY%2F5tmhaOSYUvypXtoilZ6iEGdKVmwfwiNZoCCL95FD7pVFehlS200udvQdDRw4DbH8\
  qMD8XfE90OzST%2FTctEvgWpvaPPLMYh%2FcHVzaDb0XifBwPFFFUQlTFwCS57pxUJTL01RH&X-Am\
  z-Signature=bc30c75927614354d893b77e55406033ded1410fb99bfe3c8c87a729ee80e926&\
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
        redential=ASIAZI2LB46627AQOLVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T025159Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CID6RM22MXGLE1VZhamfQCddQKWONnxxrJFiOs7c3u3peAiEA9kScea3KsbPJ8hitivrr9K\
        s1a1amlfthh1KPWcbrhKIqiAQIy%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDHsH1MycJeMz9WSRuircA4LPYXU9y%2FF5DkwDa71tB%2FyzpGFh1tZCDk\
        pVjEMFJyraUNPGPjLj0mER%2BeC%2Bs5azq1hHJgFJdMKTk8w9F%2Bbf1HYZb7mRJeyLL5m\
        HhcpE0WlUn5fny0tUWTHqVk0kzZnV3xn9AFupU4qegc6yEJg7LsieK%2Bb175opPn%2F38O\
        oI79ieF%2FF709mUsrVLo7R33aU5Vwtctr917iGUOBd4awwiHoLh5QUmL%2FP2FhP4k4UX3\
        %2FL7xtcuuc2G0et45OONwrLUfX4Hq1MBOGRFh9rHyx2e2tx3jZiRlA0BbuvjgOgZX19Hpo\
        sZsw8sFHIW8UcljNhU89M6ao1HVMQicGZl3XslxxYr2cBk7mpa60xMfLcHNbkMaiAIdfS1h\
        Nm7PuaUreM8XPG8XCwcWdODJQLcpmhhkI4%2FKXkcRnmOHrLFnO3aM1RJ8YTw5XDnoscr%2\
        BBA2V1nd7v8Nqmewd8QA6gbTfoYvDWXiW36elaEO5DdkxZgjZYLxgI8L%2FpwD8I%2Bldvs\
        7PL8pMoFsiJmQ45FLyf3Zi%2FHwtDCAPx6Ruj5j6HUYQ%2BurNmsLpZsYkSrJINDvrIucL2\
        MMll88mCGS17ultOvmVaR3c%2F0vXkv3jGid9PACUFEsgKWRSqIi%2BLOVHew1E1PAMJXdq\
        r0GOqUBd96eDvsBpqTgqd5QglQNUKT%2FSNt8hjfcsL0i32prj%2FtLNjLKuUY0pP7%2FFJ\
        ngfcYKu89Deaf2AgNR1Hw%2BOaVj3IckHYZmif%2BJdQsg39nxkllLINYLk6TviLzT22cfM\
        Vbfl%2BHEZG%2FGqQWbsLczp%2FvVqL%2BL1W%2FUat%2BVuOob33cVsod2BlTmw4RxCBor\
        Xb69Pjy653iAZPsG9w67Jn%2FN6iZLL%2B0X9Inf&X-Amz-Signature=1c88851c45573a\
        86e5b6a31511cd487fc062fa6ffddc6926760e56e9e08357a1&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-11T03:51:59.861Z"
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
UPDATE_TIME: "2025-02-11T02:53:32.258Z"
EXPIRY_TIME: "2025-02-11T03:53:22.542Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=633e543f1d75a0f5f45af392a849546ad6f6d188c93bd4ec57e6dc5ed99b970e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=d96b20a33302d745d5a6cca2d372e0d3c4312e17989cd180c3ec6f9086dec0d3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=c1674413319fa13d2478caf8b1d93b75092bd5dd4b9e3650b0d24891ef8d9034&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=5356c6e9d7cf3059b3dfe9d420748215f33411eb9b86d2499fe1bf9085040f6f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=b49c1e0121d8c4ed81d43df03a48a4e8f2dcf393b34432df5ff9fa3cfc3ff200&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666DANZFUX%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025324Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEwTST0tyCFzq3u7LJqidBXxN50EdHixTMBtrH05c%2B6cAiBHyiyWwfoewJ5eB8%2FOhO5XvmVDFJ6MZ840n1v3vW3A4SqIBAjL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMVR79Wx%2F9bJjHTOSCKtwDXCdnTuM%2FNl2p3cRZ0Gn7yIxI6eq5F%2F%2FD4U%2F76BeGVaNyIP8B5fJ7rmx%2BoZPO5fhckCr%2BeW3ubU5EspxB7NeY%2BSX4yttrOUMiOXom80841jAf8SweZFW%2FMy5QlHnaq7eO9Wd8ox%2FDadj7JuCZfNSxCrlZbEACCiC8ZhvjAOVb3SgphoAsG3OlPYxB6Blmq2smagUH%2BOUa%2Ffmn8G%2Bf1eZOiwec16JCkSSzjsaZ3KCxdSMA8it%2BBOC0uo4i2sivPcTZhrDO7o59y9xkqqqRvcBBizmlI6wqNALW36xmlBdIcOatMFm53%2B%2BZasG%2FjVy91n9ki8thbEc3TvP0D9leDKNr9aX2iCxmFUPry3%2BsRcAl8KvSeDffNV7Fb7XIvk586%2FfszlvAK6ua2X%2B1FWel9f0vGabah%2FAt2FO%2FRQigQkht%2BU3GedRtXAhOn7fTugk0sXVpeR7gSE84PKIKaj7%2F0yMH3Xm2MwY0uDdJBjp0nO9rRn%2FIR2d50xV37acBM0R%2F1QvCsAs%2F%2FYGlegQyQn3ouWS%2FGBHgnnNCGSalOUB7mvfLkUorkORD7bq2JSe%2FERNfM8TRo7omfcVdIHKWKbIg0omenoR7O15WkjjOJT2iMO06bpedGJEodYtuFiaSMckwlN2qvQY6pgFXtvp%2BxaxMvKVDi4e2RAtNaTcvsjTLg87KTD9n5uKvhHb2KtGbgqFyRYDhWIpBLYfmBMwlxzpAXS8KdVyZSfvo0Ex1VvV9525vNeKxBluaQ3yR9uepb5HuVSUML73Vg1AoAi4%2BSHWLRU9wDG5mB8MdCgmc2ivcIDLvARGWBpAgThm8PiY7swnvoxihy5AB2b5iv7hgJBAbPt6OOJAnNtmt5ZX6vck5&X-Amz-Signature=456730bc3aa0291afc0c42db8fd9343925c572d3c84ab4d57840174c40589249&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TRKLMO5D%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAGxL8Qh129nyHCYAHkH6x02UdddS2s8%2FgMJ0DN61QUGAiB3FnOjf%2B9Cz9KzSQLJWBFYXBjukEGC48D5VlZe879CkiqIBAjM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMVIKtg38I56I1dNt8KtwDEPF8epx1aKIyl6tqXS2jv2D3Vw3YATYhCRqdC0k8skQRy%2BEBFaD2ahjhRJMrpKMkKvlcOwVwdDK65O33vg0NAJwpxIy1irjnDa5Z87gDbw%2FyMdo6SxB%2FEPNhnvJSJuekjTtA3KlWdH6ram7C69DZZcsq1CC40%2BuhCMoSGY6NquhVHuqpaFB14rfpvUtWErgosePdiVi7yN4X0qh3PybAOxws8ztJGfl1LK0aHcyei%2BIbyPRexFyGgTrMHFbh6gF8gK2pGl%2ByeJcl5YiF97oyLjuosFsO8dJxnLjQaLNOV1LfoIz2fKgGycNFpikw3h7QnPzAYbUy6rdRLqCp8STLbFcG9M2i12maShuj%2FUJ3kNRgy4yeghmV%2FWtCzc3tlMiOmaSciGmDkzApf83wOjcyhsU1GN3kHMW7OEhmbwByWWMj%2F90qpOVt%2FLTdzq0ISrM9BxR9km%2B8iZTJrnWn1dQGwVzgAtAA8CvziaGOMSvjGN3TuRCPG7Rz44Q54F7RHSbumZDFdynpYmGLDj32WRDAGeQ5tJUttFSnqZpL3rKKrWccE0LY%2FERGNWMiELEgQcygPYrent3Ze0D40nHitx9c5GZPb1Bz0NkSM%2FcG6XtuGLDhvN7rcVxbevZSXZMw3%2FaqvQY6pgGv%2FzJuZR%2B%2BEel7qGiZ%2FR46znGIHi2pdDuEJEZ91Jplic4BGpg9hh%2FEhrwKUM0F8O4OOqQbaFYzVkCK4ZWgF84GDQbN0wx8qDqoC%2BuVFDyXB%2BJje6kJsOP5QJ0WkGAdJDChAbA%2BxoQn91i4MDENGBwsMtOjPYLLV3tSE3VzcMO98lHG%2Fx86k7TvOieGNsIuaTqTwvq27dKost61XTlQz0WXkDkdUB%2Fd&X-Amz-Signature=74e67fc375a0fff41592240326ace34dce26356898ee2384da1ea043453b3605&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=e3ed745afc04b10853b94be4f3ec1a6313337c4e1e02451ccc5ae0a0fc9f8634&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=e3d546e16e5daec86469bf086e04e57192159ccf5b2a372b52521fecf67c456f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QV5EKTVN%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T025323Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDr4BFwUrwItNSNLfZA1Cwf6g4l5KhvAI9r5yrbs0P3%2BwIgH8tm2UBlsdk2ilm7rLWQVcmRLM18ZZAO0oiA4LXEnnwqiAQIzP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZqBqnOtJwhh1robyrcAwdNZ4vWQ4UEUiCm4vf31Sjw%2BpMHvtlJNrW4lU4ZMG%2B1qohZ8VQFq5wpZq7b%2FD8mgI%2BUM0c%2Flu4hDFzFO2oy08YmnmAVSuI0bM09wARRRqygXV33HrnTwEAr79AcIfpgMNHWdXIuYPMA%2Btgi6J4ZA7n0%2BzPMrE1QHnolnYLhcxwIKgMDl2eXt897%2BV4p7esZhhD2RRXDPPhOFMo9DqYGdzC1ujWAFKGKbsbycpJ2X0QGdgzp8nkHa8A9WoVwo79i4aKrOFMlShFzhK%2BSNL9l%2FD0uPsqo1o80ktSk3a5my0lZjTdkiX22DbDI%2BJTEGcIwbNccbGrRu1KIZbpjcjUUFcpU7qUUEpjvJK%2Byga6u2ARoHllzA1oABBkVWcbee20r7CtGXQJXRl4fBgS4QsYITTYHJmDry4aap%2FWd%2FLGSZZxpP77Y9TWJXHBYopksgmZOHhVdo52tmFB4sxwEyLH0tPR3BoY362So6j%2BEI%2FcaE9OsaYc712oMgD2kmjfKW8fhU7T8k5Cztdm1wWU49gk2tggfQpt2F05AFLvc2SafB4WBtSHEeaaXNcGEXJ3wV0%2BbqmR1H6dM5CGxZKyZlN%2FrJ9E4m8Ur3PtjOYJSXYD%2FQlJoF8%2BsdQKxGpKNKcyoMOL2qr0GOqUBplOX%2F2VzDPDWp0%2FNJHIPBMy8ukA1%2FX7OmPvwSi62qQ1yRE7kTbA27Skh%2Fg8l%2BKHs5XrdYzUucBvtvCQsLk4L9sguW1d8BOOfBDvLvGSbdz0IBjAgi4pI%2B8pvfdIUsANeazJBgyaZRKw85ZwbsLh2l5GyhQP%2BqsuTE4VxZxwwdxHgLiwSrva35qffElg3QUyQA3HeztXrWXx6omMR3KOXqtj%2FMmY0&X-Amz-Signature=c15b3c3a4759ecdc471fea635e822034f4b61afa9b92a43b1dbd3fafb40460fd&X-Amz-SignedHeaders=host&x-id=GetObject)


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

