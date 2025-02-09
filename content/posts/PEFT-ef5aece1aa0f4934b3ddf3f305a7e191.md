---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466665GYXMU%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T092139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIA1a3XZBQW%2Bysbvuf\
  %2F8BhxdSMHM%2B4W94jwOPfcrGYg5eAiA9xz%2F5EH%2FLHzyNGJGBqLCP%2FQJOUx30HQ70mHAB\
  3m414iqIBAii%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMq%2BeedKd\
  YRePj0PEJKtwDIxOOV7FsCYaGmB1NDUkjT18fzDbe482Qnwg1WC3E3lbK6tHPVUN8vm25Zz0uJ%2F\
  qXbTWxRpBfYypmUrIGr7SNyCTPFemlCwIJ6Uw7WBvmzQPppursLHx24RWj3AEoTLZ4SzltdoUAQfF\
  l9txqoY8jepqmZMIq9B8U3Ss5iu07gNp5EbzHZW%2FucX%2F%2FNf5kCu1Bys9Ng6NInqJKY7RlOP\
  5OQnhB0L3ivb2E9Z8JdrvYJx6aLfgSIbWyBCIWOoqtedGQq%2BdKgjIa686WM3NhPvHXF6jl62nlz\
  glLlTBNYcnEVicyTBWYp9mAWZIBElgq7Yo%2B8QPr514fQd8MrXtdZuVrJVD2O8ckiye4Z2ERkQ7N\
  AYmI5hbQi0%2BhDEAMWaPMWRDX6Oz1G6%2BpzMQOVcMWFo4eHrc%2FoxBz%2FXlzzrSeF8HxcvQvM\
  wheJp7yFJ5EExNrjf72UEbuHr%2BuabuyQmXw0fA6mVu4kzIa3O30D7N8THsdaez%2F7wcI6cFHU9\
  QXeJvMClRpWcXlXwZvH6hV63qZ5qin7aRhtLUf5dx0JplI%2FJweYIqzxFCJdPhufr%2FqArM0lLQ\
  %2FYBNVYERoza6aIYzZq7RifQ67kgrUSo5EiNn9TGXUo4M7%2FPlJOgT5iKppCMcw0OOhvQY6pgH3\
  NyE4xZKP8UvPkZPLFJDdGTtRXxDzrR%2BODVONwb%2FVldBv2OpD3RfcevgX1%2FRA%2F%2BBkNqq\
  lLbt2pzBwYYq7iLy1vy0MMY2sphrJobOW31T5xebagYbdifxjHivqAjaQCQ88jXhfEfHot3SJiKv6\
  dvfvC%2FE3z5Cq%2BysZY%2F4nqlkCiVjzZUIglNRsrX9wKLvHekek6rCiumVETUSir4Z4jCtmloE\
  Uuvad&X-Amz-Signature=6cca957621b318ac06dcc4d3c5d7ba8125f2e9575819179dd34e3e6\
  9a3b2eab5&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665X4IGU7H%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T092010Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIGClLsBoUWdTf%2BVSuhD9YaWNteY%2F7WrVSYkOdRaawfAGAiEA01wpf9IUGZaD1ReY7g\
        D0Epih0e0aG5aixz7K2zuZBrQqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDA%2FSkvdD1bI%2FY2i5aSrcAx4USLqRT3yKfqWiR%2FiDBQAlmT18BP\
        xheKR4Fu3pJpJEv8jMpr8hpx1wXvOIq63zQcXOsRl93G%2B%2BOCqURUx5qVHgeeDvMknX4\
        NBDHheE2AH%2FHptxucQ0G1TG%2F4M0exMYnm9LE4RIY2bFgoravaGgfQza0K5eLKGajWVt\
        W3%2B99ZV9Yvip9A2Wkzut%2BGjdymWQiAY%2Fd0DQlz4lSt4yO%2FH5mZIHXDaimnTZIx%\
        2Bt2iFsvRQuppzGr0oi9SHOT9Xwh0npspo59dPToW7zMJlinOoCB0ahVIm%2FDkr0pT%2Fb\
        j%2FaB%2Bl%2FnniVe5QFSCNas6SPbY94dlXu7dhwO%2BKXUugEup6EnBDz3Jt2By8BGkNS\
        ZBlLGLQHAqSvQZWiEM5SgWATLNHwplvapE1GkcVjxPX7P0BhOQo%2B%2Fc9qTInpsSZ%2BW\
        VoDXRtreaFRP%2FLHgIy9gPACeK6Ik%2B7nw3lV9%2B9tX%2FXfUGXFZe35s4wfK%2FdOJA\
        yhWZgksfLpodtgOGOV4jL%2BiECH1qnBOPjI%2BaV1X15zKI7AY0t9g%2FMOXut9RGlrcnD\
        jnNjgzhUcOwCLrf3H6y%2BrEkQPFRSxULWoL996izZiHcUWRp5xnvWebI82vtdmAPqqiSrn\
        EaBSCO1HpZhSn9gv%2BbdUlMPXjob0GOqUBxlJxohZkv4Z6JkAv2iM1CJpFIpUntNCwH38K\
        9Kfw5H%2Fr1GaFHVSMBWSIszVLBRdr0vBdJehYG6II3x%2Bn3F9fnAh%2FBcifzOWmzyqTb\
        tfTX8qVkpCpweoBtjqoUPVVe4OZIJkjOgsKo63WswsDGRNQWZerx6PqnGP4%2FT7UCpHgz5\
        51CcapIPNO7lM7VHdPMrBugEhng%2BlibM6AUkshvZTehijCDC2B&X-Amz-Signature=b2\
        ba110f9c25a0d04d5052abd90fdd83f5909713e6b373d9265976fbe99d6a66&X-Amz-Si\
        gnedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-09T10:20:10.867Z"
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
UPDATE_TIME: "2025-02-09T09:21:44.724Z"
EXPIRY_TIME: "2025-02-09T10:21:37.734Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=9eb0f7fec79d096a7e5b24c51d3179e1d2bbad85178f8f17276295f04a432c82&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=a440eacc771ffd9df77034d28fb1b22ee8ce10d0d268f4ccb0c781f3891f1acc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=cccc7080b5d0ac519b945fac846f3c31da10682ff24a66230748dd8a9fc1a52a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=4ad14fc2d08f48553459df161f4ba6f06f9470bd25b92bcfdb40512160d19393&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=7660527a2411e99e5e003045fc80a0933f1b42f6ffd9950ff9e99f90d1428a68&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667X5ICTR7%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjVXS6svcc2tH8LA260y6Z02pCc%2FNL2vU7nylmqi7NKQIgHH4wlsZrQj%2BF10f%2BQPBE2hTLw9NENAj5jqFyAuJtju4qiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGlEmZqPZWTCNb8FmircA69nUW0N3mMM8n1p31j7NJXL1N8Th%2BmcZdbkETVd9mLizd1BDKZgSNpdgB0zIAOuSqm4Cr%2Buw7hNoOBw%2BFfXJNudi40VFS106eSlRuboBsCx57D7uh9TYMLIcMHcPyoEvuBzGADHY4RWosvmaRPPkTRwooMIQB94Gaok1m8wjOetVTRkNzBjxbIROe4jiv3WCx41PTE3J8vS3aaxVnkUZtOq%2F8IaLCu1fu0%2BnoKctkotKOuyWCO6r5MzwlKMj1WtylB%2B7tnibOtbABLVV1uVis4xXVL8XagaXLYVJvRQ%2BbDgObmWAWuznfK0a587IZI8JlB6Hi6kvNPLZYHJbf1TD2HCQlIF4cQV3cFm0BfW8rH2u4uCQb%2Fh9aID238Oci5tq5fkDLq8LdxBx24sHk6INx5kqfkIv%2FVjLablJSa8CzjDS7MjFVQjnwufVfIq0ptn4jpc9sdAz0Op0Zx6K7Ortsb3O64gN39LQzQxLToilHd63b%2FEFHzuJ6UYWdwNtVXGFgT5fJ8cUzIlfLoACbYHEzwDVJ4PyIEiIWjtXv9NswOQFANI4SnK%2BKZD3snzHlGb5apnh8ZWWXxvVLgbUE00kf8pyI%2FJasTgS6rztdZgV0dtv5oa%2FKsoOHyjyp%2BvMOHjob0GOqUB6K2TkgDbWqdhS%2FbfUgIdnZCIrMvlVzAxfKTF7HWkbCqQNlE3%2Bh%2FnDS5%2BhhiY3dkgesvvefkwl3R8KQG6nGjRf3yhYQcNpmTH9mOvGo6tapWJvvhZQEKyKcD2JAALkG%2BPXyKJBSI2IzbvDBr6xLcHXaFuFNhEzbhsgJ9aZn5pTYLVoqIeZOGaEOmq0XtFndsuwiPv4KPnZfs4sB19ekCSYJcFwudE&X-Amz-Signature=fdc7343caec775183b27d8687786fc8be190d02a644b8387d80801895116f60d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WNNKKKLY%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092139Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIE5zp8s89dstEWgvlNlacRhePXSlcYhGg%2FLPF93l6clgAiEA9f2FyuwrEPgmK%2FNxazRXqnDcrKmwEhptjjyAaxNzW0wqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNyIlosNbu6xm2fS2yrcA784%2BCYf%2Fvjo%2FmqirQHbWN3bnP2GTU9cyvL7LDO%2BMh67OhOnzeDpBJZSLy9NwStBTVlNjr%2FnG7rgfqRIXSqm9zJIXyWyGWFAXKTb3mZU0gg0cgPuuJo9mf9KHJKwtmqbPdRv7dETzxwhkH3oWY%2Fk73qogx3jNCef6vXECcQheYt4PToXIVma%2Fd8xn8KTFPpaBr4SVjFNkxVpift%2F7W6lhs6flZJjsEir%2Fz3C%2Fsg5s3OyIJaYlvAANhkGtSrzZt0pw0u%2BzyAU71hMCE4UQFz4VyOvImy2yyXpSqTKcQb0rsldjwMmYDdDkcoczobSV0t0Ra%2FtnXT%2BilElmYQ9vn0EcN3DnOnC9oSJXLSic%2FpimL4I4NgbRinzpNlkPXPUmlM%2FW9kQ%2FOBRHazLoO8%2BCp%2By8cdJ1vTzpOK0AWQ5dSRUqIOKJc6Obyv%2BkrTOcFJJUhYaCnWwpPIFW7NqYH6T8ImHfdKCbolzdAo552tVssAAaV9fuuAoLG0RMG0c%2BLRYkDxLPqoLPQJFdmiALRTKEOPf2ljD8A13VEjEsAppV4Dca%2FoNr56k91APJh3cTsgCCsPjL6GZj8xAA5YeRpZYgoanKg2PC8B50b3jZo4S%2BPpOkVqwr4ipMrJtRW1DBB0dMIDkob0GOqUB2LrJd9zLYLTFAXfzuW3bQkfHxEhQFYBPMfWh67U0zA6hl7FUeWwQFGAG6sG%2BEiv1Q3nxR%2FRidqlzjWwR6WAaW0v7Ya9wrWh6u4SN6WLHtyLcycO3mRBDDDt6yFr6j97yL20w%2FZXo1fewtWrZ3dLoUqBVKQABZtaU29kwfUY52L3XwuT6mfcPEgM3236gONACL2vBcUsbn4fDT1p8%2FcpHQRYnv46E&X-Amz-Signature=e54bf594269dfd68d0e698ce39b44713a66004d4d437c0a0cc022cf105c5d81f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=9d5ab733bb1735be4b4dc5edc28ea88ec90851bbfd01cd354e6cc3efede7c20b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=bab22748ee749b5463eb2bc421af50d307f0d207659b4d51f9cf817665226f3f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z6BUTRNO%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T092138Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC5kHJ4x%2F3hZu416RJONrrGn34xaH5WqQ0ezw5y5G6fpQIgeJkDvjszanFYKIOSe3y%2Bx12oitLSZFGYT833v5QyfPEqiAQIov%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDng2XxstzCqDzyM3CrcAyTzev%2FGP%2BHLnaxTRH%2FMeiczbsDXFB9rpYL7JZX9vNt%2BGNlZtewyPqKkLxjb3UqG8G%2BOMIDgfR3QZMpOsSqVkUP%2FVnbWSvKsBOOr4ao0%2BO00W8tTERhMlmEV%2B1yC4%2FI7a9LBpCwNT0JOWShVXNDCYRm5Y6kewA2TMVKgcRFHbl5rHiA%2Fa4rxDqdngGQS%2FBzoRr7iyMBcHcGfM24v%2BhU1aZfcyly9ZnIzZWRfnlCq2ftVOgpT7kuMVAvb4W9tSubOTrGcjkXH0fjpdaX2%2B%2F260HFGagv8aPvhPbTuOprec1kwPtyl%2BisdPfE7Yqz3B7b9C19b6Cdzit8JYxokf5uwq0ckBsNt7i5WOFdWoGGPoCj7MnO8wCOs383kHNZ0obJjCzYLOrigayUB1qudAwkZnJQsHyngC%2BTgRT1S%2BDpZmOcqP4oSAFaad5dzTt4PxaQ6leob7B19Gpi1ijlG6J4aoIW8Jv05ohYUfbGjBnT%2Fjb5CgJ3OM31yNmB0ofNDGlcV%2B41VD2cjdLANeiElqR6IN%2BRiypLfDjVfivnaS3fenfsLcPsi%2FuoB890dwsWYjOIH0TEzl%2BU%2BIRuei8%2BaaDIls%2F1056RLbHB8Hw9VZION4CuVl4rRVddftYrt0G16MNrjob0GOqUBxb5hucn5%2FexAH3hYqvScf2PVO9UYhPs2QLLTqrUdfgERQANR30fJBY6sxM4RYS6hJXT9MMgGXcCCNOeGy0IkH0rWuHfyVxQUZHHsxvWl%2BgtuOBgzQCa6ualSIDut3AxW9TJJcemuoPvCVxHPDreWnXftlC4wKaIkTbVql09B50GIDA7ke%2FMzo5KDdltLreCHliq%2BPmKeClh8UnPXXjQ3JtdniWAX&X-Amz-Signature=fb4cf4ec5d7aec76ccacba118642129e3924a68a3fad7ae8cd92098a6a16eb13&X-Amz-SignedHeaders=host&x-id=GetObject)


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

