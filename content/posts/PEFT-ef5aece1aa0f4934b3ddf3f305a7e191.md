---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XQ3IKU6B%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T023340Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECAaCXVzLXdlc3QtMiJIMEYCIQD7PkeNQYRmhnCsbFS9cHTZ6qoy%2FujUDnrastk3A4LArQIhA\
  NeMmbYGtl2HDkXrhwBFgvzvQeL%2Fv1bKXBNuUTndXQLEKv8DCDkQABoMNjM3NDIzMTgzODA1IgxN\
  Ljy1PYN1MqUm1DUq3AO1MPDEYQhH815dItAfecTsbiAj30CA9pLMU7nUYNj%2BUg7O66grjMPYEyx\
  iQ5TstFdYGM3HxN73ub4Ppd1%2FXPIdEbcx1iMi88796QbqnMxqjK4F0D6loyH5zZTL6lB8yQWI1A\
  gQgahAO7x3pRbEpizYkEeIXuHezRRFUCnj%2BHtG6%2F7J4aUf%2Fg8XaCGNl52aKscml2kRVk3W8\
  nnjaNtkbvEjV%2F8jlog2ku7mtvGoCvVS9fkhBn0Q5RoOwnqxF%2FhRGQJv3nGJq66N00X9a%2FqQ\
  9X9Nut8fHIZe8CtbwV0J5sIF1aRLkUXxZu9rCeVSSF8SdRmwDYaMScJiu2QCJ0yqfhcm8Eily8F%2\
  BWN2h5ZPZB%2F12ZMMmLuBNIW7liEps%2FBYlNFo6oJ2Y9vdQkE0GMwBVApMgWy6ZlFAcb1Wb4QKC\
  XqfhJBGUo28OG2UDOxl1xHiMQsKxmes14t1DM%2B1e9jkcBr8RukSn90W6o8Po7IGR9w6iuszaAYK\
  8Hh%2F5oK0u0X0pshAYf%2Bxmig1FTMBevPYgCet8hpKZUyiCimCUJoXpolA2z2z5ZXPQ0e1Vh1i2\
  D5zwqUWXvwLtFip%2BugyySkykwokKMr3mxQWQ%2BjJ7p02%2Firu7Pb0olfiThZgOlhU5uDCPz4q\
  9BjqkASszmMq%2FFfMw%2ByTAKyPLwrZWpv9grU3ba%2FP5nNVazmPNxMWFeFx315M9N3DvCFi3do\
  fEnyu9LwO%2FVUZmJZycFHLl38AYW%2BRfLXErmafjSnnv8%2BWiCAGyb8bYB%2BCvfgOyntTJy9h\
  ozKKFcuYu1%2FfDcRPKxmgg91TFyGR2F1JQ7qPEK7Jp4%2FSs13cCmANLw0OoYYlhsU4FGZ7HIULK\
  0hH6eeWPaPTz&X-Amz-Signature=c627022565b54102f287907d1e3c21bf1d5d9e05bac767bf\
  4b139d8dc05aa9db&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665WDV6UVS%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T023230Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIHDC3nbuWn4lqfD%2BZeNJQhhVPHFBh\
        espz%2FJZ7rD%2BKmn%2FAiEA04xqeoGTHNsDdPGejiUx7k%2Fp1pnTnJPkPD523Gq2HDMq\
        %2FwMIORAAGgw2Mzc0MjMxODM4MDUiDBJF9ycX5MLsXYUKDyrcA5u%2BJ%2FBwEHiX1rA%2\
        BVCse2ertFd9DrY2excKMNuoLYnuJPiNSOewz1mp8OX9%2FXFWmPeka5OobLc3erqQsROtR\
        lVefwrXxQk7ro34%2B7jClUwRd6FnpR7lMow8XPzdKVerC0R469V4TBmwGVPS62eK5lc5hO\
        ShaNoJfJvv7KujJdLdHZH2CKxpq%2BIRGb6Xp%2F9ub%2BmROZJKyeKvT1ReCrg%2FQB1Yr\
        hke%2Bqe2WJDNAZxq%2Fkof1hsHnLssak6epT%2BmzCRwO653jb0d4J6dwnUeNnw29CPW6r\
        CNyBoWnkyRYoD0B%2FdAjOoZ1Ss3pl5QGAbuzzllMOBT79AjdZLFEZFcYqB9U6yVDorzxl5\
        lVHDZdqWYlMhtkxN2MwIDe6YnLf798o4YEh%2FF0iG884n4NR60HN%2FTGXig3f3NVdFgQD\
        jG6OLFLGBjNUASoo3kayQHJv%2B%2BsTml7TyfGSK6GtVs4MUXm92lfVBf%2Bqf%2BnT99Q\
        4t8s9TRL2%2BaxXHjQrqzgdsNgv%2FcVCHfsN4X7wDBuDZCnmXcTOA6XLbzAXDUnfY0uMbb\
        0%2B66BXw7DTGfuNFFxG6Bza5681hu%2BE%2BSOlcNQHQJPNwnxUvHohnOP%2BPTvj0GEzK\
        stVqCiJeYWdnsosWORsSeP0KCMMNLPir0GOqUBoMBiHk9e%2B010amsEGglX%2B%2FP3aVo\
        Jzr4b9YFV5tsXp71oI4PbBctIyDjfk%2B1%2BvHk%2BqHS%2FVVZj9JLmkxzJL8U1OdEj2l\
        spzyMNdk51vELJx7OKcSm0%2FhdoI5h93Iffd3uWIkwLiY7Riwcx1VqtjXHQJXDWk4kCGVM\
        W4cJWZkgPObA6faWondTBLhxdjfM%2Fd5s53XWOhoym1aQCwcwwlJaZhkoEEIlI&X-Amz-S\
        ignature=fa2163a721c6da55cf515f96ed670e47008cc1696ee2bb84d0de30516c6294\
        2b&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T03:32:30.851Z"
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
UPDATE_TIME: "2025-02-05T02:33:46.824Z"
EXPIRY_TIME: "2025-02-05T03:33:38.445Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=db540243d919f07a9620b7467aad77a2fe2d21bb97dd6381291dd868e2b6579e&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=7e112c3f2e29deaf14b55d5da28bc27f98ee34edfee8d2c651b0557e24c8afc4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=d4f1db4c70fad5f3ffd6a5b126747a02c5de914c3855f12e1eb3ca042c9bac08&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=17df30562c2fd3d8c2585d5fee5f5a710e0aefc19de329e9a7e8b112b30a83d7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=e1675fe1b654794a12773fd740128096224f166077ec0120b890177c8b5e38f9&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UMAUMU4G%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023340Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIEt4baEUAzkmscYZS1%2F2hJvlNcnoTCmorTzkgGPFN%2FkqAiEAqKSGzoQEHOOkWE3lOvDERR56g6qjgdKK7FXP8uvOZdcq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDHPKBNubllPij2lD%2FCrcAxw0j20Vk2OOSak1GNfulnTx3j0e%2Fbw4%2BOH7K7MLk9MeHVFkZ9HcnPWMysOc7iJthSbO1GpJZ5RYti6bN1sBK0%2FH7KFUUHNQr%2Fzvf9RThFTIgZiLM1f0LLPPvmhQBiE5EvzJb1g7XUuLyV%2FOkCdHWE5I05rwE%2B1d17iEPwtc3EYJf4bjAFxQ6yVPOd1TMDAJdLI8KCM%2BY5nPc9NkQWk4GljlLgee9v6mBANbBJJui1sOzEqOk7V%2FZrkMnofmSdwEOOp1X0dH9FqpbFLLpUUtJQwXeKLenuneIxxd7C2gopuEFsZcOKIJxGm8pNiWSUAJEVERrLzuu14l2MSluFbSJ2XlLHgh5rRHJxgUfx7Hdo2%2BD67GfL7vMOr5frpMeBOWYEx328mllHm4bbbmENRfJUCtEAonUw5x1SamPLLKInP8ue8VEcmCR6P%2FlL5zDKi6skSAfc3YaaUlsOJVD3c7Z4Yq%2BEUaJ5P1luXU1SAn3HNxPeZW5nd%2FZSxfXhkfnsJmlTFgTOh9CugRoPOWodHskzcz%2BL8z3ylvDU7GWMMRrDi51YyOtgytV55vrT4J0CnmGw4y8qZHxWEXtRfgA2rVs5NJ5gnjHyL059tccivetRM9NkaZmBjy2kTFyNiMMKzPir0GOqUBgkqwOiu9GBDBTpiwtHqMr0T6SKuCb90yLFHMYkNR6tiOh9nriE6gqfqArcu%2Ba2xAuUOVPi1ScuTxC3dE%2BBLhuGhcqfipWFlPWNNMMTE3PsaOR%2BWFQuD%2FeTHFqfE8JKRHANE4WjBxkyCJcT6aGTPbWzlDV4uPjwpi8a3FTJw0SPjIpycUjHzPuPbyXGyOqEh%2FzYeOpi%2BALCMEIKuPzA4Tw9zeHt1%2B&X-Amz-Signature=70f3a6f400d29e60a2c2f20cf8142f41c59efc442ac90bd1bd66455aed9b1101&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YWHOMUHB%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023340Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIHQk%2Bwj1jD8O%2BRCOsCpdlRqtmKAvaZwzxmE2OwHMQNBfAiAfNlvQDE5JBXwjXEJLO33XWeskWohBc3IfjZImx%2FDBXCr%2FAwg5EAAaDDYzNzQyMzE4MzgwNSIMOlHndq6yZgYL4AuDKtwDay%2FAzDkdG16bZtc7gFmbeco4IitAjKuCRxrgr36l9W2qN5hicfyZbZyvTE1F9Auhy9zjpBq98KEL3PUh0QNGNGo39%2F9Ju34Yt%2BBNS77cal7NOWfXKgyJRMap%2BVfATnVVbu1a8XZxIycgWlQoRAirJuBgsSOVAtkomD5uKN7sVoMEw1hOUqyE%2FNBWWE%2Fjs4oNl9nugUBQpTKax9SMLZHIsKORhR0Ab8vx7HwhS%2BoofVQTigkqd6XifkqXQRzCEi447MUoCYVA%2FmHu85iVZ6GsU%2BpfeRDt8Ks8vQ0%2BzPC7eWLOuWbl1IZoIutqh65nKl5Ih3%2F%2FrAVOaUfplVowGko4m5j4OFtkbKaKkCEsYgFoOMvLf3tz0Rw0wvM6%2BuS6OV358EfGaFX%2B%2FvUR6j2ij8y0tmAOFdy2ijoLi0f6gRJ1VhkJ4tc2oOI%2BAmpT4JaEaXnyTJUIK31RpWSABcdahrFIFX6omDtTvz7KVJueau1j05JokLIO4FuGW5QsHgARVKvIQkUlvIrsGttiDQWQz8%2FuVH%2BSIT9oUWjPMUF763icvbLwySowOugiXAXtqQZowmnwYFMPMP1oym1MhCKjZyITq%2FsGQ%2FAubKdmerUYDFxhgN1znfGeSs0GW7m0a2gwk8%2BKvQY6pgG2KKqqa%2BE84POZzNij%2BoUYUx%2BUf7o6mGZMDhtvky75fJYChpni1CTjPnXb91RWv4psgA8ZIqEIM%2B0YrVpZpL%2Bdx5jMeYiQ2ywCcCg5U%2FyV%2Bl93ZkIQ07Rj4dbKD72AuF%2BR5k6U3bbm7721HxP1NxpHtSwd89%2FOKpyn0FP5M4Kz%2Fxd4Bhhilrc9e5E9yvaRt1Is%2FDYtiU5HG0QnBBiOPdT3n%2Bu3OQRm&X-Amz-Signature=b2d22e5c604aac6b6402f5911e3be3eb9ff60857e9445a01536010efbd23b65a&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=a2fa75811aba6220b9a4ab6c2466273f7e80b750a1e50c85819e699087854686&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=13efa8f0839884c3cd0401ef53a935bb8505a3a624cf56abd7a4ad1e0bfa4442&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46623KSYQTI%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T023339Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJIMEYCIQCp5c%2BtJtkdCRhtclnooUI7%2BCn7ANVRnYk3hcz9DHmJ5gIhAMfTztZKL1HYZost7%2Fyke0hivtVfNXCgbSnfDixLnubgKv8DCDkQABoMNjM3NDIzMTgzODA1IgwjzlB%2FGwWPn1ODZJ4q3APLsvSU8MqIyN8bD5UirdjXJWCS3nR0uY%2FVqzDgPexYPojebLO4kRDYTMD2wtZOG1tgKaqjh4gfIEKHZ1cG%2Ff4EweHIZe3qXoZ09TebANiwYbg%2BFGXL0DWKFpm4WOqTMFXp6azTsRnpFglN%2BKBifrIiwpDWZTdPbXRHNnwKu7q6EQ%2FQvY%2BU3cELor5eEHKn21CdWSUoKHNqesBXji9gUvJ%2FuOmc6WtD5V%2B%2Bz5OfNCdczh3ZW387mOO3%2BjlmNqbBwkC%2BSSdDSBn%2FddkoLD%2BmaLQ%2FClkJXu76oN1Yw9dp6lW3s7MC7GO0%2BOoMOZ3aTJpoeRyGXzU%2Fo3b5GzG%2BoElsa0cVDjNa41g9erImWTO3bxke7UnsEIypiIE%2BUTw8PlVEGIlOEHdsXFACwfuhBok7gLjMqiO9gLKOa9uQCQMj94fOqDGVdMrxI7Qjam1u1FlQEVRebrKdP3Fh%2BrmF0Z%2Bq5LtaAf5WoAv6X9u4LzJWLcr9axdadIJddAZMgsXWnRhGgHA1p3nR1Ztk0B%2FAK41GF36PD4N3%2F3gX1Y3GH7TV2o1O0%2B%2B3GUtKcofRWAfu3h8QvkHcXyxrn59gAkJOtxCmlQCF%2FU9JsMRVEWqYBUCmcLlQ%2B5ihpBcsu08Dqvq2QjD8zoq9BjqkAVsOsEbsE%2FLjFlBvFWYMS3HKLpQVuW1LsD4Z%2Fty2cYzZTcmyTdxqcmcTWA%2FfZbkuu%2BbBFJcZrA4xGMOkrNrnTEuMLbb8pmlhCuHBdiSKIgCX6oWhCed3yizR4B0aolRtbANCbKl%2BvR%2BWrkV1cT%2FEmGMKyN46xcpGNQb%2F3RKPBu1WsCh%2BFFkcOzpJyFQ80mG87Tq64aMOuH26lopdh2wR3y0G8QNk&X-Amz-Signature=1bd9bd49886d53782fbe3318bbbd227367aaae536ee5af775a1fdb7f728e0685&X-Amz-SignedHeaders=host&x-id=GetObject)


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

