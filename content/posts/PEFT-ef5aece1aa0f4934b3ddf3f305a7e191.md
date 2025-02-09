---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466U3EJCHL7%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T063014Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDeZ8q%2FwsateFbtt\
  JV%2BT%2BtkmApl66zBgocR3rquzx0wtgIgK6kiugK3mxT%2BLVuh4RVa4qGo9jGrXqpp8sN5acCU\
  aQkqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHPKKkS8vcWeF\
  nIzBSrcA7LsHUsnIMbAlmLN2rWvoi0kr75ZyFk8po1Owl8XseFyGeYgtPnMD1IIzDNo1R0gLVZPaR\
  rKQSZ2jI8nAAyYoR%2FXqin%2Fa7wFh%2FQUaK%2BAsgWGjkC23v15CYKINVfuB9s36gb5SyzyeZL\
  IBuCxTNeybEYoAsYsP1fZQIIqUDFhBNP%2F2EodrVokNZEzOmEepCpRQJPkUNtpKKzSkpRpI9cMAo\
  1oKxsuw%2FnSE2Q2ZwBp6SHQT5QMyRuV3Kv6xCohqFWq70%2Bp4l6%2BvQyncos1pzLKrVrWKGr%2\
  Bx8YUHcuTcaf97mvBidCs3jsqGuk13H8Ltyam46Vba7LSWjSCncQnG8BRw1euZbJSHiwqvGX%2FHL\
  0pFJNFkanZ0ntEkt0hBAdmG6vQ%2Bp9i8w5djsM1Dm5ywd6gPClldRfQypGkHQUOGzxV6bYwIuf2f\
  nidfLFTUlehodIGgbcAahKkxczGZItBzrvh38pOU0xIVlLgmeHhEz3jODa8iPVXda34PNfGjZAAz7\
  0KH%2BLlC4PNl%2BKrJ0E96vuW7jTZjN0DDnjJJMRQyOwz%2Bo3dVFdbHfQXpo4yxeEfoDk8sU%2B\
  U%2BfytTNCQgKr4455%2BFoLvSRSKq00%2FlE1B5E1x%2BFmsyNZrZ181RWW727N%2BMOG%2BoL0G\
  OqUBBSwJlSymawDL3oAETAGPG4zEDFvrAGf3zllpi3WDRIBFVSe%2BUdAaIFz1H1mnFMODz6LYwOD\
  GbuO89FHDXJl7zN4ea7ffsUjAVH0jg2P6LaoFZ9OSpQPvb5MqiG54qS%2FneHkcW%2FZw54XlqSjm\
  2Zz3%2BYFws3wAbfo4dNdp5gbKmRO7mfjyezV4lKU4xWEbtauA4fAeChsWXalo7VkXXEkttiTrv67\
  %2B&X-Amz-Signature=97490c4eae28fd826f1c2904e4b7be213d629bb0fa1acce68872226e4\
  a7d1b12&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TWQRGAOA%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T062855Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDQaHOXKnTNHtd6%2Fdsl9CFlzGVmyykvBTC5vcXUZq%2BAQgIhAILLRYFMvt4W%2B7%2\
        BWALaEIAQ%2Bil3fpNyXHKW247WHfeNXKogECJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwE\
        QABoMNjM3NDIzMTgzODA1Igw2SRMPaPD5rdMc%2BLAq3APRcqLNI%2FI36GAS%2FOR%2Bsx\
        Ucz7y%2F4tduss4eZLb37KVL%2BSMvvvtJaGYTTrr06TFNiSUn9M34EL2uIjNt6eKgcz%2B\
        wRnOYTduaZ7J3tcPyMagEykKXeToyysM7a58QU7nEJuHyEX3mNJrP1x%2BzzWwuNkj1KDv%\
        2BsfvnVPPRZvoSj%2B4tvn9CP4EIMTwSNhyaO3lGgp1YvE4PPVUJSekxTeP0lmz0N30RYhC\
        A5aZrMKHe51kulr%2BOmnCqc5xTQPy2oIs8HWA%2BvkG53Qd%2BpMRcDbg3TY%2F28IWDHZ\
        4QkypELHu3OuiB0XTL4%2F%2F5CZPco2rTJ8d89mjbUqB3aP%2FknqH3EJbfGrUCJWPvvO6\
        FDL4kjYJTbKyvgoiwATvl6eKLbiPBOEetuLw%2FZEgqdj%2FCtNh9YAcVUpX55CHArJXSAp\
        qdYhCz0BnThS6yR8KLk3%2B6HR5zZoN8QPw9ypwNX5Cd3FpmMYNNODK%2BYkmYm4UxDuw%2\
        FqIyVP4GK2BuctGWa31e2G9jZ0w71YIi41bu5EnsD1rXuoZGuVxLofysKz6KIwWpmtPr6I%\
        2BvDwUBCd9966FYIAs%2B9HJen9tgvgP0ZYFmsaOpKUe%2BH3ySM%2FzVqEfMGPXKVGFwKJ\
        w3YeJ8qimvTXPaoheg%2FwDCBwKC9BjqkAVbjX8U3Kg28oY9VbK2M7PtKDGMK4LlC1JpF3y\
        14nJ29r73jQY9og3hIKjYiRRAOmZApD2wxhdb27tqTarAPgG1qx5JVspRe5y3dVt1j%2BeY\
        DE3dF%2FWEUJ4ox1fYdUz3qNO9vt1xX7AFTHE%2FHqPhFXQ%2B3KtuwNmxRZPCuuGiEb6wv\
        WkAC1HNKB%2FUJPCBuI8p0GGgWJBWB0KIG5%2BswO8JIeT1H04lx&X-Amz-Signature=dc\
        b4b4b04d39d2016a7da2f9e5ecc65fa18147dab647188aab19a65b2e4fb99b&X-Amz-Si\
        gnedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-09T07:28:55.653Z"
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
UPDATE_TIME: "2025-02-09T06:30:21.704Z"
EXPIRY_TIME: "2025-02-09T07:30:11.795Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=1c9d3ed1c5e93007681f365a42e79fb3849acee0a16ea9eb5483c1e4354c2272&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=82b14c4bcb611e1a8f9df8b224e4bc4c2dd07425cdb4131520694fea702b0156&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=a0f9ba74e3b6b3673d401f67abd68a2600eac733e308a52916a3599edc08795f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=0b5f4ae0b7d5f2fd5bebfe132877a97069fcb3e138df0f839d8606d7653ad40b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=1a0445ca37b66df1fc6396caca41b6b5a1b49f517cc746854c7e05c5c7b98c13&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UBKJWYWS%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIGMip5KvXnoSRsVcD5sj9shRRV6igBMEz9IgLvE7mezdAiBOUhP6zw8gw5FgxydnmtpvE4ZDzQljgrMW0pqud81aXSqIBAic%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMxv%2BDv1t2jXC2s%2FBjKtwDRo6kvg1A4EOeizgir85FRZqh9k2tMvLmk5%2F%2BEHhOLdXzA%2FM61xkYe5V89dKSfjlPJW0bx7HvO%2FZuFkAuEjromIMHx5YcLWWJ6i8IvcjfsO7%2BIA%2FOi1179%2FdnBdtaX5bgRCi80yfi%2Ftgg98LGyjVKH3kH0otot3w7g0041Z6mw3OhpuQmREJH6ElovKF5G%2FusDIcONHvAQ0jEhAPEcSM5Esy7xoltvmGXMwul0ZRxMWgULKDiXfHLjL8lJoeRmkC1R7Aiw5LL30UQO1XuboSpfBg5stzrc5Bd%2BlGwzB5TTkjwp4W4ZWjxBlomL8MosiOD8XXS2YHWqTBLqR%2F%2FgqE9m1bFtcQx6OWTs9EvIOCdsb5GfzM255R3r6%2BsxN%2BT12EqVfcpg9bztSHYxgmn2BG6hOZNpEEeODtElAT5ZY7ati5i94f5oIxN5cY4zJLDh9xI9nG3DNEnElJj6JlUEeMmmzAqJ%2BOI4moT%2BEgw6YRDZVkyVxsKlDVIV6pDr4DwVDku3f0rAGf%2FZQw0yIpBGAyICW6F7r9480mkeyoU0lXKUnlOOnZJ59XrfDvMTLUTcX4LhTdJ4iXfYt0Bx6jKjkE1N5o3UXruOGHKLu5tIO8LNpvgF9kgCQEAYhgIYAgwjr%2BgvQY6pgFCPsJS4Vr%2Beg849yrY9GvvxsgjHz4hml3W2wqOjudTXBiM3Yelrnu3x8Bsxavj24hY27VD%2BIImRdQMl2aca7toe0PVUqdJ%2BdakxBUXVFwRVH7911cqJakNt6kiUzrRkI8%2FLsnix0sMoc2%2BjHKpYzifHfXWneV47qzdbvhVGEsnEX6ZRqERwZZwGyPOa3hS01swxClCUIaB5Koy9%2F8YBYsW%2BBvxjuFW&X-Amz-Signature=715e4d1ddec1b28c544fba529396325edc621fe4fd21150f2084e1602e1b2065&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SZUCXZZW%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063014Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDvQYkO9x8NeB9V9vspfy0eOYTCt6zVjae9bTXr3rY1DgIgBPT2gPSQqoTB1b5QpIVecwecMl6O1Do3doeNJG9m4I8qiAQInf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDC9AdhB1xLxi%2ByyFCCrcAzqYy31RRbANb8TppiAfWEJGGqDTOyl4480r3ECzJnHD1gKGMA62d60hYtTD5O%2BVZuNKviOy1NeQuVaCGgO6qPoUxPz%2Bz%2Ff0aTJharERnBz2ar8qBQQtm651IXUMnJgy5P6thMFr3Yvvhh1V057L0sE6WPOY3qlmBMnXmn3wheD4LT9HgKeLzTS5ECN4abVE1Pc2ym2hRdwma%2F%2Fo6cAXS5Zf0ewvvsnicgIH4%2BJFlZEm368VcGRwrwk1dPVrY18FSFuDydZ4VI%2FYCqjuyLr%2Fd%2Ff2Eyg2QmxikRgJc7NNM8HRxSwPRcW0fvMbT%2F1%2FAspQSGmBSYhiYYh8HhejZg1K6s9O7i%2BO6URf8ipmT31uCiWgSQlaj1wwWRzixpu9UiTAWBiJVe96jh7SZunUxXTmueqwpW4OkQ5WnWh36SBB35%2FOWwUdzseu8uxlxLCc4WqKXJU3S22VZ3qsWElRKsNcg5U93rWNVtRhp4L2b1R14X5PlL9RBCmQWqP9FtDTZ6gc8yWlY6y2qTh3cH%2F7adolQogTCjlrwosaEW7KdiZuo7xT3YsqnMJF9FQ6239LbEhQkePraRb7GZCedMASu5J5LkfFHndPBaNSpRbjk6LBG%2FM9%2F6TXgzd4GBgIZLQJMMW%2FoL0GOqUBP9cynYXVzSt7%2BYKOys1hWz8FBVXEjK%2BikOBFZfhnGF7%2FzxqlWk8hPuMTppSSnuHIqRijjvNXAT3hLVA3RuRUIWQw7nYMp2T17iuAbU6KDAKkGTwDcdDgt7goKa8iNjWWM%2FwagFmNgegGXEw5gjTVuOYaIOzAZE22oTgldHnQ7FB%2FWh5itElQZTSA3gqEiaJbNv%2F4INYeADf%2BhNXjbkyZSCYqL2mi&X-Amz-Signature=a3a76f9ecedb1f4e7fbabae046f6e351acfa59e3227a092c0542e4769af054f2&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=36f871cfa6f9f63bf9327b290acd2f8d4239c97f45a47b6b5c55a0b68a808437&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=a335c42f093555d397b4d8da7d0a1aaea2599548f73f04f2cb862863fcfef62c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TG7WVUET%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T063012Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBgF3hbGiaeewfBpfodIPM87pDV1%2F08KGMCzv4ALbFc4AiEAyboqCV9hpxngnJdHqrCie7FZS1UtZ1K5KTEUmt2hwdYqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCy6hkO6iFs%2FlN00ZSrcA2b5Irt7Oka4jR4Z7MyypxbqHtV5j6bjaOy05OozfigEHVbtU4mQI6wSQSzNCPog4Qd0Xkf0j4KrDh7AvE6JNAOl1Bnl6X%2F9COQbJWaTYHk7T2qVbm663orp93SJHgIRVIrBmjyq4sXoHHrdEmF80qayzn65VXPCJtzvOMLjQm4whqdhjtf7fM6R9WUR91jYgMjA%2Fk5cZ0IXsuXvwyby%2BLW%2BkXHfiLa0hs0UrfeDvAYZTtFnqGWmMl2j8UcnZ6zNNA6Lbl%2BZ09ymuIkJkSn8dOKX2%2BEI4dSxD%2Bwff8lOPOhrScEE5mu6n3s5cnjmJMmrWParYEu5T2GIeVo%2BxL7%2BoPPu7A14KlnK81m%2F2YkN6m60oxnKeTOWhQ313DnOB7si6fdMzsKsS6T5xbXlZBdqRH1%2FoL4OtsPNqml7PZshI2eh6K9yaznDfChqXduzSy26703aJgiJFJv5gFqnJpTIo2RJQgofF12UZVTW3t8ntwDbN%2F9Mj0gI5ysTPl6iXqhDGR72e53lJJI7cfBlwmmr5LUFJG1yu9d9K6%2FRU0s2arqYF5J2dwTWZSQyWA%2BXud5p7yGe2NxxntljV6AreRCa2t2KzcwPTTLmDxMMhtxU%2BFZqp3Me2%2BZ9d8Eab87sMMK%2FoL0GOqUB9UTtoDjRRx1pqCLILTF70og62%2FnRImvgW9fllbkFquaLo4raGMVRsZ0ry7gNhVuxr9b7iCbUfpzzQ17HZsvWgse5%2B9rLbfnWmSmtz3BcrJvIyT%2Bo5wFOPxYG7KJecSeOVUf0RSzC91Z5%2FJQ5kKIOzSY%2BnxMR9rSoilLJ2HVqRLPTaf8%2B%2FF3mwno0d9WABVa2JJBkUZ7eo%2FIvvMy%2BD82yYNs1GcEx&X-Amz-Signature=a014fd6f1b95747038bfe80f9d49621d78e0cac025e337d20c94938a62f943c4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

