---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663C6RJPY5%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T172047Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEkaCXVzLXdlc3QtMiJIMEYCIQCe05dIA3eTtl2B1cepRDOLNXr%2Fg5H1WXI8lOKR4u2itAIhA\
  JyCk%2B8vvd1b1oTkUoE%2F5HHvEfyo7IRdWv8nJADckkmHKv8DCGIQABoMNjM3NDIzMTgzODA1Ig\
  wNpIJKeaWzuRzWDQkq3ANeGID3YOAC1kXaNvMwjsRxFOmgVcQJ83qYpkhGbUHukMbMuSjD8nGDbgr\
  PZx02yb9dTDy8rjmH6k6liqqAKUkl1YKgcURqrbL%2BbzbPYeLUH%2BAo3DI0cPyJ4vI3tmAYNk8p\
  NVm2jho7X%2BiUZuNMdBMfCrins8m523n%2FpqW9I%2FDSo7GWcp7s%2B6ff%2BkdNV%2Bw9NBpWI\
  J0ANnSOKXG3m0wp2c2K36zPt7xYeSxGbXUGVE7CALIZHIgN%2B7DXZ9JPdZOLHTgkh2tQhWdYBW9e\
  CF0p2y%2FQc8TvNQO7JV%2BOfUXVGKSkNq0%2Bin8X5FRQ3Py6e1%2FyrGw%2BkID0YwoeCADaFDl\
  EfdjHZTlOhZhlwdU5ATVEkw0GN%2Brgmfi70kJgUGbkc8IWzaAvXv0U3NZ75S2ER%2FdzzyPN9Coh\
  OHeu%2FbtLXYcVyhexKWujnO%2FcdX1rW%2FJfvnyFYqZzHSAwn4RazYoombp74EoCVCmNwZNtFOy\
  aclddFiJZAcwBWGf%2BiekhIhsdv82Ilh5fH38nC3BiDea8EeU76NSlMHh4eI%2FMifY5%2BOknvV\
  2UiQsg%2Bq16rUao2rQvFr4ZWfQG6xGgDYtKi3wu6hS7NDBUXkQwcHRww2CGWSu0uRWIBs7o%2BKo\
  zDxmDnGbjEDC70pO9BjqkATHxhx9Xw1qv%2BxeJcRWiKhx0phkoJGOyMXA2Tspe2IYZptKflf4Khr\
  369weXIY6DyJkfPV6XAtTBaIsH6h940iXOezcfb4txGNTF3Q212YolhDkKNGfr7v0RgqFwvUV6VbP\
  oMtdOiXmzNgYAh0RPNwq0WuH9n45R6uk441JEb2zMdGhNHU8Yt9L0RuDCcbf6hWrf4HJLBC7WpTpi\
  aewMO3KiO5Af&X-Amz-Signature=92a5bedfa2610977bc91a8551052da36c04eb406d2580641\
  ad63e04e436acd49&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SE5EUDL6%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T171917Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIGLPNfReGSWwFbL6%2B%2BE7t3EmrCc\
        LuvpXoA4F0nW2NT2yAiEA7TimVdef86weuckkEXaxnUE1twF4uozpAd7tJNuGe6Mq%2FwMI\
        YhAAGgw2Mzc0MjMxODM4MDUiDMBtU%2F93J6DsfIIk%2FCrcAwntHdVgjyO1JANpqylNGbY\
        5rUzwFe4uJaoe2k%2F6ty8vxmKYazBBNq3M5MLQAQDSB0knKQNrmZwaxeDHcFO9jn4zW5L%\
        2FRfKTWcEIDw0ocS9WD1XZQ6ayq54ySOkcNLGizAPH0oWwLJ%2BB5JJQ8%2Fjrkidz8EdNW\
        XTBjawMUlOkq7GZlNyFMyLLyiqmfI3NEOoHs%2FyruezgZOtNU2dzR3tWxPq2me5QeNInTD\
        RHBAkq%2Fu5mM2ZcFdv1G3t3Mgcq%2FivQIs1hL7V5bsfwOswEgbL5r524TU3DrMKpD9rey\
        elcRTcTXZedZtrRrUckGA%2FtuuUUIYCrxVTvy3xFhp1S42bcwYJpHVsdb7zcn2IrKVE4BK\
        r1zY38z2wjmiXmaAOOnZ05yJROnpdcnYaoK48Ofk1452mZcKv7N%2BWuJWBvdGLPYdmQRy1\
        5n%2Fron0Bjpx4KTdqFmCYvjaooHlzOOaxIt8Anf2uRPs5KU9sInxAoJOtmZnVN1ajERTHZ\
        YqumdcSGTUSVG0ne0U9tR1vknXkkoBB5TV4fK%2FZiOhldTwCJ7qFnVLoEpjRMPPSfXhf1M\
        d1H0XTh6iubfIvfEDWWi%2FC8gdBPoLde1%2FRCaSEN52RlPCA20dfvwCYOiMuCgkLaeKPV\
        MPvSk70GOqUBh1wD%2F1XQoqeTiOXlSvzWeXEGZ4BvwbLvO0c62XUmJ%2BZ7Mpbd9PjC403\
        Qr7gRX6D0hzG1mu9vNXR%2Brdjw2ciRfqKFu%2BChuPp8n7AFMXjlkGbKLZ0tkCDxAToL2g\
        xBAeW7O1bc%2BachKsdWZxryOeYtt22d19Znn7Ifhsg%2FVObA3VDSl9ln6o69X%2BcO0Il\
        OJbsLzvglwrBMi6PhmgEr85ecqPXSdCXs&X-Amz-Signature=22382facd6a9a698197c1\
        2f1cc77317d57ad0a4ac17653e5062f20310bff09d5&X-Amz-SignedHeaders=host&x-\
        id=GetObject"
      expiry_time: "2025-02-06T18:19:17.560Z"
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
UPDATE_TIME: "2025-02-06T17:20:52.913Z"
EXPIRY_TIME: "2025-02-06T18:20:44.450Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=9653cc7d9e3afb781300f4b6bbf65348fe6cc25acb0cd321c13fc08117c5d7b3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=20e85d62093d39a953d09db9eadf28e500be89f6d29c2f8d128eb2ca795584cd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=cf874771577b509ca0bab9068f884ff5508ea42bb7c61b78afb91262f2a5d5e6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=840d4c162257755f3106b0c0e330924e49d745b0d86a3e2d2c9f9fd0e7349558&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=7b4935d185b9dcdcc3fe6dcda6d7b4d3bed466dc726c184dd8ae37a94567665c&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SQB6FZTY%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172046Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQC0zQDT%2F4e2ZxxQsi34rw1jRS2ElIQmgVnw7SMYHcIwlQIgWJW1hUvJxXIPXoraZp1Wva5hsemGz6tWSoEe%2FutAthcq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDB6OuGEFgL4mpva8ByrcA%2FVYRgdJ9MtphS%2BBAvA%2BDH8fcMXYsL2Srih7HQx9r52UEL2YHeEfr5c%2Bezx8cy9TcfVzysPWNNquwH761X5QPw0Tjus8X4b3lCfduqfOh0yxvMADJNclfI9pKg%2Fb2pp7Td2WR%2BG0DNNPJoJzmssgJnzR2shB6AXmLFn35lv5C%2F42pZvYLPreER2fxvajK6uZmGPwAr%2BtDMxhBhpgtIYHUWO1gp%2FPY%2FThRZ%2FMNDYeZ2xfdiy5%2B4mzDddBXv7Rw3GoeZDUizffewe8wSQzHl0%2FRRip4hBWXvUTwYrMT%2FD8nOgabGbyXm9tBnVoYcfKPiUJg13ndeNtm6a0CGG6OBxTIxweCBoUWgFf0atHU7puYrrRW%2BJSGAX84Sh1Dy7smi%2FwqedJZeGcZkV2MyCGmwB2kREl6X3HnT0k9bjpLsY1WLuP09%2BS0tyDvuubttadUIoEnExdjfKb1%2B%2BF3xeVa6S9iQPBi%2FiwLW2CKF8FSexMnPPsylP4fDTV7biJwZjtJ%2FKU5hxlZfbWscJJX7Ko5IeR%2FdRg5hGYUKVM8zzfBMhFyzE4d15q9Z0yve9jyn8SuIbK9tbecvxXpt%2Bl1Gd6YJZG3yB8cLOfM2IvB6MY0uzirHMUCobvpOQ%2BIqtORvxgMO7Sk70GOqUByZps%2F2jdj25FNLw5E4v79ED1923s7V%2B0ny3VxB5Ij7Rs2bT7RNW8C9KRP9G4R5EWKnby6pLnETVAdt4tkh%2B%2B%2F7CWW7tuP79JT%2FXkOA65c0KjM70xSWHIrQ8Is1ng%2FKWLW4RUCkyh9rU%2FZbzIa69OfndhEJM1S6nYskpC45av4z4bn22gOrMk2krkT4GS0OeU%2FxIn6nx9quBEIZ7u1b9t0pTwadYe&X-Amz-Signature=1b8920f4f0c506c6099233ea730b82bc732b0399d9d40711ecc700327e18bd71&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SEZ73WGE%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172047Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIQDYyeiuoFVWX7pcoyD5yN0VPudXhWFRj00W22E9uEswQgIgMnsWEOIcRSb841VgA0E81qxm7vPvO8ms4pCJCSR1rYYq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDPwxvuItM13rY%2FT%2BPircA0V9CxYkbGGzLiHkaPWcIyN6Epd5L1dR6as%2FMMQlFkXwQ1Ut%2FLgkkCMxP5pWl00al0YYTJVVbLfshX2NLmidVHMImbjNN6OocOTDEGPMojSpd8ULW%2BhIrryEyE3ag0uzrjX617zadgARnutf4%2FRnNTZWUix%2BUhWepsjjpBlIdgs%2Fqh12z1%2FUfIAxFnjC8%2Bdhqq%2BAzVHrAuenjMmAx%2FdF5T8vyip1d8z0mF1P1p8jFJ55yI%2Fdpq7Ln9wIfXDhg6rjOBvIt9ZLbR5%2FSy9V7gX0Mnq7Mm5PJoKI0HnUbC1WM%2BkKOnH7nbU2nLCoVy6S8jhbp%2FN4dLV3yrkFbkedNq6iqCk%2BJ4ZajtYbLMmcwS4DqKdcVIdjOTs29P3EYVx9ouMu6qtIV5iuNnyz7eZCDOoua%2ByWPGTGIpEGdHT4Nn5Scjhx0dwAa0OaDk2iG29NX%2BRTeDaAk6bz%2BISS9BieWa2%2BDNFFFGYZqknuSUw0X%2F4Z2Yl6gPLTOLWIpSrljR6s7DLBAN%2B7ix46HZharBRNA5KNWnXnfapMEWaanC%2Fgnlv4YWvPLLrQpq4o3GeZlsuuskRLxCD51Lc5eCNpFRsyYxI4RAh1qQGM8elkaFkrIsPQDqjndpGvUZnIDGff15ThMJDTk70GOqUB%2Fx47fsD2gA9REJKCFddIYOa%2B7%2FzmPTMr9HhjjPxj9Ta4HolzohTILEp1PQ0tx5Wb1WrdV4cGU%2B1oIy%2Bq2aRtB%2BPvMrV%2FR0AnWXLkIzVaXUg%2FGDiSpDxHaqHITlpzXxOy91cdO33sbj18xEBd0Yemp9VRMmt1PaVW7cVCn1VjVfOXPwhiO6%2B0pMd1%2FASlQMcQvTn2bZoQ3I9XM4KK0q8u3SoPUMPu&X-Amz-Signature=0aed499c7bd7dbdbf6debb3d3cdb052682130c24d8e30bcb0509d71fc2206911&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=6e92d586508b9b073ecd0158f4d640c7a29f7c9c89ffafb2eb32b662f75caa15&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=fe806dadd59207a50f1cba1f7ec2583317d308d70b5179ba4c7f7242f7569cf2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665YQ6LGFJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T172045Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEkaCXVzLXdlc3QtMiJHMEUCIFaKK5SELjck8BxT5go4mkqslu9E0SryQ3Kdgqr4dJqVAiEA9xtHmbB5ZF78RXLLeqzkyACSyPUqHylWd3NwDzpSe2Iq%2FwMIYhAAGgw2Mzc0MjMxODM4MDUiDBYB52P%2BYyKenNhTaircA1GG708hp3fowmcn8EhJmRcHQNAFLenVxRZXAKnSdTHltBvMFzvOwt0%2FGcHwFAJgpgord0%2B1sKHw9s4OUIUe7w1xP0LzCh9szyDpHGe7Pznytss4mi8rwILlWkZj1o3%2Fo%2B5hxZrDpKX6oWdG6IETA9Vev63p3rT5sfer8XWvV1uKOhDKx99fZr5WBpAtdg6ax9LVBxLCdQ8OeQYggX9EwmjCnFtNj095pZv6XswU1G8ugLYH0q4%2BMkdHOy6SVIahGItfuyygY88KjiLGCk%2BEzr%2FWENh6W5Mzy3cEdMMgBEOMBpyo4Ek%2BQ%2BuACzKFP5AAi1KLRI322ivsTYoIOxtey4ISVIkboUV70XTkr%2BGTpt857yUcMmhpVdQxsXfFkjetdJ%2BfSDldwhDFuST44UQDKTdwTaTfbywwZfFB5VpxMYIX6SxgVYA38%2BEPvwRU9HZlCjzQ8NHLG%2ByA9m4YsNjBGB0oljQ6441%2FJE%2BkMsANUnZJQW502MnVrLaxbpnli2cvpC3Q4mHG1Cr7fjgY8w2Jg%2F4x7BFEMWU1Ihe6%2BcelmmhhwwozmWJcLoBzbVjJ6WHadsD2vaH%2BVKmB9cCieiWkkgjUSs%2Blr35n%2FRujq1fbaJ3FcJftv0NQ6hSmye0XMMLSk70GOqUBOukuTNv1Hf1YsgRfAezyufpbGJ6FwYERlLOYgxU1zvkz25kl1NxkWlaV1QEo4cdm7%2FTX0IK%2BJEuktXGs3bim9nMDUf92z2PtXoqXM9cL6HMJxiFHf%2BXmjHmEO1dHLWQ02fffKw6ztDo7eLiMwBgyJWlm%2BeCRJSDk7L2LlAeM875iLxISVealdBYm%2FEq78t%2FWtN2gtectFq86PtQGbqJxFCM%2FuDBk&X-Amz-Signature=8b50bb0ba5fbd07bd51766847366b7e7aee3aef530d1bf3dfd5d5f1de87bed54&X-Amz-SignedHeaders=host&x-id=GetObject)


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

