---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466R36FA5CN%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T111937Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDOPVRSVQhufjUrkpcI\
  0oMDU00EDotbK3AXuJs8dNfZPAiA0%2FL3cMkQb%2ButLevwESX8y9ewW8GsBfnc4bSxXUuSQryqI\
  BAi8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMFcp82p3GDUOlBpWuK\
  twDHV5GEXjedCs%2B7DIc%2BKwz%2BpVSQb9iQcrDpvKVnZA5TGQFGRiudjz496tmgsu%2BaPl6tt\
  GZyQlehm50BG96kslFa8OCFd4CLzdx4wec%2B4HpEab27z3vwWJGMzm2%2FUe6hUxyodCu8Fejo14\
  HejHciXGIZbEg9Vg42cLyGe8MgjT4vAt2PFHNgTH%2BjMnvGqIU%2B0aaT%2B2923QMhApCd7vG0w\
  0%2BFenZdVTIQqe9nu8qvWR1iOgFp7Zt%2Fe7jw4IeX%2B3NcfG9hNJTk3O9JiDMbko4bKBlIZNOC\
  DkXWBH3musLVbovWGKFXl56qdrgw%2Frnx71f51csrJba%2FHx4ltry1e0hcD3Tw1j4KH%2Bnb3CW\
  ljOrIzPU2EDtAE9EG785pwcCJ3bfDb%2Fc7r3lSzNXpwJvDmFmsMBVQIKmTA83yY8ko0cunVqM9kl\
  ZOefWxuBAW1UoSIAr9DQpPLToFtu4ub3lXB%2FJDDm0qOfXWQK2Tc60Z23dSMhuYB7Vl844rw1JKf\
  8bLLoPMXQcQ0u6LccEUWKvnj2kcdRRD0LQZlfwTs87K%2B4wG7WT91CQzVFCgzSgnxbOtcz7rqcdu\
  SkjUKdOdRDa%2FSUCFyY0q0WmANx6JZCT8eQcv8XfUcEmfV1TiHEOguwFnA4wna6nvQY6pgEHrPQd\
  Bkqyx76iE%2BpZtbf7jk046ed6w5eT2hCnTpMrKgmjhk314%2FNK%2FTATlGnTDmx9idDBVRpnHWP\
  THCg%2BiqvVBiNz6dYh98%2BVtZDMf5k%2Bk0hwPKeBEPgiEZ9RWgFlReuZZtJNKFcV%2B6PTHFQu\
  nLsCy95%2FbJqZmmfpa4OkttCYCxpiSjTCj2YStpQ2fS82nVieri%2BEEumxgqW1Zll2t749%2F3I\
  5%2BBMQ&X-Amz-Signature=96a0ef6b76c14dbd3c3fa64ae7e7e01caa130ed4885b55ca4356f\
  6e8569d687c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UBKXK7PM%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T111815Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIFyAaNKtTn2Bk56o9OYhRE3yU4WWimQNkm18AnRxDzJUAiBEFkFNu0kPzLqbzLtrzI13Rh\
        5ioBhyUH1tbt9oR%2BV8LCqIBAi8%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQ\
        yMzE4MzgwNSIMI3ZAxOc3lt6eaqEtKtwD4jZIsQWyUIQebqvLPuqPsGtK%2FqjgCvC50chJ\
        AqQMRW9BahUBSLUcjPecBkhjMjvEWlNycClJBhgisN7uChaGTbkf121fgFdHwgE2pv%2BKr\
        KVYurFGtPB5snFCBFOlvhCM3ReFr4Yf8tnzDdSSY5Z7PB9jPMxw5YzB92imLsFdpmevriYi\
        Q%2FUW19mRmEHgd%2FQqy51NI2ozp%2FaEXJJBddcEj7CChvFXdI1xpVr2XSJPIlCL4mOGm\
        Y7Ddgq3EHNO8nH4106cXHxa%2BkJ6Zj2NhY8cjCwmJ7MuAbwmuQxt7aM9CllMGCPizJOh7w\
        dEtN9iB4h9yOP478MEpQAwr4wU2PhE93WZXABgszMIdyz7iNRWmfmroKlNRf6F1pAORbfi8\
        Usm9YEhc%2Bbz1gFZ53MrFQdpmIjgj%2FNiAGC1i7cfOklpUe8Qp6Txi8HehxGnifXNn19%\
        2Flno7Z9%2FY61rk%2F1vpM6Pm8GVyhxDrw1TN4JWgEXBwk8XbyzY5W%2BhOfl9Xa6yg%2F\
        AtD0RbxDWyZd7%2FHycVxwudrK8w1SRT5krnCIzaWlwEJlCFeP8pXrBIzBCZ4HbSxlLZZQ3\
        RezG1F2aHhL%2BNBX6DAbEV79grsJcC9KGJ8It1lTGMnC%2BpJn9wiRpTneW0wxa6nvQY6p\
        gG8jIubxtYxU1BLqs7xuRFYp%2BNkJTk0TrAdu%2FwyJ6Gi2B9ZAdn2y2SyxyojVDDpVMwu\
        25IpSPHusR7w7OefI0JC7k6kiV8vPXErM3gXfl%2BvlZwjBCia4TX%2BtCtvwaQZJgIoiGh\
        N7vJQ%2FOs%2FxYb7Umzc2eKeM4khrXtWTg5Ul5FH1V6%2BrbqKtCjwQzYPVrPyMwAaiCvE\
        MjvWkFyp2V5IWBGJhtNNMVET&X-Amz-Signature=a209ddf4341102dca33b20d83bbdf7\
        f01cea6c581406f43184af3f81c798850d&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-02-10T12:18:15.703Z"
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
UPDATE_TIME: "2025-02-10T11:19:43.629Z"
EXPIRY_TIME: "2025-02-10T12:19:35.311Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=66cabae6652f1b543b016af63aad0d00f6a89c9b01d10d6c1088506816f75483&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=757556c41274e685a01675512cef5cacbb0729f3dbf784b92492571736af68a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=763fd84be0af855533de6d7f6f1c0aba3c9dd2bfc9b772e5991d66d1db90c746&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=3908e03f1798c87f78cd636656058da162064cb48f3d4741d6fcd42b581ee050&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=dc176021df88a566f307fc5834512055a0c990d62969419312f6199bba314c7d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662G2LANC3%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111936Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID%2Fn9YzGIp%2Fl1ZuNH3Re5Wh8dQcvM3tEODD8rh22ySjhAiEAsTcboxCJLCRAQkMZQT5%2FyCtKHjFEdPTspLglad%2BOVVoqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIuTTgw0xs3GgLXZdCrcA4XdkvtfayMn%2FsIb0mExiyj7IIU9tNOIy6BNhPwSyax4sJiQswcl1U4Bz3BSALi2VQt0JH4NHaB0mS1PuE3qapLCeqY1I28LlrrMNE7gd%2FhT4tkb0IwSP0VMrvUHNIprVPL3hqXJ3kP%2FDWwDlsZpJoH%2FN0JqVdbtvNGFBmu%2BiI2Kqt4gjRlSJWGbvNoGPnpGV6SbO2ooXgsViySJEVo2FjALyVl1ypgLvyP%2BoXhf9F61BsteblbFHdl5ODPY66zPOwc2pdq37iGhbFzv6H33v5M8yaL%2F4YTalFaZN51Q%2BS8CPzNnyaMlbtlht%2BfgVyE7o0pX26%2FCR6kKFQkz%2BJafxCRnNFJEx%2B5mbW6JQlTYfbVu3ETCKcmFMloZRj2N5LPugP8GtBC7Gb4zGwY8TP8%2BVJGmhITq4vWuur2gNLADBbjchxGwpfXPNnDaSAK%2BxmlSYdj9hdya%2B80aAwfKLwendpbSTaXKqaD4BoMgHkridUqi9%2Br%2F5%2F4VTz1Qjw59QqxGfKVeBefXnVrY1C3vTs67rjtumSJ8GjMe1ZeiYq%2Flds3L4KhR0lpS75iSzNnac3xgjaw9TXZ%2BQsEysrqtXcQIrLCsQlhTFU0K6H8wTb%2BWWO9u17h%2F35YdsPujQtJ7MMutp70GOqUBdMTwy7cv40NMciVL8kP%2BQKU4J9AbBia14536D1nLnng0Qfqn2788J4yikUubvf%2FBMfEh1cOhUra2YJNBF5gnHlCA5g4SAHMABwb25XSBUqzQJI%2BvNcyOJkZEmXSv2GWKxE5Mmvs4ogABjN5njQj7SWzDBsDpZRzjrMjLklLALmEeViFOUsvam6Q1fA0PP8OMTAyOiOdY5rbzcCBKtzdUhVg8UUHx&X-Amz-Signature=fe6b6ef6180782c65474e50f94514a0b6c60ddf2dfd7f1fe2331d025d8415393&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663VSBH636%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111937Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIG2Fk%2FZG1mxhAkTo5PBGx9criInzkSVQ9ioiMyMfESCBAiEA%2Fq5FdRUDop1h2OCrUbWcD5pVoTGjVdCtJklgphfOU%2FQqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDESsp8vWqfFoIZDjwCrcA5CIC8NyYqdEuihBvTgZZnZLO9S9rZMWTKRMA6%2FgIqh75fnMWRwUeVo9TtFzeX8h80jInXHBxOrI%2B9PmCvz1EVZmzYEmZ9GKmRGVRyykq0i8%2FXPMAGd%2BqIr6j6SbrrKdTwIYEvzxc0SYTqnEo%2B7X%2Fa2yh%2BRqTX7G5BGeFeYbsP9nsQnFz9RkQ4esveY0J3x%2BoneYvu6%2B20ldCwIj0NgeK4TdX8vSARZkqYrDFLqEudN3OlDi00H581gT0%2BVTq7h9rVSv4ahppGyl%2FJaGrKJ70y3DhCsQ2wqaP7G%2FMwxOcXH4Awu9nnk%2BSf7liixvM7okz3%2BxR2IXO9piExHKReTDvgGwXaBROHHGnYadJ4w%2BK2xH2ABcoJTwSehl7hH0bTw%2FlkNoevMpaqNHOadtbPZUWgFiy%2BrkE%2FE0n4Wy%2B3nVNxF01vvZzR9pu5Id8iwH4t4dKLrLYhMHtIL3sbRYHPsig7fmtordEAUdoDHPlXD7LAcy5S78%2FMtiV9wczL5xf%2FEDQHpIRkON0Z325%2FcHAwwJRR4YZRS6palD0iYLUliXGYy6wgJyI60iJouI%2BKIbmGKkJ5nwe9rOYBybQCbuJBEc89GYvZpglz0Fmx5w4M03j6Da%2FsWfHzzt%2FlE9mcgmML%2Btp70GOqUB4%2Bznm69w21gHlNH4Nz5M1T1kUk%2BTb21b5cgkh3cq%2B2veW0IPPDF5zmgXvcfy4HUhsMHOHLpxqoHly2spA0FdeCLialZT271W7QKYsqqnPjsjWxaZfK1DdiZstrzKq5FEhaPolallSwmFbTAlUoTscBBmsHbRNzySUxeucdFU8CCNt5zc64uUYgNdNdTeYcKQnjX5okS8OUVMQF4xTM1WfwycYnkC&X-Amz-Signature=38434280ccd2c1b028f463bee36d6216f89ee3ccf2f55b95543b0d6d11d6fc4e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=65528a6f08722025435d558d2e60fedcf7083e97c87726b791e026cc349fe252&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=da6495f1630aebeaa49aa46418e6b3b0fea85afb3fe68bd6135e615aca0a8138&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UC4ONWYZ%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T111935Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCpwl0SHi13z6U0nZ7jiGQ4xEVT5a23VFdSF2H7%2F59sKAIgHBjeSBcrkaXqqvWYcHpyRFfn%2BJFchN%2BcEa%2FyF2IBG9wqiAQIvP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGPF%2B8b%2FIMrxLVwE3yrcA23Vpbz%2BsyTKJMmOZkExz3wtTUxv0356xDZQ8OiR9x%2BGNS1vnMkJlpkzZNUFeV5sqloqRj1KtxO5ZRoHj%2FA%2BNbG5uoqHLZCIAG7yXmgmtLEFif6LebUM6cUoWMbI1d939Bk7ZyPRq99Q5akm6VFLtRSxjNsPerRP7fxcYFcGJlXaQAT842KgQLm8S4l5DIlzEok2XCnFjdSDyPzch7%2BYfiShG%2FDitScKXWUReMIdqR2dLzyP%2BgPoKmJ2w15m1MI7gqgFcM24U5SI67QvOdOEkzCW0UNUB92Dw%2FyowUnmMIZoKQQUMZGbhhURUH9D0gd7Np4EByiVnco%2Fx0B5xLRFNZ4u4jrncej3x%2FgHGBBxIpwjb4JDYjG3oDXDxDtYz53siHXWFJk8alaCge7TDmAWMPxbm5OhvLsp3sXdQ8eWJipNbVjpELrngpr%2FbCyI%2FfDiZCcRBwxV%2BlPTHQIaXtiPt3Y7994T6WtvdnHQLzsQ1CKYs%2Bc86qKeyzpjl23Gm173%2BZrC0BmL8MJRTlkPfS2c71XpGdG7SQo0DAmHgJ%2BmGK8FRmN6ZIarHc6JfOXlP%2B4dBvtHdGk%2BedEt5x%2FOxzDvzJ4p3A9lbuQedYUhYQGr13sEyKfNlpZoZq7tsZWMMIuup70GOqUBfuKxJl%2F3ET6a5Kgg5zeBOX2TPFyN73psdls3bCffgive1xdWlyT2Gz%2BbWoUNccsjuxx2AUpMf49Wflu4UOVTUupapXX16VybfOuj2htaTj2RJyc%2BxE0uFvyJ4lw40xUXb0ZL%2FQbuYhI6QJOq%2BlkOvcwel2wOh7Z%2FA2mRfZUMoRqc%2B2XQyBFwC525OUlpu9rApSv3l%2F9yKEIHz2zYKeFYhUdxASxJ&X-Amz-Signature=fbf056c7614034bde24b7f73ab5d093e9a06302c303aa695f7c2c6b0e68ef5c0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

