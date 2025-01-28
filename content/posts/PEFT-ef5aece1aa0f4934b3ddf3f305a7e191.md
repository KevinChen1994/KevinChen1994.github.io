---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46667L7WMC6%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250128T202431Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHQaCXVzLXdlc3QtMiJHMEUCIC4uMV%2BipseICL7AizuwP4f5CqX0PWcfrVjwfmG9kAOJAiEAy\
  QnLwrlp9zvHTRN%2BgfKt0zzZoJ8F9qA9rqxvWnWKe2wq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDE\
  QyrbWrwJm9p5T4fSrcAwje%2FlpX6YdrZ6LBLf%2ByMBhd10yBeG0CB613du5C80lQkBtQTaU9anO\
  6k%2FvWSajEq0KNmKZ3m9KIlyGw6jgOsMRJsUEm0eMiEf0tUKR5GkVaHWcKkDV9njqI7fHHizPugi\
  bjNS%2F3AWwWDe0UT6DOrUNVc4hVhVFJFxfCpBSS8tgYfVl%2BMvHAWlaaACai3LcxZIhEMOplwwu\
  aY3axO2tQFH3KKzPyXNDr4O%2B5ikiKOrU4oyDLj5wMQwFIreW0I0X4OTa1X3LoYyGINIMpQmpIJv\
  3E9oiAfIkjjH5US%2BrQ%2BDrH2qmZAPDg1OrI9ui%2F6UFgnpKDHqTmPPfsJXl6N83zwJfENASD9\
  KwKyjL12vBJNh7OAyrEZdGWtRGxakph6nuZAol2NfqDwmaqFq4AtJq6p7rHTpGT9mJG6sdlfc%2F0\
  sGMXSm%2Fsi9DxhIINqLhIt8nbieNdL0TK3ePuzYlIaNT3bv0ZuEtcqHWiyBB9oWVWzcuSLFD8TWo\
  HKynr8i8wwEgjWqnAQTcwMZGfi1vZJEYLlLv8D4Ssl2%2BAZKY%2FCwH3xf5Fy9z4jWWT3VzCrUhH\
  qyK9%2BSb5V%2BkzDzWspgWTl3Wn0geAtp1RPp%2F838eUO8CWvAQpEnmNatu3HBeuatzGMPnp5Lw\
  GOqUBcGsl3yQzFkphSrqUAnfeXs8kPehqRhS8MA5%2BOUnvBnthw7CS8cEMIGVVW2UQpIhjiKWJf9\
  30fw%2F7HzS%2FYoYcrDGR4%2F4SvbEgIrp23MK2G5lbO%2FJy41YkLgxHdZyW2%2FsQOH8rv3u3d\
  82xJMTTQynuqZAWx4vA8dwZ3UFIgHupfgmjuFX4Pl3sO8hk%2Fv2KfULdF8PilrDZGy1TNKQJP7Gp\
  BHg2Q9jY&X-Amz-Signature=063b7c16c8f51f4e195113cfd19271a58108582a9c7a48b064f4\
  f0bbb17790f8&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46673NVZAUG%2F20250128%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250128T202310Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIF2irmPp6ngdNk%2Byefy6OTgiEPwg9\
        weBzh02lGVV1CLfAiEA7RvPrISn7hNj7nZdcSe5UyXLvO1fnZkR5ucF0wet5QMq%2FwMIfR\
        AAGgw2Mzc0MjMxODM4MDUiDJOj6Oef0YJBfsnT1CrcA1RfyryL%2B8l7Qpk1zx0IM2%2F44\
        1Slw5QUzp%2F0vU4c7TYo2ibVO8QOcMMIAOy9DWetuaJ3j9ip3XcOUs1FB9oCP1487E%2Be\
        AE3QM9qLN85aRSHuYDnth4LE2rR%2BM82YeCK89N9X4kazkgxmTTWDMq2Swv8L%2FOmo0QI\
        tlrl9mgJfh0RH7Vi25rNnsqsNJJrd%2FnH9Ow58QxPVs1B0YWEwa3EuoxWgpkN7n6NOaj47\
        %2Bv4lcmA8KoIvWbV29vCQQvIK2YOvHVzCR98%2BLWDnoVNWEzwthg2YdKOet6xTN81glef\
        MfeO8xAaXXfghFFsC%2FgN5jlhi1J1RqN3aW7ty4NOUKDlui4BmhPnS3R7%2Bm4DsQFgYCW\
        TW%2Feg%2BEVzN%2FwSf1RFMPjsI5D2IDM9nqx50LFITstAMdQLPLOk5%2BGivNwxEVpWsu\
        0nMEl3wu8SE3SAdyFqjOuLexvaEuoWXzHh0XZVC5vNUtHXYSym4QnWq2QxnEygCA4lD5pO1\
        1%2FedIjmVHJskI7y%2BAY03jtFJfGQN%2FL27mskVFh%2FwRVcOs0AbrkDkMcITapLgV9C\
        LATdZcOYioddcE6Ig1C%2Bk%2B9JQ0L1XHzt%2F7T1P7Am0Yma4RMgRz8M27GBTdaO%2B3Q\
        saQob7tQr0QQASMN7f5LwGOqUBxZ682jWL9WLKyuB81uRUZx1HUT4ZmNcLegFYpfGUNId07\
        Mrl0OjrgyVFQYnveaz%2Fnkbmx%2Bmo3l3ohSzElGApfHBuHcGnaKJqCG6WNI6KQMteOkGD\
        nBK90R5b6hDzbpEn90tQVRoEp%2BdNTK1wx%2FGnIMXz%2BCxKGPUrEyUxaOhFa3gA%2BT2\
        JDv6%2BRAOoJr8%2B0PiXxSOWRBDDGE8wkjwJKbk9Sk3A2Rq4&X-Amz-Signature=0494c\
        1674a4467f9c5a3f3f28b9dba58fcecbb00ec04981ce5f30de7f4bd2a0e&X-Amz-Signe\
        dHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-28T21:23:10.626Z"
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
UPDATE_TIME: "2025-01-28T20:24:39.200Z"
EXPIRY_TIME: "2025-01-28T21:24:29.640Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=303a77a7d92856f08c881d0f22b314ac04183d32fd52ce2f9b412980ca8ae55c&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=98f622bbaa5f4bdbb5224ec46ab7c8f7fc6fbd25e29f9017e5ceae4901ee6261&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=cf82fa2c4dcd59a4af1348fd1ef191f66139fbd5fbe73b0fdf9f66235e84683b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=c8fd7b3718cfa4e0fe23a03b2ff8725e4542b4f99ef5815cbf7071ce364c87a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=9b9c82ea0373e92752164a4fa5ca7607a140b42300a0e9318ed89a31a7e6dc96&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662LLWC47R%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202430Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJGMEQCIBkqW%2FNdtGLGOoHdCogrfw%2FJCHNRPkgO7Y%2Bdineyno9LAiBSWdusIVqHbWI%2FpM9GUBPEnb5KJdqvxAF%2Bg0Hj6VShQyr%2FAwh9EAAaDDYzNzQyMzE4MzgwNSIMVCMmsZd%2BiRdmjh%2FuKtwDVde6nyGk6xSfuF3qrPHfr5HV5LGYdlZU%2FdphidLQ6kmvWeGG7CG1Ds90WOcx46mwW8FsWj4iI0v02PYX%2FoimfBfqwqeol87LnqH0wOIY1us2KPlDQ3wjuEsVHJfYKNCcmgzHR1Q9cFiAOWJahQIRuN0smsxPWrhnMWOHQkdmMktl0kb4vRqQzWZvjN3W2rrSLyFWnNiL8oYJnBFawOARRw8VG6Yk0K7guBDgID7j7E6V8CaI7UuBLXBINN5bo0gXmjMam3KrgjiFwuV2Fm8k%2FiOUmUvGqS56Hoz3tPArova1UMIb9g8zQDE69L1uYFmc4JaiPgx1F%2FBu0X2RpnmyOsCBmeaYkK9GTh9OMxHrmbBPGRbGGIbZ5DSDov%2BeHP%2BWD1%2BUEkspbhOvt8TRZN721Lqv6%2BcAh5lwS4e7w%2BDlVzqGqMHlly0y660sXaiI1PN1c9LeDVCOSLszfDkZ699kVPlB86GkB1PQtJINm6L6QAwmpD3uej20bmUTllSJx36B1MWrkfG1x4WhJHXQhUE%2FZBusYUHj7PdWZAXHt76HZqRcPkPL47oCnAS%2FkR5ykOPXCFzpNi6IYxRAaaTAqJ0oah7xfXO1NsCjiczT1hsbA3zoBsbtJXwzCRFBVOcwxenkvAY6pgFQec%2BTXYCU8hBuv9pHCMP%2BCmvrE%2BnrnnQ%2BhKqz6KQEiOv4nOskI%2BgoqYYjCnSuwcw5rRI7X0wT2KsoNybjSiO1N7uJtNKMHLOXS%2F2vns1jIX9KOe0oLKau9roKU8arcLDTWKqt1AnuUj0mZO84bSGpRpNl7YoGTaafIlZLUD1fPfy2zaa2dk3pB31eEr9AWguNQVmeSPwgJ51K0NZUitUdAPOTS%2F5I&X-Amz-Signature=690d7e2442ed1354e78a631df6b80117c8c1c74357b0e6510790648b908982c2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667OPJWKVR%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202431Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIQCMXD95hf441AOt18d7iAVkip3t7dXBnKt9GPybiNqqXwIgQUvewTcQK6iAKGVdq4akH41w1az10JQUw2emBM1fkWgq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDGxOJ%2BPZT0Skdz9nkircA%2BiXP%2BDRAIgRfveT76Wo4BTiLsU5jd1poZ5kuDcX9Y3qM4AxJXzzhQDGnXAfasppAmOMXjeFUlcc8hzPLjRSOgHnIrBAbRVTolA1O0p07TvVYCx%2FpkwNf9cMGG%2FrOnpoC5%2BypUsNYVD00KHiyWdnyIqYs549hLSAekQjFKSrgvyWFXU4erW3%2BNM2BOyXocqpipK%2B4ckzDo%2B44cm9bhyCnVngl73z%2B5Sz9cVgb7j9kktG2fdREPtBRbFZKSG9QioQeYCcMozKTiXG4LaHaON2ekplVMnD2gbeeckQbYfxmoagOymhTr6GjkO1L%2BrMLjStv7eWwEa7z8zYEKZOX4E%2F4hxNXTt9YU9hs8PqJKj3V0o36RplR2%2Fj53Zy55HyZLTwTiLLNhKASfLvmlS5TJ1RlULKJuzD%2BYLaGpVhHonvMFu88yrC%2FIKw4Tv%2FqBZVxvw54uKcP4cL%2FLB9H3tYg3Qa%2FC75sUeaMio5DX8dZbSz4DPXpiZP2qx3L08gsrlwGPsCxdRDtjAR1KYsCsS9i752nbKguR4fNxm2u2QCXS5Mo0XNDy1zmksEcL0L%2FolVeDJdXmD6ZoKrTnfbnCshGpZZeUM6WvHn7RjVogeXJPReKzxHlTluReWFuCko%2BTV%2FMJHq5LwGOqUBOYSu19IZhC1XSirfHppyniQpY3BKmQd96hAp7VDTg9OLTBglpedcFGeQ1g15A8dVab5PfkzE9C92DAqunj%2FfUQamqnmtV8qAbNy1E9yQv57eKNJpq2g1e%2FYMVN8oy32%2FWfrzP%2BEYehv5iSE8J5Wu%2BIRk30EQhe7QGc7N%2BgzNp9fB97zercoeNUwawXU2NWSDrTv8iU7WsbJcoSir1ain%2FKWUSXDk&X-Amz-Signature=b52e12284b3bd64a4720f91adfc981e1654fe1f638f899e7f9e6933f0c3cc0e4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202430Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=3ae2dcc92fca5c61ea413379828bc25a5a1f5a97e24d2d17a6801bb7e2bc0574&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=d664c00797abd14d7c1090b88c5cc52eb517cc3a89cdbbfeb1cd28c6eb27ce2d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SFHV7VHM%2F20250128%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250128T202430Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIBRvps8qEtPs2imJhR5Br%2BiB6L67roU6pK4%2BpnwRyEGuAiEA5IewP2ldLsYySBEjteXlPMA1UqQ0fa5%2BlaKl9zQ8Q5oq%2FwMIfRAAGgw2Mzc0MjMxODM4MDUiDCnVDKO%2FWNBd8ggCfSrcAxN7TUGSC3HWNwucas76nYXhAt4KNdDBA0cvpBITdH3hrH8xuCic6j%2FZjzaGHht9rRVQY5YleQHgWrRlik2HUlmgzvmMeF%2FWsxGbKvXGsiwdb0v1e29K1oKGCq49obl8Jpxb7zVPQrtElM7xM46qgvnRYahsIQzB4eVyX8P9QBwuQOhh6EEaKXzvlBRt9bK7WNDdGhy0rdV2Gl7NjxxPN689bYU1xq4vewAUIbBM9XkQHxWq8472VJAG5WNtHMQjWOE%2FC%2B%2FYIRzlZ5B4bpDGqEi3tWrVb%2Ben6z%2BQ9bSgeH5C%2F9BKdDLM4UaJ9nf3ug7E3akwlHQKXwka171ZEwFt5p%2BSDyc4rmARbvCjaJsSD5yKZsyrewV131RMF8HLzD5ZTYMeBTmoN9W0rOgRhfjkg%2Fuu%2B3dyyUX%2FFuZxIVbPcPGsUfrENzScJROKy64NwebVEZVrg7qwPJYbgEcIfe1dnhX5wyukEJdiWu2olEWmSHpUSIfSDxGlhOzp7rXKAQKoLaLMpNh5n%2F4xeCaH%2FJ3Kiywa0QBp%2FJ%2BqGnX4kuGdNuxOSXrdzSlNB%2BlavvWCnLGrIwFtMDfodIsOXl9aMjWGmYZbZATkeR2WP1zBxgrJ1sQWPdq8EE%2FLjbvHBzKFMPPq5LwGOqUBrkK0MaxWY%2FypuF%2Bv0CUrc2%2Bx6wFHfF1ErJdJnszVfN%2B3sndmE5eHMyJd7T3M3HAFjNP8spcnzkaopDBJU%2FPL3Cnq0h2FH9r4dUXAVe%2BMTV42sGEkx8aBIfXNYrLscAv3KH2MuotDpe1E5%2BtJ9JW3xEGibD%2BIwHjuQ4Pf8zW%2FrlKaBH3T541RTKr8%2Ber8YXLI7vSiYu03hEH5c3rkmUnch%2BQh8%2Bsa&X-Amz-Signature=7ca897777b428cac235e0e3b4dfbb0c02572c53bfb3ebfed0ab50f64e2e17d46&X-Amz-SignedHeaders=host&x-id=GetObject)


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

