# chinese-financial-resources
本仓库致力于收集和整理全面的中文金融数据资源，旨在帮助研究人员及从业者展开工作。

## 数据汇总

### 比赛数据
<details><summary><b>1、金融信息负面及主体判定比赛数据集</b></summary>
  1. 任务描述：该任务分为两个子任务：<br>
给定一条金融文本和文本中出现的金融实体列表，<br>
（1）负面信息判定：判定该文本是否包含金融实体的负面信息。如果该文本不包含负面信息，或者包含负面信息但负面信息未涉及到金融实体，则负面信息判定结果为0。<br>
（2）负面主体判定：如果任务1中包含金融实体的负面信息，继续判断负面信息的主体对象是实体列表中的哪些实体。<br>
  <br>
  2. 数据集地址：https://www.datafountain.cn/competitions/353<br>
  <br>



</details>

<details><summary><b>2、CCKS-NEC-金融领域的因果事件要素抽取</b></summary>
  l 任务描述：本任务旨在从海量财经新闻中抽取因果事件并补齐相关事件要素，具体为是继因果关系抽取后，
  从因果事件所在篇章抽取原因事件要素和结果事件要素。目前金融领域的事件抽取和事件要素填充主要针对一定范围内的特定事件，需要针对不同事件类型定义不同的Schema，对专业知识和人工成本要求较高。
  而本任务借鉴了开放领域的事件抽取和事件要素填充的思路，通过定义较为标准的事件Schema和数据标注，意图实现对更丰富的金融事件类型的自动抽取。
 
  l 该任务目标是继因果抽取后，从因果事件所在篇章抽取原因事件要素和结果事件要素。即给定文本T，及其包含的原因事件C和结果事件E，分别抽取C和E中的事件要素，如下：
输入：一段文本，其包含的原因事件C和结果事件E。
输出：原因事件和结果事件的事件要素。
  l 数据集地址：https://www.biendata.xyz/competition/ccks-nec-2022/
</details>

<details><summary><b>3、CCKS2022：面向金融领域的FEW-SHOT事件抽取</b></summary>
  l 任务描述：我们将提供一定数量的事件类型及其事件主体公司，其中一部分事件类型在训练数据集中标注样本数量有限，但在测试数据集中数量会比较多。而我们在评测的时候对标注样本数量有限的事件类型将
  给与更高的权重，事件的类型判断和主体抽取是评测的目标。
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks2022_eventext/
</details>

<details><summary><b>4、CCKS 2019 面向金融领域的事件主体抽取</b></summary>
  l 任务描述：本次评测任务的主要目标是从真实的新闻语料中，抽取特定事件类型的主体。即给定一段文本T，和文本所属的事件类型S，从文本T中抽取指定事件类型S的事件主体。
输入：一段文本，事件类型S
输出：事件主体
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2019_4/
</details>

<details><summary><b>5、CCKS 2020：面向金融领域的篇章级事件主体与要素抽取（一）事件主体抽取</b></summary>
  l 任务描述：本次评测任务的文本范围包括互联网上的新闻文本，上市公司发布的公告文本（PDF文档已转成无结构化的文本内容）。 本次评测任务的事件类型包括：财务造假、偿付能力不足、高层失联/去世、企业破产、
  重大资损、重大赔付、重大事故、股权冻结、股权质押、增持、减持等。本次评测任务把发生特定事件类型的主体称为事件主体，如 “公司A向公司B赔付”对于事件类型“重大赔付”的事件主体是“公司A”。事件要素为该事件类型的所有属性信息，如事件类型“破产清算”的事件要素包括“发布公告时间”、“破产清算的公司”、“受理法院”、 “公司所属行业”、 “裁定时间”。
本次评测包括两个子任务：事件主体抽取和篇章事件要素抽取。
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2020_4_1/
</details>

<details><summary><b>6、CCKS 2020：面向金融领域的篇章级事件主体与要素抽取（二）篇章事件要素抽取</b></summary>
  l 任务描述：子任务二
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2020_4_2/
</details>

<details><summary><b>7、CCKS 2020：面向金融领域的小样本跨类迁移事件抽取</b></summary>
  l 任务描述：在金融领域，事件抽取是一项十分重要的任务，也是自然语言处理领域一项比较复杂的任务，而小样本下的事件抽取模型在落地应用中也极为需要。本任务需要从金融领域新闻资讯句子中，抽取事件知识（包括事件类型、触发词和事件元素），并将大样本下训练的模型跨类迁移到小样本的其他事件类型上。
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2020_3/
</details>

<details><summary><b>8、CCKS 2020: 基于本体的金融知识图谱自动化构建技术评测</b></summary>
  l 任务描述：本评测任务参考 TAC KBP 中的 Cold Start 评测任务的方案，围绕金融研报知识图谱的自动化图谱构建所展开。评测从预定义图谱模式（Schema）和少量的种子知识图谱开始，从非结构化的文本数据中构建知识图谱
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2020_5/
</details>

<details><summary><b>9、CCKS 2021：面向金融领域的篇章级事件抽取和事件因果关系抽取（一）篇章级事件元素抽取</b></summary>
  l 任务描述：本次评测任务的文本语料来自于互联上的公开新闻、报告。在篇章级事件元素抽取任务中，给定篇章级长文本和事件类型，从篇章级文本中识别事件的元素。
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2021_task6_1/
</details>
  
  <details><summary><b>10、CCKS 2021：面向金融领域的篇章级事件抽取和事件因果关系抽取（二）事件关系抽取</b></summary>
  l 任务描述：本次评测任务的文本语料来自于互联上的公开新闻、报告。在事件关系抽取任务中，给定一段描述因果或影响关系的文本，从文本中抽取原因事件的表示和结果事件的表示，其中事件的表示包括事件类型和事件的三个要素：影响地域、产品、行业。
  
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2021_task6_2/
</details>

<details><summary><b>11、CCKS 2018 微众银行智能客服问句匹配大赛</b></summary>
l 数据集名称：CCKS 2018 微众银行智能客服问句匹配数据集

l 数据集提供者：微众银行

l 数据集介绍：微众银行智能客服问句匹配数据集是由微众银行提供语料支持，哈尔滨工业大学（深圳）智能计算研究中心负责组织实施的真实场景语句意图匹配任务。
  
l 数据集格式：输入：一个语句对。  输出：表明该语句对是否表达相同或者相似意图的二值标签（0或1）

l 数据集地址：https://www.biendata.xyz/competition/CCKS2018_3/
</details>

### 公开数据
<details><summary><b>1、1997年至2020年亚马逊股价</b></summary>
l 数据集名称：亚马逊股票价格数据集
  
l 数据集提供者：亚马逊
  
l 数据集介绍：亚马逊股票价格的时间序列预测。
  
l 链接：https://aistudio.baidu.com/aistudio/datasetdetail/106629
  
l 关于数据集：DATE-格式：YY-MM-DD、Open-股票在开市时的价格、High-当天达到的最高价格、Low-当天达到的最低价格、Close-股票收盘时价格、
  Adj Close-调整后所有适用的股利和股息分配的收盘价、Volume-交易股数。
</details>
  
<details><summary><b>2、上市及中小型企业工商信息数据</b></summary>
l 数据集名称：上市及中小型企业工商信息数据集

l 数据集提供者：SmoothNLP

l 数据集介绍：数据集字段：名称,公司名称,公司介绍,工商,地址,工商注册id,成立时间,法人代表,注册资金,统一信用代码,网址
  
l 数据集地址：https://github.com/smoothnlp/FinancialDatasets/tree/master
</details>
  
  
<details><summary><b>3、金融行业问答数据集</b></summary>
l 背景描述: 77万条金融行业问答数据，包括用户提问、网友回答、最佳回答 
  
l 数据说明: financezhidao_filter.csv: 加工处理： 过滤了id、url、qid、reply_t、user字段，对question、reply做了脱敏处理 
  
l 字段说明: title-问题的标题, question-问题内容（可为空）, reply-回复内容, is_best-是否为页面上显示的最佳回答
  
l 数据集地址：https://aistudio.baidu.com/aistudio/datasetdetail/34744/0
</details>
  
<details><summary><b>4、2万条中文金融新闻数据集</b></summary>
  l 背景描述：2万条金融新闻数据集，包括了`新闻标题、新闻内容和发稿日期。
  
  l 数据集地址：https://www.heywhale.com/mw/dataset/5eb69242366f4d002d77d2b7/file
</details>


  
  <details><summary><b>5、基于金融财报中的混合表格与文本数据的问答</b></summary>
  l 任务描述：给定从金融财报中筛选的一个半结构化的表格和几个与该表格相关的段落（一般不少于2个），当收到一个与之相关的自然语言形式的问题后，要求模型能够根据表格和段落给出该问题的相应的答案。
  
  l 数据集地址：https://www.datafountain.cn/competitions/573
</details>

<details><summary><b>6、DUEE-fin金融事件数据集</b></summary>
  l 任务描述：篇章级事件抽取数据集（DuEE-Fin）是金融领域篇章级别事件抽取数据集，共包含13个已定义好的事件类型约束和1.15万中文篇章（存在部分非目标篇章作为负样例），其中6900训练集，1150验证集和3450测试集
  l 数据集地址：https://aistudio.baidu.com/aistudio/datasetdetail/157875/0
</details>

<details><summary><b>7、BBT-CFLEB中文金融6个评估任务数据集</b></summary>
  l 任务描述： BBT-CFLEB 选择了六个任务：2个语言生成，4个语言理解。  
  （1）FinNL，一个金融新闻分类数据集。  
  （2）FinNA，金融新闻摘要数据集。  
  （3）FinRE，金融新闻关系抽取数据集。  
  （4）FinFE，金融社交媒体文本情感分类数据集。  
  （5）FinQA，金融新闻公告事件问答数据集（源自 DuEE-fin (Han et al., 2022) 数据集）。  
  （6）FinNSP，金融负面新闻及其主题确定数据集。
  l 数据集地址：https://github.com/ssymmetry/BBT-FinCUGE-Applications/tree/main/FinCUGE_Publish/
</details>

<details><summary><b></b></summary>
  l 任务描述：
  l 数据集地址：https://www.biendata.xyz/competition/ccks_2021_task6_2/
</details>
  
  
## 贡献

欢迎社区成员做出贡献。数据持续收集中，如果您有其他相关资源提供或者您想分享自己的工作，请提交 PR 并在其中描述您的更改。

## 致谢

在此向数据源提供方、项目贡献者一并表示感谢！

## 声明

请严格遵守数据源提供方的许可协议，以免造成不必要的麻烦。
