---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YSYOGDDB%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T022220Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECAaCXVzLXdlc3QtMiJGMEQCIElwK4pBrlXOsnXuoQn4E%2B67opUL66CmCWY6imhXwLmxAiAbw\
  s3AyQrOvM5DjC%2FKwolbNcJJ7%2F96VaDRi1SFgxiT2ir%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM\
  hurFF5fAu%2BDufSOgKtwDOZu2rT2GYPM%2BxcbcHE9hBLkBBrf1YMICnGiLvaQ%2F7MSOYIpfljc\
  kJRTCVysPH2Dj1MTFstShqw99CVKO%2BhVsaId1yjcLwO4V5H2uGE097SfRoJOKjkIBZd34tMY2TI\
  Hqp20bFnMR%2F2DH1mtbE10%2FRVoLzKJVOd97u8e3f3bKdVLHf5UHQXLCa6aABAYZxOEXcBUjtGQ\
  vtG5ZtwsKHkQgCczzV0IjwEKrjbFILGSUmorye6dP1HHtTlcMbVzCc%2BzyCtdZIFFYUCWO3Bpjed\
  E30XEyp1%2FEKDrZhWdUrnZpq0R9RsI0QBMyB0L5qDlDED%2Br9CGMQdWtXhmuShDQHNj%2FPmZw%\
  2BpruRJsMSmdNZ2E4fcFcQnOfGCS6VKNtRADwBNRKp6K4QnNnvM7kLpF4Xzs%2B4s19WoeuPfllT%\
  2BywJASFulvHWBV4Rzl1ACftC82U3xhBCGV6lGZJmXcI3tglY2XPVvEhf6pZiqsb65iMNcyRsOuYR\
  Aeyo%2Fx1yNPkAlTWh0Z33%2BnbHxO%2BLRA508RF2Ev1NuotnFwmVIVKkopMKHIRSN2JwP5%2Fw1\
  JVLvLQkLVA5iAB5KMtm%2F67ZaZ6osCyzGGLN%2B8E%2BrrTlq1Q%2BOl2LnBvMXJmv8c%2F%2B1U\
  rERS%2FM9cwt8%2BKvQY6pgGxA7OBVLvMcZKP6pwTAoO1ZCMs5PbQHSEXJpwvUtjJS8ck6jpe07qi\
  cMWTcQmHFc3lj31xkLjmMgoWaVDJSEBk31SvLQrQhEkjxvokPPLL44PWHAFvCsDt5zJWXsFgwEmqZ\
  sbQRbx%2BEzabAxiievPgcqFykX02UPuO0EXAX8uU46w06tc2J1Vj%2FpTUfDpC0a%2BxM16x6SkK\
  gZ6%2FXcZZwYvT1taR9NFu&X-Amz-Signature=d7a724e5cf4df5e9b58f13bad9d9b3152f661a\
  9f409d7bcc51b83152a739939a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TQKWHYMH%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T022052Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIAotZhkkBMGLhewN%2BTsiXU4D%2FL%\
        2BJSSmJjvv8QsiVoV8KAiEApIUQWsMyUUR%2FCsYPp5ArHcZR3p1z05rKzr4OlOYfPj0q%2\
        FwMIORAAGgw2Mzc0MjMxODM4MDUiDPxaEQ8gWfXfdQ%2BH9yrcA0iy87%2BCXMxHP7b6NhT\
        %2Bb9IONwh8xoppMrpKarTrIHVYyNXUM4nN7jZhIvn%2B7ZO00%2F2cng4IF62VfaC%2Bb1\
        4XG%2BYFWb4f7JsSE5TGI6wJWnfOSB9yLOnfGpQUUUhKdbjARQyNPcQuViLIc4JGWSE%2FI\
        PyaxHklXls0AWIHhNivUKvkIZX6lmPg67kao4kYfmyCbuCNTfaGMH200Rc%2BnFapnGVK7P\
        ahsstQLUammvrVBOAPMWPlfgz8t1BhjpvthbHYSodL5vibD4wHWk4SyFxt%2F8mbrmOstfz\
        ijG5Q1C0siVrO2DSsj3ZbiVRPCAByDJVAH4wXqgrQm6UxyDXEAro0ZsP%2F7OMRjW75aDtR\
        oJHR34pREJV%2FkAzU9J4QEiA31ysuhSaekUNrW4u0fcO6rxKjVS0xv98974T830DHZ2wVB\
        705iOyuF2A3soJkL3nCfgReQEsREYZpCuIYuY5npv%2FX3LEvdFHxKbbo239tqBNE5V9ABR\
        FAIQZBre7d%2BN2O%2FgsGFmQ%2F5B%2Fc1cXBEv2CsvMPGktU%2BTsk7Z1c%2Fm2NF5LaF\
        gEZc3Vbd9Z7MlmvLRWLGRQKCbLbF13sa5zxZ8FEYaR1BSez4vxDs%2By1TdptQ17aDUT5%2\
        BxjQSLKncwzMOrPqMKTPir0GOqUBF4hWVzeq%2BOrsnV7A72vbhByjkCS0fMcKaLZJqi%2F\
        pZNw%2B29cE8gr1JzYeh7LoI9W%2F7SjyIbEwhkNnJ%2BGSS0%2ByHn6v2njapMihWtYDGX\
        vOf%2FTLkLfCeZw2Ote%2BD4X8vHcsyV9ZIcRwQ3qbpt44eSRcTkfg%2FI23yWr747JOfSE\
        U%2FXrgTI8jejCVIf8XaKdp6g%2FbTZGtxmcEMlgfqgLWChK7VhDrGVyN&X-Amz-Signatu\
        re=4a6b8fecdef12310314e2accaf13c6c84eabfbceb0f264e29cfb841fc5675704&X-A\
        mz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T03:20:52.138Z"
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
UPDATE_TIME: "2025-02-05T02:22:27.817Z"
EXPIRY_TIME: "2025-02-05T03:22:14.526Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=ed79616f39cbcdcc6350d17b360e75a4cf8771c845f9e00559ecabac7bd00950&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=078622340b60a3cd9b8eb2d92d7825a30e48e88e8343d6b308e5fab4cb437ae9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=fc112c6fa66d316a098514738132d527f206860277181d2af3daf60b0488244b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=1b2f5cda2e8ac1090d9b3def7bead99aabc35a3c2a659d233b48e433e009a0c4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022214Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=e89d31cd66708c6a049022aa2e9cd17ceb6c3ac0e20c8d7f3e144689f3603b0f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RSF2UOC5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQCulHHaGWIEs%2F0JWsHb84sOPSxDrgX6UUHWytmIQWcfFwIgG7n3vjhxzgJfRuOscBGbyuQnlGegjYyTXI%2FtQtJl7aYq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDLH3my1u3Zl23wZf6ircA%2BtwUEQPN%2FpYtwuWvBR2dyP6kAGLzUr7pfLitySyAJgngIlo1vjz%2FVqp4Y1AkBuCFRF05%2BsMN2XD7uyTo2NR432BwX2o3enIeRZ6Q5cxKZ0p%2F0Ezb5cVVQQcq6RRp3KKsRO1qObceIKmGdBkrWy25q2rTy%2FmmUP%2By3bAW%2BenMOb5jo1zHAfcPjwVUNwP2ETmMtfWZI8JjF1AnXiPgxB7vAQz7foBQKaPsyqaFPD3ZpqV2jtTYQopoilRdkKhEOrh%2BY98J9sK3qKsvcyA%2FftF0Zuv0meRHE6UasSnEOyk0GitF%2FtYUe8Q8ygxQJGU%2F%2FBj5frBmlNRs3%2BiCQPAFt9s53%2FlTwNX9fLA6aSikSaAtdGfkYWh2s1PnZZd1x63tAOzlERYaQZwv5cWRuJsoX5o21enevVijpERo1Wriby0Z9TwyWv9Lvu%2FvYy4j7pZfmz82yhwU%2FCM7HWANjqRbCfGnSDQtBoJWhoxSKm2D%2B1AsJ4FaIxbTA%2FjOLTFkKJEBrXQkopANIGfoxvwcuq328dBl1k4atsWdYq9UrGGet3Mre49RCveeTREfuTCioUcDhSFZc4wkv7og7xG2n8I7yFHjaC4b4bQb5%2F6sX%2Fn0vnGAtFwIKdCzRHXyLuHB73ZMLPPir0GOqUBEON7q2WypnyBJjIDWalO4c2jaFt7IIlNeH3OUxiW%2FD13%2BZ%2FacTxdrkGLRctcaxUdmtEYcfoP98WWVoY%2BOFw0f995ixaIDVzR35ddVDu4BVmQkBBDLtD%2BK23Z%2FWc%2F03WrrGtFsPTgsAKkDOMoQsZ9X%2FqDEOa0Whdhj00NlSIL1q6eb5Gd3KCsAvrAcK%2FrT3hziLdZygKwmQ%2FjO2HVES4hbaZfVAXR&X-Amz-Signature=a7311f77cdba29296d09d5fe1263be5f9841a6e9a740f7edcb3f242b558096f7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NBMZM3F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022219Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIDrgQsY%2B2jasAqHVYdaEv6jz5aQdIERoIFKlGT43wjC3AiBOD%2Beqq0Ga%2Bzxi9sNz%2FiD0%2F1hCiOBJR7wIYX3AxK%2B98yr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIMVfPsNAMAyH2s4j4zKtwDBAhNvKHidE%2BtpX6FyOQuaLT7nGNVoFVNVqGB4oQ61qJVu3MngYc9haQzISVAJYE803tE%2Bu60Fmd3L7e%2FLBcFGgB4r6eoVUKG9wuBvJYeispVWsUJn2Qc26eoh5kma%2BY%2FOSTSYtbtuBs25fC8nz7oFQPkxh%2BDF95enFaTeVbmqDfoM27FRvK7Ti67WlICdJ4%2BcSM5wgDDSMkEIf48B3dwodQ%2BeoU0IBYtuaWhW%2FQTAgziV%2BMEIALzb5tmneKN1cgSvaCOk9rnYYD%2FLQfd9yUQ2OicYnNAEVm7mRSpNvUxWAXWjRNuWtPLPHAvLYrr%2FDEN9ZpdeWdAZtrWbHv5AaW7%2F%2Bqvhn%2BVF9U462psoMZsHAZZ0SVDCnvRA9apwHm8D3MnmCfd7ghzUAsvsi2iGJUi8k0JeaoSZ%2FBk9aX3nsl%2B1MzxjASI9P0jhUepZ9bFsQJusAUYH1%2Fa0Kx%2FPi9W2xJkrL54OulXihnWenW9DKUF1EoQ9m%2FcHUhqvm5QAxmwjZYoEfac2QyQDS6bvdnKV8DAL4XXo7s%2BJsEboRIBhK1SjSM6aYBhzyol8e8tkFaCq3AAa1HZFc9lPCrDFAjNEFqo0wUiMwPfoMc8ClgGyU5uDgKk0Dn3syJZ1z%2FUCKIw%2F86KvQY6pgF2CjWQpM%2Fy5x1%2B4h60SmeqO3s%2FaD5n5SW2HL854LHXlUUHgjHmCGffbtJbyH8MUYOMAdpJM7Zom8rpy4dMcB5b2Jo4ggEVFRQ4MCTwLq1euKuYhT8j8CbJOrWUemYH5A0TtLy8G6OhAQjboMdNgvHDU6Wm8EbDm%2FY9%2BsSx1wgowI%2Fy3LRqrMgy3XXvR8swLzK4VvnKhanATzk5ZyvshFScRjS9EGZ5&X-Amz-Signature=1b437e992ab6cb81b055481b87800fe685e702048264df161718966d26569e6e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=666056edb1ac443452119b04827ad76caec42c1f80552bc75b5639de353ee0ad&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=946b1eb791e580888de34f5468b70ec8f36c0ccc317394d2eac8db7dda230c9c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666OHCGS6F%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T022215Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIEMSMeg1Ac4%2B0X0pP8XAfu4RcBJAdHFwj9l3MoS%2BQB%2FWAiBHxzSw59Bwf9t%2FmyXxpK6RHZ2ItKXI6%2BDHMjTwXPPmTSr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIM2LHjk3vmL%2BkRWg1wKtwDvDUFwl%2BkePSwU0vfoNfJOVNv7Tm1vvrJLZe5c2IBEdNn7m6ap96uRMX2jxcmHI%2BuBIVGSSfK%2BpBsCzIOf8GwVQjsMP1M8agpHwzZWdeROCR%2Fxshg2LAhLtKAgVEKxw3%2B4FV53JRBTRcLPzaxUdql5rX6vLjPCioR7rE8QUaWK5Px3NBy96yxCSUnhGg8OIuQfu9LbBAeXwaii2hKPWjYafgN0skj%2BnrJlumfG7Z9S8os6nElgP9di5Vg13UQ5E8gV7yj737%2Bt1H7SwPfG%2FxlO0nmrIxPxauWROWZ7gxNzwon%2FgPjL2NfojnZoPzcF8vBPhnaEq9a8v0Z%2Fb9%2Fzkkc%2F16bcOGFTYdBE8kwAYMJSLP551KrXPvx3lnTORlE0zaSKGhZvjuDss2xEvDF14dEpYFWwDBgZa2GfdNp8vmqMex3gyjyq2Lu3O58uv0ONs%2FstvIx8wH%2FdWIOQlv4NUakU2ivJKmV1PV9VWpWelPZ%2FBB17quRwB400%2BBcxx%2B1SLRTUWPsDkOYZtzKxKn9o4PuX7d57MceRjjWiEabYbLUftaSHBFsXoa7L43U%2FdU4V%2FWQhf4rALE3H8JqqJJAp4%2FeaQliCUbY%2FxgAdAiEKhuxm%2BzGMTnZVFe%2F8Kuvmzgw%2B8%2BKvQY6pgGJk4Cduc3k%2FkgfFSokw1JG%2FaT66cKRNinVqp0KL6%2BA7ZRxjbwv2RtMtko4IQKut4Fzzcm3uvFFBmbdZEa%2FJDmfsBAR6IzKQ8rv%2Fqxet4WShl2bsLzKMMwsM5O%2F5GYJXF0NhByVNgC5AVcv%2B3UdjW5yyNbh0M%2Bs7gIFpYB7ZW8rb5CLYkGewN9yFTdvoi%2FU1yJ4JLB%2B%2FHMukkTtLDpqn3USHr%2BvQml7&X-Amz-Signature=d82593b260e343a4317a9cb2464f88c1e7aaf4c5cc2c0c8b2b981acf83465d14&X-Amz-SignedHeaders=host&x-id=GetObject)


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

