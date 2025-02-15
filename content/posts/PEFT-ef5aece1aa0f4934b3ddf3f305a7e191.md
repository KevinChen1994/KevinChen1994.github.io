---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q74QNPXI%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T162639Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEB8aCXVzLXdlc3QtMiJHMEUCIQCGVuas7JEd%2B%2Bo2GN4xJUSMdta1ZgI9di9XeMfZP1tsmgI\
  gH2t5DuePKOMzR%2BHCfuLxDabCpbBfi5%2BO5HKIqvtpOtkq%2FwMIRxAAGgw2Mzc0MjMxODM4MD\
  UiDAVPjxrUNpTeevaoIircA7ZQmo7rfQz%2BNBZy7S4iGpQbo1%2B27GWdPkAvNxLk%2BjEioxTqo\
  6gDCWvGWT35jqQG3qwblgZAW0ECA4PnQisxnO3jbXcVS53Gp1rxNzWedDlt%2BbV1jU8J%2FmTbER\
  E5Lmsq0iDu4Axzd9Fvm3ac8wcjj2BNqX%2FtfyBy4ke9%2BfaD80jQImJdUeIQlY%2BObZZJFmgzG\
  6ey4YxVcqZqMlYIjcAUijYUmpmV8JYg9BcnPRXPA0Yi4RvFq7mIMKtK0acEKt52LGMK2%2BPQvm72\
  Obivxy7nkD4eHngUFYzX7SrgzQzIlVncKRlMvR7rpuPna7TCRtB%2FylV8rUINQ5xw6rmejlpJVuR\
  kG78XsuVrmbWmNMUeb3V6lWCeA4M6%2B6xTbHdUaLwdq9%2BKhSZGj8aQ%2B88IU5g3CtVS26t9JQ\
  W4GAkBYRW2gsbjYSe0nYxN5nNLh%2FA0AjUi99utL4g4bbZUkhGAjwy6euM0QbSUMZ5gLb298TVOi\
  z%2FTIdeQZeJBOv29lE2E3kv%2Fb3NWhGXNOIBD7ejpmyMaVs8Q4d7tFowvSj%2FrNGudGTAi1Y1F\
  M1ezUL7KXRSmru5CgcCPj%2BPaAj40wtiLiAyE1N8D2%2BUp5LBQk2bZjvcPPKjhrLIF%2BX%2BSz\
  %2FJxJ2QVMO%2FFwr0GOqUBtPPC2A6PUWtnSE3o3MycrFhJZ1Q8Ir1sbqOzxHpD1txtyJ6iREC%2F\
  5Ogm3FLtQ9QPZ8epA04QqYpeQQI%2BAFhEzgUbJrG5PYMPO8Q%2F091Bpx4ypuByqGaMwWEOl3a6p\
  AIgLgZ%2BOQOsxhV0ELJg9LYIxP48zgZDA4cmaoo2Dzm5rS2TOyow3SYIFk2NdU%2FzsIdM%2BCHs\
  FBhC9Y6LgGL4R2ghvU9DL2ka&X-Amz-Signature=e7fe6378e9c915a9d52b47882e5da89df2d3\
  14bfc12040b7d40f4f8c234ec456&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WDYLGOA4%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T162518Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQDH0SkJqd%2BO317kV4jHY5%2BUJvs\
        SOkVY0McjOrQsBbr11QIgOiBeyGhyrKIBELREyS3i9pqO14m2pUboRyYxHDP5Zjwq%2FwMI\
        RxAAGgw2Mzc0MjMxODM4MDUiDHh8Xbm6Pi%2F0N%2BUSoyrcAzOmitQ%2BuWrRmJM8s76MM\
        SCC0NHLKKRtoB5Y0k0H%2Fp4VU8Li2QXc%2FkuFe1agCfPjowXYcZ9o%2FVKXK4gdnx8eNn\
        5qtO9kxEwR6nNatu1qkh9PrvYIV3hg%2Bpdf1W2H%2BGBv%2Bje3DsJlXK5%2FvqHFzwF%2\
        FN6DcxGdMfZ1tQq%2BmI6%2Frq6V9Cc8oHWM4z9tx5vl2nEPo6gmwmwv9qB%2BWMK47X2hU\
        lbVVMJvk3uWtYGFYQQbGSiFb9qm5HNQs9G0Yn%2F3LBu%2BRk22JDdwr%2BGmgs40zNmJsx\
        1zicwh8%2BJzVCH1r2NgRxIPNARm%2BO9llCVZUZaw031JHZRp3AymQkRTV3usvKGAlqtPF\
        w3Pz27FSyPuyX3Boc53V2WsmJKjO4BqI%2F7sLuDuVewiF738gz7LrL9RrKdG4Rnewj%2F4\
        r%2BhnZ%2BpwssdYGal%2BdBvlMSdnBfbunnALBwnzo99P4zsfFelmMZULtdHWmhR0gM6qh\
        yz13ygBnKwvhvo52WBSilUJhrEwh5SgDqwmonffOTA3gIAVaDy%2F83VwibLA6mSSpjdyBc\
        0NIBdzXf75oGarrZwXHvfBFwwDNuW23Bxt8j0dQD9QzGv4gYecq8xzu8a4zC62JNBPsBlfg\
        rkiJeJpA08DEVOCUvQg1MP3Fwr0GOqUBJFoR6c6t%2BVL8eKHIWFHkwvAWxIZX8uENnA0Tp\
        F362rxgRBmuekC7pK%2Bq5RSbH3teC2NudhUp3fuJtulo7m8%2FTd6hOSEK1MnoL4eZgKKB\
        bLD59hDLmOyYS31GNjQ8BxZXHGSwBbY%2BdrGuixIECo8SYrHwMLP6qA08Lak7H8Quzv3ci\
        U%2BLYrG6z9TWNX8Zg95hzRXft3kNW24xlWiBl4U0N6gIQhN%2F&X-Amz-Signature=4f6\
        0933f409deeb4b23dcde6993375408dd3c51479437de794b14a060f687df4&X-Amz-Sig\
        nedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-15T17:25:18.026Z"
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
UPDATE_TIME: "2025-02-15T16:26:42.658Z"
EXPIRY_TIME: "2025-02-15T17:26:37.417Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=0ad348f0a1bbc55f22ef5b41633e9898034e152562f8e778bbe7c94d3a6b44b0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=5181b04bee1d2f2e1fa74b1fa7cb83f17a926acc5aab65302e344244609b476a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=04d95ab58b2b6f33ffeb0fa7356ef11e5fda618a515705707f824845f4743153&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=21497114d1030d97cada921923eaa333de7b7d2cc320c68f153817b0da2b126f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=2c05929c7f02fba7c0ce554ef1858589fe28d39def3e4916436ead544cd5e71a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666QKIN3YJ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJGMEQCIBsc5SPza%2BCzRR5V4C2eKINuu98sRshqNTRjeuaHKl4xAiAQyqy1Hk5naqV6oC2IvSy%2F44jKMotVYU773V%2BMoTkLWSr%2FAwhIEAAaDDYzNzQyMzE4MzgwNSIMS0BnkYsX1Vt7pgqBKtwDh5viA%2BM3pkttHwV1Dbam0yZ500CUO3dPiEoOTj7T7Vl0kvx4bjiEnxfPqW1Jvq84n5mcUTmqANy86HOvnSw3Nl4225BKyOb4UHDCJQOwnuIp%2FVV%2FFqtOA6%2FErz0CKUF5zFgiYEIp3Tz0vCSsaMJelkjh54nwAdFjBXdQ7ZKqP%2BdIpclZK9%2BX4yXqMbf1W%2FIzwtCOknDGfxM1kaiXNWr485KQjX2OtSt8ZLve9uEfVZr%2FRydFjLeH%2BqGDmj6TqPBAECJnFEfoMvhtGm%2FBlFdcuL3QfVHmmBWI9ljD6d8J9tp4USPaBlx0VyY1qZ0SWUV%2BgZ61IxPr9paoMrEbBFJ%2F8ZEvnjb9GoKodzLcifA8HP%2FptlLmKnAjAOouOM5UKxvfkxdA2IzJyc5NQTK7or%2BJfTGpcl%2FZRKDbptAZ%2FxqSKnj8mVP7E3tObzqZ7OpVyaRytAiI0GArsiyMgOP4dohtSlNAOO25CF7CwNL0WlHbwaG9Ax2HL3krEpfQBTexSDrwxJXPCzRQRTozRnvsjSygvSsdlM9cUcQbtcpB6%2FED3%2FyMZcefG4GG5uhYouhbsjN4t1%2B9w%2F%2BvZ9SVZajmiC4iMo3mzsTOhnxGJKPHj7MPP5TMEtnpRpbBLUJjBtswuMbCvQY6pgEEb7%2B22CrTvWHUzR4qGG2WcCVEE1ygM8ybmyhjAmhi%2BVTZHaXzRoIspRdf6nPqjX24GMFCJiAKE6xczB8pg2MPq91Bvx5T7P40WOB03wLWrkyBsEADOznBdwTGjhzv9AVi0CBdbOKupfMKWHqzEdJp7c57zGpncmSbQGwsx6uJ79zQKSeth4kyhY0HH7QqKCcieqm%2F6tRgXmt3J8Gi9m4NGp1XPlAb&X-Amz-Signature=a498478ade7aac131f43e8ce0b8690f19ba128d55e60a3a002c926bb91b01265&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y653JRBY%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162639Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIGfe7iesu%2BRPRj8p6xLforw9i8n29QlKj4IpREhvdHMuAiEAy3sXI5tl2x6%2B000uO%2BovAhNS9O5zvbvOTuQJAwaL%2BQ8q%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDBllIBAK3Bm7gAxE4ircA36Bg3jV6YYyv9vJsW4J1KcLberuTkN0ZYZg1Zq0B%2FQTjJIggEyp7RCyoYod%2Bjo0Zze4Pq5G3JcaAFPUZwNKEkCySx%2BMumq5E9eFv44TrJxNT40QJFMaOIYPBO0AOKo9vtNB3zmZA%2Bj0%2Bs0VVCMiR0l%2B3b%2FFrXmFr12y3Z%2BZ28%2BPvbcWttUr1yJwxP0yzx7gGKjsYnEAv5GhBRsPZX7zLsWd4bS8DQQVXjM99LQDQ9cVTByazbWDSRGl0hUy17HWdaiOe3NU3GvgH8Gm9eoYzpRoXUcEVeXJULC3xMNrckYKM8nUex9kj2kRHtuPnZcfW7tEnd8%2FOptLPm5yRjJj7UCtVfHBIOtG2SWdBiqjj1FOrEHKFQiBjHNOL4PZGgUq3WjMAlkuzAsllKQNan5%2FenvwmFDzRtNtWIO%2BqmEiPYVeJvb%2BZnzr2lLw%2FdL5CfPKOvZPi32pZnnIIIs9%2FJaAd25lkT9bYQObwJFXZAzgNUCMwdHAqYRSnpp3vr95HaSI6EdTKm5vZeroTaoR1q75yfYqzgrpFSKc5uDC%2FGKJ8yYx%2FD%2Bhpl1XxoPJqMB%2BwP4DyePaQREMJ8%2Fb6heJNBZcSR%2FsoWhmCCz5gmaE%2BoL%2FpH2KxsX3dueYCldHMQ0FMKrGwr0GOqUBGr2AvQCVpJQ7j3LMj8dDvzfUQyzfUxr09vNvOahyHZrQBE%2BF4GE%2FmVIEKp6VB4SOj4QQex6GZY7kUfRxc2SfvpJriubisoYxk10XDbm7sNR%2B7cb9e56ZjKE5V2h%2BSdQrMdxBXuq9KxabKva6AWK0AhV1VLdvlXzKhmaAPKmF1v8L6OrCBRUXE4iiLo%2BS4LeNKyB8R6alv3XvDP0uDut4mA05OunA&X-Amz-Signature=5f88195c2131a38a50a96b45d086b97f6068fb7b9b2873a90b18b4f9daa99b5c&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=ef32e3084966601f78ce3d84937fe3e6d577f6ed8f2b135cd6b4c79b7264832d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=28bdf57bf5fad6da907a2955178d71cd1029b69441496d556aacb69f911ac24e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667K3AJYDH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T162637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLXdlc3QtMiJHMEUCIQCf6brBunKZSohZP7T%2FcC2qrLQ064oQSpaKqVPExou47QIgQEKiocbi1v8%2BjsN1D%2BWUWbq5afed%2BnNQGsXcS7DtydMq%2FwMIRxAAGgw2Mzc0MjMxODM4MDUiDI3yTMep5dG7Hcv%2BBSrcA%2BYnpfrLp515J5E4pefU4Ygn5LEoGzNgkUWc4CfNjeX9SUjJwqJz%2FHAStvqUtd0v7IShQpOkY6ik%2FjJZ2ZG2DPVhGDoKekZD876zc9CkM3MHkWsgLIB%2BjYN8bmrxT7oZ37p4h9H9JBAS%2Bnn%2Fj7a9n%2B2EXulSfS7vt3387jwl%2BHp3EznSuPUVIVAKUhUcxsPHGbUDdGsBFPdje5FRpmsUTw23Ie3l%2BEcW0PLGlWTMxjsLjTkKcvWO2XIWDOZ4zFtgXw8AtolWbq0o7bFkec075ZEm%2FHqU0lYxSovVP65VkubGTtNNyYMEk%2BLiRFSOaq4Iu6Fa1ZUkc2AtrPo5RiqA9Lsqd7qANgj89OXWbpDCyIHMPu4bnPhnE7pGSePAO3tA6B22%2B6hrFfEGX0nT2j6BMzVg5DCgksHSi32tHgU%2Bu8xKE8x2qIqoiua7zTukZI97Oxpk259iPbBSWlDM6RdXRZeCP0%2BrLCk3wSO84VuRvpLQ9MhXlXk%2BhH%2Fs%2FFdulR0k%2FvMvX7Q08iorAlNeS6yYfvk%2BHpgnNnIxKhTMuxSdZF7GkOVRiVrmKMIMOnsP3WLXnfUtiGyRBGNVBSMIIyVGYsR32KUphCRxyNbdMbZDqeZ%2BnJopX9AQtuhnO2nGMI7Gwr0GOqUBuzs%2FTPJscjQtK8R0J2IgaGHEK0T7vYiXj40mDrMU2mraYbzBs71WolytFjtfHxK9yZ0K4AduVQOgoaqJNaNK8Q%2FFqxogcxvQ4XU1JN80Fxcd1G6Z45TRw9eNIsDwVzI8JAMafMKe%2BB7qQrajC49mirschjZV9A83LBwLHT1%2BAObecKuFjt5fFJb5OxcfLkhyQ2A%2FuAqUaQHBWYGD69z5Hw%2F%2BgE04&X-Amz-Signature=e24cb07bb689d7619699efa4d3f8b79a83ae7aec8d61f42389b1a99130c3bd58&X-Amz-SignedHeaders=host&x-id=GetObject)


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

