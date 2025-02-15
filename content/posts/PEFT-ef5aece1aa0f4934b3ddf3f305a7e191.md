---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46673NACGJF%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T124104Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBsaCXVzLXdlc3QtMiJHMEUCIQCuf40gEAWSw9Rbk6Mk5ah0ERNZU2xv9wcwZ6zRb20OpAIgY1d\
  rSXMHFnt8E5T%2F6BXLd9W79xF2W%2BMcIjIMof5qlAsq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDA\
  e13RN%2BB9861xMJ3CrcA01MlJ0ukjvri9QzWjmYyvTqRMEapipHo5C0j%2FuRinnHOZivyYOv7P6\
  6Uq6Dm%2Fg6S%2FE01yGMIuf4RHlmaBumWfTmsjP5o5j6tWOtGUHe4z%2FF4YcTlphkBgvaG1gfPL\
  XO29y4A%2Fq5XiIu%2FXQaF4aq%2FXVgFySyZvfieKhxyI6ahVbHJLVpZF5Bt7TUTmFeOngEMa6yU\
  bKRW9Bq7%2B0x0Uel0SAcTIbJTWZUDcQ3x9jVEnmBYXMNuLKy%2FcbFDvk7IPct%2Bf60xljScKIo\
  dsQi6EJm4TX%2BFgR9j59c%2FpGOXZtpJY9APFKggZMFWS2AGahWTO%2Bym3XEpFEhWdCd1DAvNQ9\
  PwhTNtY6BUXcbMBwOa%2B4y3Gom%2Fd060xq71Avtb35DNWPYFECXeKzua5ZzkJb0S7naBLC7xmUS\
  WrhxtSYcrW4PeQh7CjnSj2ytO5r3BriLRppl5wzrBT7djMhzbvRrEFIo7YrLtPe1RYFrMKDK17ZaW\
  FrwBKzGfQ0PwNMdsNbRu10N5mFBe9mryuzmfHJg6ss2UVuDE6QZO9vjpMah%2FSmfbpLT%2BrEQ1y\
  0MLLHTv2GXAKmK6P%2Fy%2Byytox1cvX6sfcmdtCEXjTYxai%2F%2BGqZwuJ7N5JGPttSvJ75F5dt\
  %2BdYkNMPTtwb0GOqUBLND4sGTVqhGzOIX%2BU6q8wrzagZo3GIVwwOqnpa3jXv3g36ZqnC6KrgJz\
  rgci87MVmQ%2FM9e%2Fc50%2FtLnjk3R8V2OpjJA%2B7gxXJYBqTTwIe%2FET3iXIyLyCYLOo7vR7\
  7XQhvDVfRJHl0HFbNkbTTc1kq8aN7hdNWxagQvP6Y7aE7TRbW1kBuvq0PJ4757BUE6AA0XHdiq6BQ\
  p9V3mzlD03WzudgnzFPG&X-Amz-Signature=ffc8d38cae95650d3fc41d11e2d1f011b9098bba\
  aeddfc548151515ea50b5156&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466UT4LY5O3%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T123938Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJIMEYCIQD8cUDBN5zWmb7nJTGBysiIZqyA4Py\
        7lWICZf6bPCJFJQIhAOKyFelau9T2C9ZlXRz4vZh9E1Aq8dnux%2BiF1CGgr%2BwQKv8DCE\
        QQABoMNjM3NDIzMTgzODA1Igw94UGWLPwtahrtOvkq3AO3YaMOmki58rk9hPqisOEskqf5Y\
        6YyjFm%2FAeighDsYLAG8C7aMpTUuSBL6RgDiy%2BTVasK073bmj4spylEIb50OwKt0nxXM\
        rSDSfihfRHu8QUoAGbIw6jY40oCsXTzCXQmXHK7RlPc3%2BFTu0KoXoINSxL6bQyxXWsP5z\
        86%2Fhh4KtAU%2FZ3GvstrtEscO22W0%2Bd6iFhDgoKrDGD%2BZkPpgcpU4EBcxXgII%2BL\
        XtACwbdKT2XWU8K8OjyYdkc0di2v3bK68pNLLn4b%2Bt04VVcmjekwNNeQL%2BxPMoKSqyP\
        7Z6MOwLArjQc0cB0swwWfde8gy3E39esMN1Y858WdAhildekX1QAmIgJz5TWbGbdRhzBhnq\
        Y9NMBwwdmqQeIv92EAwFioF2zUURBrvDxMx21C0SBj%2BQrYY3RcQUlEAatPy%2FLDjnFkU\
        %2BLbgi7kAjvbRwAlft5J5GqomdrBK3Wnw3BNWKj51to0T%2BdX3Dt08SP2Nifgz8x3hOOy\
        8l1A4x%2BvCOa6bRGawy9wUvSVaNK7dPnE8ZkSlibM1oscj%2FlUO3dJBArRqNz5x2fNrX%\
        2B8BFvXe6tFmR9ngZEvyZaPP%2BmwJ3Y5LAgaTtebL9DywRscZXXQHiq1YFmLpHLh%2F%2B\
        hipJsDnxXDDi7MG9BjqkAek5%2F5FA4z9dgjB1tPLRZoYEVsZih0OS7qgqIvYftE1Op1712\
        WEL9v8eY%2FF%2Fm4yjeng%2FYc7NVQqmy%2B8LfkTolsGnL4Y056g9rGUnM9oumg3aT8VK\
        BUNbe8snUT3IElhcCwpcgs8r1GY93ujZdqzlr4OftZYVre75jQGTIgzlzFowP6DJ%2FRcbk\
        uWEW1x%2F8yBjvqIAE6hvj9iNMLu53zc%2FRtlCv2pc&X-Amz-Signature=dbd016998b6\
        9f2939d7e6d4f7396de77adcda7f802a87b78beee7b020c14d109&X-Amz-SignedHeade\
        rs=host&x-id=GetObject"
      expiry_time: "2025-02-15T13:39:38.522Z"
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
UPDATE_TIME: "2025-02-15T12:41:09.190Z"
EXPIRY_TIME: "2025-02-15T13:40:53.357Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=26bc28d4817ba6f1e50a4050d9002cc6b5aeebb5e40266b9d9c56462f077f61a&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=0dc922160917991bf86fe39e8ef6c5921a76a9b3c5d6728e4555dbb2a62a8fb5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=d5e02649692064dc5e1e5eed409233e7ec8540b0724d871953817b32ece1df8d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=cce6cfa44fa31461ed45e0a59f8e8eeeec35203f7a6469bb5a2001b33ceda5ee&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=c7588d08f2bf595ced11dd68466ad38ccb38c1f9116df0672a63a1b46c69e549&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662YNNV6LV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124054Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCID5Dmfb6we6WpoCiDEYGYTo%2BSLurdx82HdWgNT08XjF8AiEA85KCJC4ogQ6c8lZV8L%2Fk740lN7EN0X1%2Bmdx8IfPV3H8q%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDF5gaIAiRvBYUuZwDCrcAyqupHdG%2FRc1iZRp8dn34s%2F3xbCirHyGKLL6pB4z0toTfrIcV5djsldKjzvU8GPXuDc10U22IUzeRDJb4KF6l9F%2FT4b3QG2HVphiA8kwlWcCFyb6f004BAHDF4BP7VBcWsKFVZL4QpyZve73vDy0DHNk3MrmTHWn6VZG1VYZOYW8XZYoWkioAF9EirjCfs%2FvCLx8ZcXNkM2bU0%2Bvjje%2F8uFJ8%2B1QKUDtozCkUBOLVGeIPT%2BQ7zWANDZSjFXLo1hKL%2FELtsyN9zS1HaEb1lRzaZlQKTM6ry0I1knzt5T3VmB5ExkWS27Q2mv4YA2zphJsNoGUMkZdMcthfzLw4llizCsEYzDIhk1Gn6PovpcYsgcfQ91rE2kNzwdfBP8i6bpLUs0mDp1M%2Bs7dkLqJWItCTCspVuJxlOpnW%2BkoIpkq%2Fwd0mxrbX70e1aWVdOchCTmRE3lsqkeA5Njwu8CSxIkYLAOb4hzd7OYQ3py3Ii%2F3d6IqQ%2B%2FGkosfJcIfEqSwNIEgeMUPDZjvW0XET1ddVFLeYGiXNDftRjtePgZVHEWfbUNP8atLbz6JnFuh5xhkMLS9%2BfDCzlUeru%2FBVggb0oEs9pwwW8WiKD3BnWeBuxSVFALLICYfpjJ1%2FpXAIveTMPTtwb0GOqUBinSsQCEW4cHdWmuspq7ktbPgqK2BLlL%2FAJRfI5drgzOw5mqX4ps%2BjgnZJ6tElGjMfwf8%2BP0LLjZdEQ0DtUHx75%2BKy7MEQQINAX21%2BA%2BH%2FA3lE%2F7v4x50pVSyqDTEU2kkRytJk1WugAU5MyrJ82%2BnIfmKE2yIEHTfYQxOaCT6l6mmNzLZGOiL%2F8OwSDW0KzNX%2BOdtXYhPBYq9gxrLRH2n9YlyOuLS&X-Amz-Signature=6854d9f531da32e657fee59ad312c389ff6cbb3c26d1dfc14064ddf178554205&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NVPS2Q4%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124104Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJIMEYCIQCc8gxBy%2B7RzIJnVozD9vlqovU2N2Sdjt9bkvMw%2FWqppgIhAJ3SmmyqKqVst2TF%2BHiYO%2Bf3CaLxCcXaunuSXZqOLRZkKv8DCEQQABoMNjM3NDIzMTgzODA1Igz1AvCKitQvoGoglCAq3AMFL9hnznCqWsn4L%2BWRUmyNs%2Fc%2FoWmWurxtz4JFbierIGEdfG59Eti87uRyjqqIVq9NZKQo2ybImUg5b3%2BFFIjjJtdA9xs6XUBGkWL0oFP848cFn92mo2XaIQJhol4rOapYlEsL5dDW37v0wgrpkzNDAOL6b%2FCLOyht3PrV92C7vN%2BjOs3GLDyzVLlUNNl%2FErkYd6XWwA0Vk6smyKCI8OGiKMI2BYcb5O7jyEHu90zCDxTV4m6Xe7gAODiZ3RbGgbChbONMko5tqcpc3gF2rn85qPt5ZgspsUwifO2YOqnAcwo2E%2FUxmTy8uOrmasP75DPg79Cq1XHv4m%2BbfyJegsPKfiroKEwmegALc%2BTnKtXQ%2BN%2FKnCjJodtlmqUNzbpd49nV6gz%2B9j0AmW6ftJv3uojOh%2FPXvYRhiMEcLZHF%2FI0Xwo01AvwcSzDs%2FPFD8cepf98N%2Bcs%2BK%2F92XbpkYPXOgRXjxp7X2ciDOAxAHv48ObOqC9pJn%2B4NxXq5W2k3gYcHYMU09OTh7itQtAdMJMsKPD0BUoFsmEFv9YIusvI1XE6vTXyQ1ZViWaiHWFA19x757ZSmRuH5%2FSzGILqKe5c462IsaeLMZB6IzszhZNuxTgr%2Fuc5kVKW298zTjYCgkzCJ7cG9BjqkAfFueZ8V1de3UC0k7au18iJ9Cepq00dQNcfrBkvuOqQ2Geg4BrS4u8Nf9dmnwz1XvR%2FahbFZXwHQf8ScUc8Pq2Cba0%2F%2BoflP%2Fw8AuCyOLUOwF%2Bu9Ui9YoFoSTRaPO7NFdtJ71vaUkG5xax6alNE%2F1HRz6EqmtyQFC92cnHq9HReTOlmm%2FvNnngQnn9IiTtfPXRewz%2F8C15E1QrdLZpUlaEJr7ht0&X-Amz-Signature=3c929fa79999c76e854246b4401168e31081da2f764037dc02b7c5c4a8a57e07&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=7e8bf22dcea64094efd85532b1775447f5bc039468cfe6c70cde3d0d08fd6aa2&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=956f26903b1f843df398e6744e122af484aa503b7fe5f27aa5a8690ee4740cc6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46662OQH2RV%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T124053Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBsaCXVzLXdlc3QtMiJHMEUCIGJRf%2B3TK2a8yiJQc6EQnKtf1LUVT%2B21LtLrozsPE4SWAiEAwYyIacTJ%2FVlChs%2BQLjjiyEFxYFOa78K91zV1zUWhX8sq%2FwMIRBAAGgw2Mzc0MjMxODM4MDUiDOwxExxtGb5Zs9HmqircA61dOmeBvZkZPmC%2BoCou37OGTO6fo2povblE40ejRqrTH1seGDjLF%2FAhwPQPcTT%2FAX5N6xkd6drPbbuFVKZVja2f8UYkp75zbQNFTtMSxyrQ9wK0hKVaZsn2yS%2Ftf%2BixQYUbkSVjWwRTm%2BcT6WuW%2BM19QHRW3gCWR2cF9DyQX6RBwg9LRe%2BHMlGDDvHLkJJluSrXHMao1N5qpAF0glS4t1Z8RtdOjzEGqX%2BUKc%2BAVgZSrOTswAo0wxompZ7tTleahtVa0sPaIL5Nf5fY%2FRx0VEZI8y8C0w220acbOcoxFoQLcfCzbSWG5t6HS2l%2B3MFy9phvqlWmR0s3JATE8l9snmVcPGbq%2Fp1rqzgcTHA2GhX%2FlLMPb3QEB9VSGfOI2jZK3svlwbb%2F6MT%2BAsoGAoMGmLJBPzI3eFraUeqvryN%2BEIDXJ%2BZpTSXjdOUqdihg%2BQ7RejJX%2FKSzgzNV4eCKyfX9mSqD4xBLNm6PDAFZDluV4ea5WG%2FxnWKqXgnwL4SM8GPTAhjZZ57cNSEUOd1svcTrhwxaNbFhhOZ3PxXV5IWCurOU7nizFvvlfGEvh9P%2FiALUeaPonTUzys%2FQ%2BW8%2FR2NLEyQb%2B7CKTqiHVYU8naylRlvjEfgiyCeGxac7WVhlMPXtwb0GOqUBGWJ7ydr%2F%2BosPqeDvKeMzkRbYx0N2KMhUr%2BxyZKRxunpBkhZ2MSGZ949ojy7jfiq7SUrijeckFl1RD98LVz4blLpOCG7Ja7QwoSyYMNEstL6c6RAZLIIf0e8KsLEFD92vvJajGfGERzAjefKlLK2fxsIsa%2FhNKiCB1SoufcId7ve4QiC3xZbrVF6QCbi5alrZM9R8NyVyLjhS1hEAhcaGsAq1ZtCE&X-Amz-Signature=54858794ab54fa92c133b24c7c3674abbd52b5cff67a20a3f57125fa82ff5e58&X-Amz-SignedHeaders=host&x-id=GetObject)


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

