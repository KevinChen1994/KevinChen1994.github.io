---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TL7GKEX2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T132844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDT46RAwgcBcG5V1eH\
  %2BKWFZDbOKsHKaE%2BrwljyfS4re6wIgAVw8QVHcwEaCi5bxN6ani%2Fj6LX3tV5uhxpXmlD2h%2\
  FDkq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDHVRJEJ8Sj5rrbLOtCrcAwN0V%2BUzLFYXwdrlpyB5Y\
  hcBHKSkOMQ10TkojvwALhkcN94NMa3YqoMvLQf4AJaRXkzW1KmH%2FMUjqOs94vzEAd2CF4JEpuLz\
  zvZanm26%2BcZoxNVOtbHbhXlpLAhyXY%2Bo%2BzFYfGWhes%2BPNPJDiMZs%2BVyhg4MSjEamHhJ\
  rxWJAy3gZsm5jkNGyqdGc6Lz7porjy14KP2mxTY%2BhG9OD3sh5y3r%2FKQCxKlAyVlH6O4RcT5ze\
  oYKQxMez4qlHSHzh6U8xioQtG7dj%2BQrVCoc7vsSfgfQCVLDWnNeyWsnRlCUMFATYStWgob1tBey\
  M3mKIio5v32s7apUErmte0qYV4vr31EKawmky%2FT%2FjlMh4ADauOUvCawXbZL83%2Fve%2F9FEy\
  skjV2x%2BJI2X8ffQm97mRXFk1Ye9g%2F00lYeqjRtH0q%2FtRnnYqOnUec30ebRsfK7E1bXMfqEO\
  Jg1UKG2QseJ%2F60gY3wXdnVVQzn86XKqiO5iiXIaOsboymq5BWIsOHRR7oUKN2IW9KO5RQKiZ2WR\
  18cGLGMG18ihyburE5Bynb15dx4pN9ciipm8cPm%2Fuv0NeGpX%2FZk%2BN2GC2DBozppR4UcARxv\
  QiqA18PrTSoTj7nxg3J%2Bzm6l2YsaQEB7Mng1v8OMJLdt70GOqUBItVftAgyB%2BeY%2BUYB4cg0\
  zgE4GaDYGPwmlYnrlmD12S6SX0Z2YwYo3XyCMoQ5c0TddfrGGlh29tBUONAzMI2QiafgUQ1RluUS9\
  JYaXtzHF%2FUYwZcwxW8d7pnKfMxq4mEXoKYnSXytMA9YYXpJQ%2FnxRqdWoNueuy3aKPXN6Jczt%\
  2Bcf0Ta0qXG7fQkq3wd6poIjAMURGoWIsmvf8Aw4CNiNeTFlw4a8&X-Amz-Signature=539dc15b\
  063095d0515c1564c5c4c4819f6fbcde8beb59520552b8a8cad18625&X-Amz-SignedHeaders=\
  host&x-id=GetObject"
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
        redential=ASIAZI2LB466UC3NAFEL%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T132737Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBzwLsvF%2BBiWyZFmwLcnyrxjwUjmInAhAE6stK03LatLAiEA8M614Yr%2FAwMgkVnY0x\
        61w7WBFEQ2Mo06lPz7Qe5rlxgq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDDq5HEbIgngcPH8\
        dcCrcAyX5GvoEhgLdMOXa63YRE0fGdXPA5JzXb06qmDNbw%2FJSk2bkzVUX4y8Rmr9a4sGE\
        ErXtj2g%2BDebqf%2B83TojNRA%2B%2FwrnmJnGWrRX3DFE8LW5sCgCGJ35mN%2F1g89iQ%\
        2FgEQvw44ySpGauGk%2F7wub%2B8O9rZEzr9tNTApUsu4HEkHaXKCnt%2FPbNlvj%2FAl0l\
        Ohre4RnOQ1mynZyRqKfjIs0tlncRHsSUpDM6Z%2BWqITq00kTIpD3AFWlOwO9a%2Bfjr80B\
        LhgD7YT4dM7LIWhMY62XmeVsBOn%2BpzpsDgGFCxQotdKTwI4m2kK4S3gejXQ%2Bkemglh1\
        JpT2MLcwbgSeBsnYLYNguWcRuaoSUtEmB8pnNbD7hISlriUAE1lvVGBONg3PrV3RrSpWi%2\
        BA14%2FQZYkWDmZ68tp4HvijqLl8mDxNZlyJrLTUMt3o6lPT9Tou9gpkqBUwMh1jKUU2oCK\
        MZ%2B6UH3dxSyNQINLtiYQNtG%2BQ%2BWrMUtvz7PaeEhqyn7tQQVw4eCqaJr3Afs89oNox\
        8u5Y1B4DQPqaCTb80J%2FnmotT63rZ%2F2%2FB4zzGQQ2%2BiXWVz6KU1GvtXoJH%2FRRLl\
        PY3YLOTGATzYCnm78RFUfm59LKxL%2FCK06QDjBWEts8b0bPI7FpdPMOrdt70GOqUB8ViGh\
        LZrid%2FkQeN%2BscF3cquGUiojAyd5fI%2FbiAdtpgKzVTqskPyQfzSchCPx847Ffn3Q8F\
        O%2Fds8S7sPHvkYQrye6HxeWKS0sXm4dv%2BJU3cG77N3XDY4YNylWgCSBARD%2F1q6mbdj\
        LSEnY4F8qwzCfF%2Flrx1kSeV71hFldSkRrEjvod2DYWECPTwMrViZX2oD1b2mXMcJeUVxe\
        %2Fk6tWtd09QyZkXVt&X-Amz-Signature=3cc55980274f35e8abd4afea86a471098149\
        6debf29da502e64401a040cc27bf&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T14:27:37.900Z"
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
UPDATE_TIME: "2025-02-13T13:28:48.319Z"
EXPIRY_TIME: "2025-02-13T14:28:43.224Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=b333a0b258131c05d840edf2765d05e103e3f531dde71553f0515fd1da0a61a5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=a8939571c044ad6a4328260059af5df9a795249eb8682c56ccd5958124c3ea6b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=2a4891f087d8dc248d3c9d6cf1562ddec75caa476e5efab412df71b68ba4a62f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=f6c642c63e07366ac802d5d00b425f93df7c869c60cc5e5c414f1d769e821e1e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=922dba9c8b88b3dab5e02e2edcd5eb6e3dead314cf0f204f76e5e2feb69f1685&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46674X47B4Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGw4mP%2FvEKUBZBuUIyNN%2BrdBaJ17EdE5kNh3fFaKfxSxAiA3Fzrj5LDXLK78LxjRhayLvz%2BFd1Q6z%2Fl%2B4H1hrrjycCr%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIMJzOaNYDgFeR3gZXKKtwDh9CiUV%2Bb9kt70Kodtv3KWspVAM9afuPE%2B0oTVMv7uI8%2FGoGq%2FtPn4%2FqYagds7wsmH8G5MkCL2dvMdWLe%2BfoCtviUbUMK1FU0AJ%2BiY0roIzmb0lXhfMNdtArkZZhjhk1y8xwPNNKA60iAfzJTpPxxOz%2FniU3VqHAAFvCmYUgTuRnBrBJXNyDEzekwelDHVGhYsNG9238KVpCwsopmAh2r%2BFz%2BybrvTgmwChWq%2BIvHBd%2FtA6nzG16mfvmW%2Fp%2FgYCPOsztxD92BY1cg6v2GdC5%2BsbQTM%2F5eA2ylA0jRFORxlxXwTDghp%2FBVmQjCc83RAuqTKUkkpni522Dz0kXEZVZhSmm0lLe7knw1v8RRLcbjvJssnkFW34FqptnN3K6pfQVWrk6YHfHjNqFMe6BFs13fb1DlfjmUi7e%2BQNwI%2BtvngwuNJoWKV9zwKRpoFjR1P4S1JkeG7Ke6eUdB587ppPuoGrl3PZW%2BssKFhsC9mQUTEbW3KwzFIxVJ4tAeL6kQ3tCAr%2FU0ioOxCCloAW5vgbmPWhlRnz2uhdsTIX6M4JemQYy5Jhr9XZlf1mg%2BYg17w9SdTg4rFEpJ2ZouEJQdPeaNn%2B35272fgQA7AUTBE%2B3Fw1drsZu1dzLqQDn54Bwwjt23vQY6pgG18G4nyLOYLtyCIi4ZWhM2M1XTGbBQx3XmSDmhXyV91PImkGVqHoEamzY1V9RneHSD3nC0nmfEiISUYumkjrqHD8d8g1JXmweR19ADfxpIXOgtO9KYGba9%2FGti0Sy%2FTVIwa8EZxEAY9XPl9kLiRolJRz0CaMvd4gYpK9rkeDIuZ6ayHT%2F6HJwxD0as8bDl6IKOaqaDW20me4tcRGvtfeQGdiz2MrM8&X-Amz-Signature=f1c311de81753410629ccf17cd234670321d6da10acc3b428a9d768e887eb46c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VILAMG37%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDgrAvQuT95Jq51U2PmA7tKDFV%2B1N0msERYR7Tl16iJGwIhAL1sLbo8iJPbZPO65g7KsQZrKGcuIdSOTsrwDDdkggBVKv8DCBYQABoMNjM3NDIzMTgzODA1IgwLTTgz68a%2FGSgJjcIq3AO4IwW8ElX8pIYlO%2FTfjGpNxaClt5wLycvKeT8GDnguUYOyt49Z%2BN8xwkWp9CjNCuRUpPlxoL%2FhEynvHY4M0J3YP06fn53coZrQ1CdXsao%2FgX9A8k18GY945zDMHJvmqaam5wSKtcDvIGsC%2FsdsdD7GOSVZcjF15xj40bTz5yhftoSdMiF5W%2Fy2HmA9A%2BfCDkmcrzY4Gzc95OtWZGPj9hMw%2FBrQPT4Xd9ERTvWCIpSgCRjq%2B%2BqsiCbRC731ZtGlHE3nMlmCONOn15sdFZz0D4ySdM3jAIFO6IOeiIrTukQFUUAZ%2F6i4%2BOHylJA2LV1RxETdRlPh%2FMvJ7CUBM0gU%2FYuNXRBWUqMQrRioTeZHmIcorIIDhStnlzPSqhe0vszDQASKSszZWTJZTzZ2GfO4NEynkRx%2F5kHEgzp9ZSO8g9C9ajs%2Fz%2BEpydqLfm6yBOIuPfJk2X6KeROhrXdRvLdnWhI6yvmhRPzR%2B8OALqbgUtLg844NUQKIYuQ3xHx599t99QvfGo6Ja7Mu2z6PfSXqpT4uFytaMmgUBwO24AllVb7FZPioft3gm%2FxPgGsrJyAir2wlt%2B7UFfZzXYXO%2BqAzc2fMqXX9Zy34Jp3jnYNO6scWe7SXFVveSZ5q5lSxZzCF3re9BjqkAS%2FS%2F3EAB5JY7M3MEqK7SdVC6Ex2zJD%2FATlyh0VznbMJKeqIOUA1t%2Bx9eqkSR2MlFXj6kHK%2FadQK8lMW29IHYiNtDMJ32EUN3lmySWF2e9wNAWPJeXc7Fis3U3ULpn%2F93rP1DHb6iFcjGgzNgezvpBPFZPOCjSC51DYkUDGMgi5PwVVcv7YdUaMlC8dI1G2nSveTk7abtlJwhzb4R8VP6l1DrMxK&X-Amz-Signature=c44a3ec15faa356691ddc21153c1a3e20d7d0bd84f95f562002390d123010680&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=7ddff63576716c9b072fcd93fb5d0ecaeff11b51e567676ebed88a76936219c1&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=54a2b46c9fcea28606d0e6b1ed16a94aba8fc2582e8b7877a6e622b1524ae9c6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VPNFPSMX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T132843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBIdiZjBFKUptL6huKibaEMDshO3ilW66NKFTJWR5%2BkrAiEAkAnh5zyX4Vw9RLK72evlJdz7gWOO1yBdFC1xU5nyfp0q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDPJZ5Qe4g%2BPwyDmx7ircA51alZMLmv70Gv%2BuNlJz1UIDzydahX1eq%2BMIxpD06Q06%2BelK1TeCbyncVDgs01%2Fc72nwn7nP0LQlHQ9rSx3e8BrqXtEmv%2FujXu0Zi2S1pY0tlf6cm9SDHWk5EZD28CQ0hr0lqJ1xDDOQTm0YkykkGxb6ipopZhyIvvYYX08lTepx%2BUHaP8wHewbzl1WbBnONfVoE9PxRLUP4fy6vjR4cbSMN8EeLcou%2F60moFFeejaFGBA4rQqGtzOBmZY4ikNmZEkaV6si%2FcH%2BX4YxLP7mafGb%2FkyFhOtS%2BeOoEqb%2FukeF%2B86yhq81A39nwrwQSNu3ngghPmsQDd6DxHkZWs2Uw46IDUXkrjqNbVj8RzcIkGTUzBpxHHnrCJAVlBBHgFaZq%2BPZvmxTmKRgcHSF1jjcmGfd5fHruy2C701HXA7r6Wsg8ke9Tpfte9nGaJ1tyG9O6WKWGSdfWmmNacDuPjFeUHfftCz32zJoYdemtG803oPJ6%2Fw79qyePOJr5QlouRl97X267rhtRtJfDaydiaYgYIcdOplJGOUvpUg%2B7nUDKCxhr0IAWuaJBFspclAJrjKNINynPy0a60pAxhITCU2Wo%2FHD8MIqHfa6GDJr7DRhlnbrmOJZj4%2FjlcrGSN9k9MJHdt70GOqUBC1L4UucWoFlp78h3cjejj7cKouLUGAIoz2e5aoNwwTsxdMySdkSBofT%2FBOe6%2BMDvdRqGwps2kWrnxZR1E9R9S1Oixev%2FPuL7TLag11%2BJ5t4qTDGbE881WhTkg3TLZBrAvgeuvdBSpI1%2FIU3e8%2BUDpAdnvujivsVVXYFwhMbTAXPfk%2F7p81UrAVnhdCM98qhP2uZYZAXQOJY8OsoL1OF%2B%2B3V9XWLm&X-Amz-Signature=facc097ca47203f4cc7b15d8c1506d205632ac23d1ef32a45c53c02b926d1786&X-Amz-SignedHeaders=host&x-id=GetObject)


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

