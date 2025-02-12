---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46666LSMOYB%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T202527Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAb%2B4blzIFxrM4FAi\
  wu11iGGvRZeK4GieTcqiC4dxrK9AiAa9WB9%2FmWlrVSrsrW7ige8EBzwyzOjhZwHL5CgrBiDQiqI\
  BAj1%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMkjQZHgEIoBZUnnLFK\
  twDJ2ZnBP9UW%2BzI5tydVlWJWWir8QurOqYVehsL1uikIgPxNjVMzXYSQfVXBgoEmzXbl22%2Fxr\
  gSemNZTMkj8zHx8eW3SAb6Sivsh7LST1B2q8yfnvbV8tjdWgmzzLJ42nxWS1fS0hR3fWYkR6p00On\
  YeSbsEP7xaWWtT%2FaXAIIOyXy6%2FOHkvNv%2BNJkjItiemgfMg8WTI6rhNG%2FOfRsy6JsRDSOj\
  Hq8FmbsqgDtS%2BXpGTsSeW%2B78SZPsjnSQu1qO6RBXjcixrkIj3sKMb%2Bhu50RC7cVLzkvHxW8\
  qnx9qzH97BXPjZj8UdpPx4jRgC6vCIsu3D9MehM08He85ltjk1HlT5ttHk%2FG0R2WJGLDSYJurna\
  CJA9ow2%2BW87GfAumWK8zkCge58XWgRen%2Fo%2BVO0pk0KgrbCfUIUfL2kQ%2BZcmp0UROigQYQ\
  NoX%2FIIQx6dy4CZEXxFqk9BqlM1AEQJLXyigdWo4yTTWftXKF0HtnJH2k9Lw8Gb8RSKWZ0v52DtE\
  q%2B7UqYYHpcgB0f7gZrzIIf3lt7xKuc0g3qPzw1ne%2BclDdF4ik7%2BhpZLUNmJ%2F5CmJpiuGR\
  s9vfYTSP2kVuJjVjoczfbsXTFFELMHm%2FNWSaRQbu%2Br79qqCCIBi1PSE6UGAAw%2BfKzvQY6pg\
  H5AqpdvYTrS9R8ibRBvEivCE%2Bq22MM%2FqeycbF3cSh8r7eebt2Zphga7WGfccFRxucIKl10kZq\
  hedrT3xePlsX1OPQD1Y1tCmxumlu01sQCaFGrQL6XgZoQGpOFPk6x7gH3EESQt8T1NUygV%2BNFoE\
  N5eWjtHtfI5S%2FBFQBSnrmCtiDiETfziFCazoxflppfAf2%2BqNzE5olFaOtlboO9%2BeyHpvO09\
  3jc&X-Amz-Signature=f3503b2c46522560704d20ec475f50eb676351c70c0939f300c67383a\
  838c63a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466427BD4VX%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T202407Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDfK2ok%2B2fz5XPmACmaGN2BfjLWMyHU6GCFET%2F4HZHwvQIgNJ5IfeTCxlgfKeqdyj\
        ULYBb5g8QXUTLX%2FRu0rhwL05IqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw\
        2Mzc0MjMxODM4MDUiDEODYN3Zn0C7DrxZJyrcA1G3g1QCKEnd7gzd%2BClsHXYGxa7DxK8P\
        %2FTwn6CGygTSNwQtBDX4vrtTTgN1PrwFtg9dchzGLkTdBVGNUWDgtu2dJT8u5ORefhgW5M\
        MKMVUlP83pLGE7BomZXv9IacFQ7bVuRqNBrjg08cSmcim9LYlaAPFH1FrSGC%2BXjZwUdmL\
        umRfnlOOsaL4gtbIzPz5SrlgheVNU3zxk06Q5SRHWtQjyvmZHUqTCCe7PmumKxkbwjgyHmT\
        p6crz4JSUyfzMvQlmcxiGOCF%2B8vA7k8u2AKuteVb3S%2BS1kSn34ccfO6tPCorYKe6GVR\
        Bvqme3P2tewnT7PX3mUg2WgPw%2B3z0Z92FG0Z61WYhW4qvdYseEuYPUPySCKaM2N10HSag\
        3J%2BeIEUrRKQL8AIjRV2cP1SLPZlOo6UFicwtjjNzsaws5T0Ba4R8EENTQjpLquHMEKd0i\
        VUh%2FRMG%2BVNtfFpYvupGaDfNJVJUkdiNwQeCWSuEk4jmmiwG8fdFM1lvAacdLcc7K%2F\
        ZvaKCbp2YiRDDHLs%2FFGmdw%2BX0ZTjJkDy5b61hEdQ9VDpcdowfNIq3f71w6VTfx%2FAH\
        4p4Fp1CKOYlP8UiLxobA4X80n8HR8zP6LA6akRRoYoBS2QMs%2BIGLpoEB3j45MPzzs70GO\
        qUBp0lR5hrn2TVR04dC%2BsOP1ei6%2B3AM9T4C%2BU81usH%2FZFyKoKfSoNd795mM9zm9\
        DidMtrCqvOc6Lies%2Bsqdu9X0agprBiyDeu4dBupmGNKxL81VUdBqIo5Gqzo6JV8JaTi6p\
        kwTDGNhLHFT6%2B7Fv%2FtJmVqR%2B9YjEv%2FOTGWzGmCypglba4wjJAUixAaZpcZxuD3o\
        sOSCHVWgvJCmHCMlbP%2FdLLqFuTFw&X-Amz-Signature=a18bb92d573365912459a483\
        8c3fc2d63b4c7175b9ec2b97f863450f30d753a1&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-12T21:24:07.762Z"
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
UPDATE_TIME: "2025-02-12T20:25:37.596Z"
EXPIRY_TIME: "2025-02-12T21:25:23.141Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=41e6921accba2086e8bb57515ad064b98f01b0c8670a2fbb40444bc410575bc7&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=165d88bbd6002ce919035d3031ccdf6e19a9e7c69c0f4cc8bcfcf17fa6e7c7a4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=6898bb225208922317d396e9f5974a2b28f24c2f98247b91b31ce6d00d7a63e1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=2aca177dfcf2d1c7fd7241d53eea152972336114da4a50eafdb29d06ffa70387&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=7c5ce89a72827fedc68fd6df834257c583db24d15b85b4eeddf1817ebcf380bc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZT7KO5KT%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202524Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIH8Wgo%2Biy9EQ%2BZO7ylOa%2Fvg5f59xNahYaYzAJH5nMXtZAiEAjgtHyFfNKBoTwQD1oI6vXTuBizCrOrD15Kjpmb8T0xkqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIpW93Ye%2BybPoyzTCyrcA1gVZXjacoSaLj5i6CbPaZtWldXCqFwtv18G9qBNNVoRBzoJ0T3HwU%2B2nz7NlTvsEaBzZmiU%2FP%2F3%2BTl%2Fhg7m3nFgxukWsKCbs7G%2BVdihcRFE6167GRlVuIUNHNhKOP3XTXuaC30EEBsbITnJ9TzSbDT82yjC60PRCpPGPXlI5O4bs4PynQwSfn%2F1gK9batKNFd5SUeaiTn6PWwIHVQiZbczfEYbvRlHDQ6MoLjLpanb3QyYYAsoCqPX7sJsZyl6FxX4j8yy4cuTPwWQ%2FBVzMxGamwq3bQBccHO4RlrOXVg0JlRKFDediiyIkZDzOHOtnElLzkHf6U7EnMzAO7UC8DqN3GH5E%2B%2FBiSX5NcEh25cmziqU5y%2FxnmQUZWKbEFKxZSv8TtaCy34OFJ5X0YeuU9PZqHur762u45y12QVID%2B6NRRGK9zpQq5XcWZcKFlDcOr%2BGrmqZvx2040c2AL6qW1piA4wC6iygxPtyiugyAQ1LiQPyzvxo5o09aH994Se9i%2F0XkLxy23pUkUYCzR%2BaqV09DnuhylpZ0K0wDwYuP%2FhIyAZk%2BD3Y%2F960nGIiCSjGMcL1GAkNNvNyP%2BhOj1QhpsmtXyLTh7gJc7NLUi8C1KN6Rq39XegFXt%2B5ARWxFMNDzs70GOqUBQ%2B%2BkS3Nq76tB4aB%2FRhLzufv0fjouG4WPDjWmTe8B1bXNJ0mCBSTuTdVfdXKEI%2BBXAluhr%2BAdrnLcNoQ6e4o8%2FcoPyMvYpnigk64qcPBRfSSgBW4sLgsr0Z%2BJHSfzJD4HA6Z%2FaggDcdlN1JOpFtaW7CM8i7aUuisue%2FIMHqfwaM5QxR8nI1qUeqQ5Pr%2FJRClEYTs%2B1Cp7R5R%2BZqyNdBEjYWLlXcA0&X-Amz-Signature=7f08e76b9db466ebf2f220205c4edeec8542ef022befa05f4dd84eb5b81e24ae&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QSA5QGOJ%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202525Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIB8HuWM7JLh9rDqMHXp4r4UZTPu8D4EMgZuutoh5vy%2FZAiEA7b9xitkYIYCvm2tO7J%2BQlVfp9IuwtMqQtnAb0fGx%2FbkqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKpI2mQkk8RKexKk5ircA80r3NmPaPytgo7mmZE8ou3iHpbQIw516NllHE7TJhEpkntppDH3Hp6itz7KT8J%2BgWeZaxq7d3%2B36wp2MMCW6SFiU4%2Fe54seEGXive4ZwFlSc1oQAinQenRlnHZvVWBSFi6ucLqYshEUiXLWiN5u%2B5Lv6eOvdoB6FBrKfKoF4d71b4Hq023pbu9oBjyNIxp4QbdXAQDOHcHjLFhpKD62mVEq8IXoPSpAVpuYZjd2gjIhkeI%2FdCghIVDrS9%2Fgd4BrYywwbe8scuvHYPEitEQRq%2BzidZ81nQfc4Puc8pjbJzAElM6asISOu%2FJ7Trd9ov0sr2iTSoS1p7yIjZyhpf7M%2Bc94KWZYRlTi5dcxAtSGiGRgFsm8dcbQtjD8S%2F7PGAEwenssCXJDAzW1m7YIbvnBEmYyY7vlOhNsSWF8efFDCOLmBWSotF8pu3eO2LsiiqnnZCLHGifTFNmIw%2BxC5XNMz4uGp79l%2BEiptvdXf7r9svxSBunE0JVqluLDywgrvV2JyZYURto3U7pW6692PD5wXnXlwLxmByja9yt3oC8FqeBdF68J2m2Aqy966AbIw4nXkYwKT2YefuDGAZjRuuJLuLJsPiZlI%2FDftqEWK0yRMunw8g9fr70DyodYgrD%2FMP7ys70GOqUBhzBm%2FswT1AZv84qIVrYWKts%2BJvYLBz2fKaMmcAqw4t6D94VSwXaXhTgr13OIuxaGfc0Mg9hOGtQeEWU1U45YEoVLjW6AWkiw%2B27XwCpZE25QoXzFnmyPptPXrcn6IASd9WZQiqd06%2But%2BywHevAfaG4UWP37tpfr64Esr7iJTnWx4JA1T7AV%2BROKXjuHfhckcgDwJQNnH0tM4xE0rz4Aw8X28R%2B1&X-Amz-Signature=65745b853911b86bb654a6b1b48374c3cc168425f77f5873c26bd8e774b4bef5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=209cf6f3644a4e64f6a186eff1232a58c15d764dd6666b40071ad71bcf558fdd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=4d6ebb6601e4084b13ccd6a5f76c62a6ebf4cfc263ab8d27ec9d765697f0863d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T6TKLUW7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T202523Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD4Ybquonq3FRNvjzaFLyrEGzNiwgvusWe2G77sSTOxsQIgOzYHJCMJA%2BGYITos4gmvLrkNbgrvzPlmPdTbLkBVx%2BIqiAQI9f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDLDoAPMZzkX4SGAg3SrcA%2FPG8OSx33RiLenCMSnZArWCup4uopKdZuspqyr12rtmurtD7m1v%2FB3CV56HQUYtYbeBtoTdv1zcSWlVmun06UuNDiVQabZCW0JmZ38w6XPpjJd1jwAM3xhs8UsbtV7%2Bdai5kWxeVp964Dp0nlDq%2BYQ9Gy1ij0ItRAYeAGEsuICMss5AiW4KCdFCvHsfPS75gUv0wtMGwc6ShYTSLiKiwleBjaaUqBlrWlN2Mrd1RQL2qWTQnjtwp1zjrTeXJhIQRm8T7H1kEkSQLIABMU%2Fqfq1uB%2FU%2BmFKre%2FdAqFE1kDDCPqElIDW9pGMuPR4RMtazvvS7sLBOSFwbWKXm6gKAlrSCizD8f9lYnKYv4wegxWUWTfrE4hu0%2BjHle7yX759uRjt4Ux28hjjKKOc7TQSeWGIcMDJ0XnWWbKqtei0PphjAfO2kV19KV1rRJjZ20K0CBlC%2BdWxOVIujqzdWY44Ee4bZWPTkYxRn1kSASwCSAgjClmesGU3Y3wv8TcgibvXeoD0xxgdUMyf8IxfStlI7VpP%2BSKNLs482gpTodWgo%2BxyRc0gMD6fowrH%2Fzk%2BbONOn5U7rWB22DQB3abAEYzyd3DzYUom0OLVu%2BGNeznXkvdqFFMDLNDGEgZEuOsGGMJrzs70GOqUBhMGi6Vzgbts3nBVibw4qoHttpJ0cMHWs%2BpBB2r8oTHfrkqdRjJWXEeaZSzEm6%2BGxBeIof0MldHqXQjQkdZMDTMn36hrK5HHLwz%2BwCMMQI8wShAH9iTFtTVUtAybdJqT6QsO9351GrezY4gUPjvmEr8bVeqQ10t4tHUE2gCFb2N4h5Rk0EruxjTuwIUMdc35XAi874FtXvJpkdnu%2Fig1iKvD35zVq&X-Amz-Signature=3017cc72a1d3d4419382d8d5479f0234a71e709e0f22bd4956b06456a5cdce64&X-Amz-SignedHeaders=host&x-id=GetObject)


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

