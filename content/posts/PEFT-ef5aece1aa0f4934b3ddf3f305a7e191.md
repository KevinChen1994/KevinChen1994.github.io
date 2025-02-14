---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466WWXV53QA%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250214T172057Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEAUaCXVzLXdlc3QtMiJHMEUCIEl4j9rzS6b5vT8o9Qu4PD1%2FW9krGn3uZmPjNBsWDerrAiEAt\
  bYb%2FBS3NCB9dS2r5P%2B62ddKFClp0gS%2BtHYWeT9M%2FC8q%2FwMILRAAGgw2Mzc0MjMxODM4\
  MDUiDGi%2BdnrgmKPJpnSV5SrcA84dLgjdqTUS%2BPHR14Hipu7qgUR0Em%2F2RjY8G5RE8Grrmnk\
  %2FbWAVoA9oUmJbiQM3tTfKxQIZDwuDnnk9aUAHd5qeyO7vH%2F2%2Be%2FYDhnd2e72%2F9FzpcG\
  UvDyzyudRjcS0mXhfF9sIRdNiLn%2BenAc61ULWcW%2Fuu96rNn86DE2PvhdamHMOgysxqaxkt4lc\
  WN%2FXsi4c3HAMDwow7HE7DbO18UjVMpMW%2FIKej5ouKP9v0V0Se8TZNlf43cDCKJ%2FibIoht22\
  hLwRzI1NZwn5mANwwjmHbvrzAQlXHXb8jVqCrepR2SHAWSR6wATp%2Bfd2CXwFCiTngLwpRP1BsLw\
  Kwu4G%2FeSo8WynpD%2F0NK5ulQ74zwvfeVulv3z7ma0nGB3Z6iPYCktWLcsBDfH5dxJCNpW6lpsU\
  %2Fw8Svz%2Fv5%2FyOX3ku9Bx%2BJlZcO39Xbl2EGaAt5kV%2Bgc%2BJKdYosWOfeQ2sIgMq6DxKf\
  O0X8dEcAOdvaq8Lnyook8mHK8k43nxeK3nawYHlMJt%2FaK75e1S5sd3n3%2BtMy8FgeW6t9oe0DI\
  BCCqTaQAdbVzeVXuhCs7XxdrVbbtO7nAmMcYciPqmVhvZh18QRp%2B%2BFhNYZaGVCEK9JVcIfW62\
  Ac%2Fl5M9gvvDLmAm6WGVMJXqvL0GOqUBhOlnBS6TNc8UOzJJvfzePVNa6ujBJ6D%2BkUK7HM40AP\
  krkWR12my8BPAarSZrOMkrevohI2CkvUvnXnzXd5AHFzgKmBg8BxLdjnfk1hkkvgRUtVQXwKWIq4A\
  tzn48vRLW6WMPqFGiFkI8A5GQlNpxTrzj9ND8tgKz5uhe%2FAeNiuLRd8iZnrTfhGutkdxfXh8O%2\
  B6JN%2FNlB3YIbZarrv38HDfZ%2FsBfO&X-Amz-Signature=9ee40c0c91c0b8328bc807139a84\
  e1c669fc18681b5ae4506ec62c04caa01f53&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YVOV25ZZ%2F20250214%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250214T171907Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIQCaTW1BIrKlhM3jwX9hL7BtaCuotyX\
        eYVlgfJM%2BYozxlwIgO13NZrHuE1iDT9O4MTjXSIiOjZHZPdMEjDI8Bm63%2FlEq%2FwMI\
        LRAAGgw2Mzc0MjMxODM4MDUiDFX10Z4vFzWZkODc8ircA%2FGCOoDiOqgK5%2FWmVlOm4so\
        jA2ttt1CJCGmjh0fLuRYpjqcqV%2FJmH3Sxox22%2B5Kpf92ZFzKsFVaA51eYdOtlVRGvhJ\
        JdTJRYJvtT48%2FvXYACqYljxjfgr1vNqIucx%2FVJXEgp9DLbrT7Xz5m2k3%2BHrXhlLBh\
        27orgsYJvgXDfsEACmsc%2FdUabGBE3nza%2B8H%2B%2F8ZOwBzeiiHnCu%2BpABuRGwZNt\
        VQdE5Tj0eEYF09SiIs65Vh4c5xvvVXmMFhjpoJ43QrKzWHC83r5JlJD8CN%2Fv8O7oILQcp\
        S1GzbDBiasEYLTWVu5r4Tsu5V4AnWP0vRoCnIy%2B31HG%2BN5xZVBZN0dHDmRnv7pQH%2B\
        vagfdunhrfjvsfXckI2ZW3rYWbhfEfl1Krm0rlWV4U4ahjtIgqMua5lW5y7t8HK1Kf6hFb6\
        2RT5b1zXDhu3oh1liWamiGGduwQiTMx4CTIjUv8HL%2B%2BnRYKQSNx4lbV%2BvLPZeVVEU\
        ZtAmSWTe6aqeRfpuss%2BUyhpfkM2tSJUhGQri%2B9bLjAaeriLI4C83rgo44DANt1pLzA3\
        BGB9%2FuWoLhIGaAeKkfLmxo8aizMiO8mw9ENJlaFZdGfTi%2BmTgdbVQ7xuSwuxECw2jlo\
        CmFZEPcHslXQr9IpMM7qvL0GOqUBhfbcoVbH84Hslr%2FIsHe8vitrm0AnAtNvHbeSm9F8O\
        zWMJXwhWeHMvQ68J3MhPXd0jNEwj83lz1dSKSxpX3DLq%2BCFbTSieAx8XPz8PHRf43RI64\
        %2BWciZjW0Z0dOeEcXZp%2FpaXHLW6a7pTCMjruqWIwZO5Gs0lvi5fJREVc47c4j56%2BLQ\
        EKlMAqEUcL46n5CR%2Bf70YSrrubeqzUH4IDDzbUDNsd3DU&X-Amz-Signature=bb89ffb\
        d31261114c1bbd8dac8f3b68d713c874d0ac575d51e17df2c126d3df9&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-14T18:19:07.525Z"
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
UPDATE_TIME: "2025-02-14T17:21:03.619Z"
EXPIRY_TIME: "2025-02-14T18:20:55.134Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=64d2c2a35fc02f091f6a3fd6795cc57001c5d1f8053bc3cc410aa623b824b992&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=cb2765327fb85cd4cca1906ba0a7d2e0f80eb78c5f43d07f216691c4ac9138ad&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=d6f6e886e08510dce513323d13b0d622fdf70547e06d2599f738bf1f841bf8c2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=6c2ce5ee22a2770c662647a057aea3d6f2417b15f1c6fc556dc0c6f493f9d0ad&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=d95e0fe684ba9b121c5b3d2ff80a10ae2f2f4a9a1e043f16860ad4066242919a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W2MAQZPI%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172056Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJGMEQCICqyjBGrIVOP1xFM%2BwtsZHd9egrZy4aF%2BEqM818r7AB0AiA90VMA63aRknv9gkfh5InWfQbmvNG%2BMaiu%2BJZ%2FGttAzCr%2FAwgtEAAaDDYzNzQyMzE4MzgwNSIM1nemSavf8sdzUTrKKtwDGNj%2BxBJHSpZ8kHOD1G4uX%2BZjEkaFioxndfnBWRawNTGdcBRYZaja2JZ78Ho3Kh%2Bao1r%2FeTVic%2FojUrZAEItL0iERDvnJXrz46VG1mEqJhZJMXWJ7UCIBmkaEYb%2FomfWxz4sZIqWtJPbyu0J9YrVWTUbRK03FN57Htbjl%2Bkm8fsP9ssBYqSlS0dC%2BWsSfQQS1udNzSWHudkV0IHQWuMhPBp%2FGKlFHci%2FwVMghv6wnwdcF52RI92owMDZzjjAJ9YKtX2EYdv4lwePFgt%2BRJc%2FJPOXoLYXsXmYyG6cNy8HP8yFOL%2Bv5LO9M09XTNu6Jw9yw1a47Px5vX%2BF5isEXPj55y8IUpsQf0KTNUAe%2FPDpbv0j%2FqvF9C7KOzQA5wTdwy5%2Fmk3A1wzGrpHRxVbrg520wjVjousdWATG4VB6DLUhO8wRMGs1JMxdk5r8HYrTerPcW8Bg27GyE1ygoCuFMaBlzrIHifOrd64cUaYgtn9ssIlZC%2FrO%2F5yXb1ANp0ml3p9R%2BXqctMFADtKORIsQXE%2FqxYtgFMfFfRbRDX8ckUC%2FJ8M9faLJAH9iwyFIIOOGWBp3yr8Dfy6RIMp5%2BrxvyQrSiuX3ADdOUc0Jz%2FJErBD2S6C8kp2oF38tNg%2BKyCVgw%2Buq8vQY6pgHNZniClJyH3UPUEGhNlIPE0XS6PSrswJhiE5uln8OasrHjd%2B6ji69BJY3r88Q97kgR7N1Lbo4VpLa5Rxejq1%2FQdPL75DOKjrSxg6PGhHmCxumkfJe9lpddosBKeLP%2BWeF%2BU2uCm%2FSbDzUcBY6nX%2Bfq9wa41%2BYhht9NLwFKZLX9Ra1l4SOA5nItOsdHISQtBtp0c92O4p138h8RU9WSm9GGlLY%2BP1u0&X-Amz-Signature=7eb38120c9f7b0c94ce005aff379aa97b2c70dcda5fe478186f4dc5cf0aaec1a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667XFBNBTZ%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172057Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJGMEQCICxd8NPoWSzRlo6cFEhuQ8v%2Fr4wxDszRNxxBTY1yipt8AiAi3WAZQ3tKOeUSUv62vcyubl7lb6p0WetkkCMFaIkZnSr%2FAwgtEAAaDDYzNzQyMzE4MzgwNSIMHbx6QPWNTIPOqaoiKtwDZTQ2zl%2FvRCnj%2FLYGGfAGPH8G3%2BKZo09MB0TeLLUtuyVPei4XbKLnH8VWaHKgPQ0ujbJv6uIFsSrsNEr5d6NXs7B4efr8VJyWHRTF0r%2FOwNHTJIAcRU4D%2F2tnAuXtQecHjAvhUb6Cl2K%2BtRaTX21%2Fg4bAkMBeoEkm1YA5%2FN7%2Bg53PaByDz8yceSE1z0XfYXnakfTSErFF1Xb3fY8OupYPGs4fDfEc%2BNTSoJRXsHpWyfuSO8wYcB%2BvF8jjXCItBvTPYsidRV8P%2Fo%2FE7jb7RbF2ugHK%2Ft4y2CQZBN57mOD5n9McBX8v6rd6Y9XvEhbR8gAmVaLcNYl2CXy9t2Gf%2FObnVKabUHVoOenWXQAqRfoVPL856pWLopoPWc2zCb35Vdk63WIOw3m7yaJdAJeoBHOJON%2FkS%2Bl78fXgNKBmkhAmwiWGu8ozaU55BNCfos6JNX5GQBVzfE0a915c2%2FpSZna%2B3L97z7E58vjWbHpw1Sn1m5vFv7lB4xvWZ%2BnmltSBuLEKRgsVL1%2B68fFV8yvFzrsgFzFmztFJRDNJkVQjp%2BLZIyP%2FQrtlpLusg108eV19shTJukUKv0IfqQ42hV8STRZ8H0vE8lrFBf%2BVwX9jqDc7PDn25KcCAvxLeVI8T8cw6Oq8vQY6pgGMjk9MaRPzwdrF8uSJHfkaqW6usR2AEWM4uKB3Da%2Bc59ZlLVdk%2B67WauUqtPg6hBuhOmfZLrK%2BNME%2BGsibeyNR8tYHyA%2FPLO6UI5i2R5P1c5f2gDcgFRJVIY3U3O44fdY1rwrDGObnl5jX%2Bn6TqSzW6%2BojzQ69pq0u7fxOqvu66mAawMtTKwkjSVgkHK0nTv%2B6BxMuIRGUDrqt%2BH0EY1A07jzV1Yqj&X-Amz-Signature=9ffbfbed6ae243accebaf2be31f2d35c24f880e7a148d913120a536df90ede58&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=0beecef77400725e90cb03eb7fba337d9a60361571dc675c306b4f1cb2e866d5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=9b441960f8d5e0efa65f7ba57798544fb45e90e1621570bf9d696ac4c9b87cd6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZQOMCLJ6%2F20250214%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250214T172055Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAUaCXVzLXdlc3QtMiJHMEUCIC01xHjSjV7rypz63IJ3t0SWfsXLpVq55LYRfm7NutGbAiEAhXyRmzsNlFAO1jmMHwn2%2BPlSwIcPX5zaCTYYEkZntYIq%2FwMILRAAGgw2Mzc0MjMxODM4MDUiDG%2BrfeFFlduZpGZhaircA2TzaAPu6WnIoRZiFdPpjXU%2FqYwv19SzEuPYypxLvd8s0FfRmYDHBsDdSc1LfBW9jpCL6t4zcUX90Lpj4aNKC0LEZxkyWg86MAu8l9aOKMGCdvDQJi61StT4AJWfrBKwOYVm%2B%2F3%2F4patP9WTv90lzCHVaD48bM1k5Ekjdo9RtOGYr7ow5u7LLNA8VWfyfRnnyDRfjoFv%2FShGZLyIvGpKCJn%2BReINzk%2FPBfAYbsE8XjHCVAB%2FlS91lxJcU9KRQCYBOkyTRg50NH8ezYwlZvRUJc6i3fSx04BckFLE9rL6QnwTK8uhHbeVqETYg8fOIpMeXbAtNTJOsg2lramjAkI7v7LPYKKLgeYE715xqOODXzlXIy62DBSeVyKJxtRv%2BZuKwasuwAEs0NlpJdMJlGml8jDYrwpJQEAdTsvgrIK5jTI4mTnUNtSScm55i05RGo0z1Nh7cRpIMGgYOB7DmrlhtBlisu65dNZGXrElfIeAE5g53E0hxEKrMd82D8hedRfMBa8InXGUOWslQD3K%2BjVHQOl%2FRbB9%2Br9Kb5dKjbYWRuJL6nKiWa%2Fl4ZsMXJKSs8F4UOaASn5OrXBZ8%2FVzGRKoOufUneOgr7WxDfBJQkbh4FitSDuy4uJW5PplCwZxMPTqvL0GOqUBjcKCWkJVWsWHT%2FNB7jb2pFFmwwj37waqG11pStWxXrEaugmww1mvEQgDdMB2LoAgU6o46w1IDGacOvdxdit2z9jIXFgavzUFoAPzlkZwAMDK%2BFqX84eC6AWH%2BLl2LG16SlmWmT%2BHISYwmXKOsjLIQZhC5nm4Xj2Id47gH52RcVmm9XBP0y%2Fb4ExnDUvJnvL7qMc1C8uMgJiy49uyRpUrq%2FLFwlvp&X-Amz-Signature=a664d1c4009fa4c090d188b0a9596c8e3de4af04adbd7176b2a53e2c1cf3fa6c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

