---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665SUA4LTT%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T063225Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIC9h9BdDa66SFobjnIb\
  T1N1%2BWhnxj2Ede8lU4mGBCzp1AiBi%2F3dNVrlXxB18iiD%2BIw2WyvAwiNKJ7afFGBl0oKCAci\
  qIBAjP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM0L%2BMMclA18avF\
  JR%2BKtwDMYlejIzy7hdO4zxMmsHYPMZFfON445CAgbvGI7AjkIO6XVeVE3vlJmUS5yonUsn4xbGQ\
  bZpdYxKbwWkRb7xozFBLVdSlDyNLSS0yhIiiqSA4YYUZ5NooxEZABJMiRoCY3RDS%2BPF%2BN6lEE\
  fy5Dlus%2FG0mBjII3oTEUkum2c4gGsheqfSFYlXTbgrSyYpK59EInGe0BAuk9p8V9Swpy98ln%2F\
  B5XYwTk27VFV6ss8LlDvm3WFhPo8mKCShs3gRz0TnR3IDdXN%2Bold8RDaz9Pr9njczYfgv7WTgpn\
  kiwVUAR8%2BO6wo6%2BVsJG%2FiqcB5hpyB9vH6W8OKWV2XAuKpop58zr%2FvWqckaoepPAsgfyMe\
  uEsLsF27j%2F1wC0zR2vKaSek7FSaObEsX8JleNfxDgEYJSpP946et%2FcSZ3nhf%2FFa1BDGNBxL\
  bNbMNF08HTXQRp4H0C1ZMxy5S52kGB6H6D1NonuSbxALPWTBSVSdWWBMEMBhc3DbjfUOLJIq0kXZ9\
  LGGg4WeMvX75pksQotE0FwKocxLDa9rTqyPUxolzf9S0v3mMwGG6JdJc81IPMZQidNzofLnSRCVra\
  WIjyDJW3%2FSiRzIQfChKAPt%2BYSmhiJ6oYiMoCqfJu%2B%2BOcLalv1O4Aw28mrvQY6pgG8y8q%\
  2Bmk2yyjnQy4BopONNraOSyMUTwkzJ7A11UWrVLdij%2FwNp4vlvt2IZy%2FQVBB%2BWOxPYYBgGK\
  AHiU%2Fmdy7olrfcJ%2Bph5fAVW7rv%2BZuSUgXIw8vXrW0iG5OBQgDo%2BFK5NF5QJfFslo47T%2\
  FJAXfjxgWGRzREAyMdKdIUPSY0BNzUK2dt1fnLnIbGYxbWMupju33nJFas8kUsVNXDTlqBl5kDzft\
  E9V&X-Amz-Signature=07726c38f97a763c52765d58a2a317333bd7bc0e0f15b57bdd6fcaedc\
  ca2f56b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46663OGAOKI%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T063106Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIFbiWP%2BZ%2Fk%2BQqXSaHPMKMpL7SooL19aUwnERAQM1Yb%2BGAiEAw1sBl%2BuGetRg\
        bNiiP30tKE1oRDW2intA2PV5D3BOOyYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FA\
        RAAGgw2Mzc0MjMxODM4MDUiDFow7STKT6GoCV0TjyrcA3s0hGlXUtk6LtU8SHdGMz8NcsmV\
        fOx6y09APAEukCC56hRVrT1CkVb5Wt6b4rXR%2BwlW4VRk5tvYwvUwaet0pCfi96mBdW7du\
        lis%2Bsk9aIiJgvXzNwB7e1jSVV60UI1jOQ07yPxlsAL0w853CRL3N6npaE1ZVHv0bi2%2B\
        UyFr%2BIbI2y%2FlUokQg9%2Fj%2F5ulh%2FEZ3Mfdrl3dU9ezp1B0YpWUUnKAlDSiefkeu\
        g%2Fmdq0aDXRGZIV8SVxlzKAEmwDXk63zZB3IDIxM%2FmpzjDA%2FBc3JdcveFC%2FFM9W1\
        %2Buo7TTqSfdApEuxBms18UlbGyHu3LoGJMJls90f%2FrK6e1taiNimcCHnKZ%2FDbH3FpE\
        Z3VU62FQ25Kbfj4jZS9XLlsXE9yK%2BFPIe6KwlKoCmIRWCOfTfJeGlLtC992Nyv2U96UsT\
        HcxJCIHE6IYsSP7wNfVGUZyp8fN0PuhkpocEjcaJD2C3a26kl7mk81FrBJAmBP6pkgOposb\
        AoIoaeXpdEBFm6sMGAASXddq6%2BfmwKCM8KnIy00TZOcN%2FT3O%2BAKFyFp5vvAGbt6M9\
        9kbKtk47Dgwh5WfM%2F2N7LzMTuN5bRJeSPzrgVneL4pGdbkuwEFEKcdP%2FRflBwFvlF6D\
        x0HYEibBUifMPTKq70GOqUBjocy314u5BJ8x6WtXX9wvjh5MIoscfmPPnpCIifNlYT5ve4f\
        G2%2FT3fSbuhHnHY0hX3yL9GqQ0XTU6P%2BcwrSU8hKURAfqbcaAQilQXPMtyhzNRD9UHan\
        JQjVcRGry4y6z0Taa6R4A9Kh7qUtLxf2BBtv%2BVy5%2FpjIw%2B3SLAPhsylFpH6S543Al\
        ODcjuLLS3vAGVEQYDJofTXM61%2BIAFuXOST6BtIiw&X-Amz-Signature=0fefd1975ffb\
        b6e633d5916755c25bb0de6b8eb226e91db792632268d703ab71&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-02-11T07:31:06.277Z"
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
UPDATE_TIME: "2025-02-11T06:32:38.971Z"
EXPIRY_TIME: "2025-02-11T07:32:21.078Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=fb7726d598424089927b06503ad464baf3fdfbe2dd7c608876acbd3b27ae78c0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=a3f0e80f478afa2df15442e3286e6ce74cee556f185c0aae1625aae9f5ef0bd6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=136d5e08052349899a44333893603d58b6386febd815408282caa578904a8572&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=bc54dec8b4dc54b634a9502c7ff3741eba4048c2624585d0a8e3e53defae7b30&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=00aaf92eafa95e607a61b2c858f8de92b0dd27442cb6383e5536826fa421f06f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WWOHMMMV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063223Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCobTBbOyIAbfZGSSP3AebEoss72ZDmwOmORuFb1kSCKAIgIcMbDw1r4d0jPjl0SFBcxgkZ6d00tJhY3uApILcaM%2BYqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDI60G1eRU7X5W56rAircA7Sff7pxJQ4gcj8LiY4dmTkKe60RBxyETOv4x4vDW7UoxLcNX8ygUiUvxE2brVdh%2BsvCXEqRAS89h3oMMuAIXzMB3k1jxPBSQRrA%2Fzag5A09Rvm%2FID60OiCk5Xxmbcuz28n96qeIQWKSYb3euucEJFMJW5E0p5d2%2FCd9XYn0HEBY3XMD7aurjMsVw36mPxwNtZzBp1IKoXZeQw2rPVlasXq7PksBVjiwCs5SXgiPTDA2RBi%2FbVpuQK3tIbxBEh6B4WHFzeIZs66iSQ%2Bjezl6%2BB3fpyMpLVI%2BHYx%2Fp87WSdAfKXEtv3ipq5ldPcozvKrfw0nZc%2FXIz%2BMcsY0FSyfYdnWJofcfpmDHC5LdwAhPMa77n9Qc4PeFOwPRvRUwVY814khf6q1AFU%2BR8j2l5pgK4tj5JeJPp%2Bs01cIP900J7DozEBWf1dsnbOMHnP5Qd55dDX2qv4kB%2B%2F4aslzaUuSNZGeM5w4qKDGjK9eg7c0phkJ0gYhh484eyeodP%2FYYEopUaNo17OBzzX%2BClpCvJVzr2O37kGf14wb6Fgr%2FJRZTi%2FWdSXcEU0JwX2QShHKjsxbOWQpmbFUcL2DuqOcU14S4z9T%2FIcbjqd6pJYfCFrEBgdovzwM0XWpUqLysN9NjMJfJq70GOqUBoKGppZwtoDrSwgfl9%2B1MNh8m9kI9MiKgyzt%2BHIq6MKHfgN5pUi0yO9s7vjj05horjATKKZRT9V0%2FimmYhZzJ0HxTeh7Gqw3yvu4e8oJNk9vz%2FzbI1bjTBRJNsNVs2ulnzO8wnNp4h1Tbv1JNAYldQh16n5pb2WwEY%2FMBk0yYLlpoRJhWZls6P21zc8VeaY3xW8McmiASJKOn1qRMoAO8unSpSxSF&X-Amz-Signature=a9d3a71a0dcc6f8465cd87e8f8167a5cd9905f89f3d924efd32ec2d6bed69dd1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z3DVC3L3%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063224Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDZFN2jshs48OLdpYfhwM9RokE1jYlxjGWQB8Eq8Bp%2BXgIhAOb9FbMpNtgRPEdp5XOaRIMPbZ4RJ%2F0LQ4GJXL8XvjG9KogECM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzTMczbC9muNfmT8v0q3ANKzOgWq6Vw8zP6acxHPFnjm7FYtDMxvGBuZuqTuK%2FiZ6yyGBC0c7m8H4EHoaTak2npBFAYB10Dwd1MUKO4tS95t1QSVQzWacPUIsX0VIFjttXvR%2BDCwnSYOlYysrWLByFL9HQC6lR2rsWa6xqBeKwQDJZUr10HnXxUk47AC5kAlyatdPq7eDU5mczhdmeFCr2zXlUb6J85PpjDdALvGexQhT32ggRWE8yt2SzpUTXBFAhcdle3Lk84gBJOhAra6ulxbJEFwnxvrWPbu0KQrC2UQZ%2BBjjX905P%2FbOHbgtgyiblsSh%2FfVOmPj%2BdUE5iM7RQs4fkgJxDuGdJ2Syn39KZtDQesvj3Zj1Q10%2FX3d6hFGJMEJ1%2Br30pgQkQRgo7qJhoxhdVwlYm67nVj08gFZzyzSyfdnCVr8rARGIe47T8tRrwLQkQ7Crl0ixd0wAUcCtpWQI4l6p6cU49tRQUzVn481GyXmgXNrD9KwRGBIqL%2BoFWN3ix0QSjZ%2FFhb6gUwNsaKuL%2FELg%2FmCvac7c98VGzLOpUuQ2Aycyb95guQho5TQOUawa1ehgaeMszhqUed8csWCCfZLYiQ%2FcidtNS8GVk1F9e2V6rii4eA53yzq5H3bwTDWPi0QyNifAlkUDDiyau9BjqkAfGf50bgBupYTCndVIp0FgwH%2Fs1WLolCdDa3KHg4eWW6Bsb1f64scfNj46nDynjMvr1EZcqCD4nD5gLTT59Cc8tPUC1L1LMSKM8xOyb9id4WdsTF8t6QQPH8pEPYBEwA%2BqcMX0IBvJX4K6Bhfyz182U0BuFLMgfxb6ZW5fqxVvQdcV%2Fh9FXT1SivtJ%2BG2uaGW2GQYC6aEBYYsV2IXr6Obj2lu0Oc&X-Amz-Signature=1993ff4e1a0ca3418fac764cec0530c2901b5f4a024cbf2c22976095caa4b8a1&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=06f1ed2e92a44850947bf6a175623c152a6662b01893807a7f871961bad41944&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=e75dae44e9837ee3f5b024c06e69ec0b3013ded4248fc37f384ecd8b2e831ab0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YEC6FSEV%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T063221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCelm2242%2B22C1H%2FkUG3ymQbkaaM25QqrY85nB8WdMpZwIgG65a8uVfedyRHPEHEVgMCAxk8AWH1mkMqZ0DjnVSdcUqiAQIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBvVVUoONkDYOj%2Bv2ircA%2Bx86opMCAzRSRUIVq7n3RVJ1x3eFAsgglnjLg6IzBadDh36pAkWPNh4VP1%2FrnGsHzgEQLTvLJE9LwQaVewfj9eqM8deDIqk8rtcHEZCDDKUMWL1HJv45%2FOAD42Q6kyUglgio%2BUxOxGaxHUKm08HZb5vfdYq5jES%2FDJIXuSfHxmDkAnz6e9ooGptFcORK1%2BTmL2mFiulwWhAun07JOVMHIOviJjdAGLz4O%2F2l6OuHrFlRTtvYnK9DOKxVZBB6qTmik2QsuC9eyBKPyw3mjAuNvvjhCPlcT3c96qLBbarDdWTfBN%2ByaTw6vP7OPrYBBgACO2DnWrUZpQcOOBZPKZiu2OitxEvR9RiLcus158Ghx1NavAMABrqX0VbWPSEhLUZG9c%2B5Jsla1bhHcq6RIRHMbwbCQhMF1kyyQ4kWnAGRyDGFiCxiF5ED0mwE%2BDou7kc8DjcVJyL3Ka3dhx2Old5dK08k5fg%2FpbLemCl7ljg86%2FqkinllcIK9X%2FOzLwJSLh8Ao6JdVPvKNgHB%2B657SXdZW4DzxsIkINcX3f5feqeGf88K%2BTPUdFsF8S5W3Pv%2BjUKwYMHXLTTJZeYa%2Fr0mekU1PvQcmgMYUeQqLIZX84NHcKVjsVvvEiTKfvBIGlkMKfJq70GOqUBiTUXkf6YyGWbo5n9RbK7GOrmceMD3J1RR5jrHem8mVJyBBMQnQs63WMPQFw4LCeDBWXVAHL6ZYpRqKhPTfYzGdA%2BFi6tK5l9HGOMMoaV3ddWtCiI6UGEZAhQC0viI1kbDyzzDtpJ0r%2BK3NRUX29TMis6qGgeDKZc9h4cJLD4cRJs2PyTIhRelecXLdudpU10KN1ZOTaaayeSdtKwV319zB6BXRyy&X-Amz-Signature=68145d8e978f190b2130896915dbe470f91278faa1d9cddf914b4a072e60dada&X-Amz-SignedHeaders=host&x-id=GetObject)


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

