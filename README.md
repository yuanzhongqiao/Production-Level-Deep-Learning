<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💡 生产级深度学习指南 🎬 📜 ⛴️</font></font></h1><a id="user-content-bulb-a-guide-to-production-level-deep-learning-clapper-scroll--ferry" class="anchor" aria-label="永久链接： :bulb：生产级深度学习指南 :clapper: :scroll: :ferry:" href="#bulb-a-guide-to-production-level-deep-learning-clapper-scroll--ferry"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/other-languages/Chinese(Simplified).md"><font style="vertical-align: inherit;">🇨🇳中文</font></a><font style="vertical-align: inherit;">翻译</font></font><a href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/other-languages/Chinese(Simplified).md"><font style="vertical-align: inherit;"></font></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🏷️ 新：</font></font><a href="https://github.com/alirezadir/Machine-Learning-Interviews"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习访谈</font></font></a></h3><a id="user-content-label-new-machine-learning-interviews" class="anchor" aria-label="永久链接：：标签：新：机器学习访谈" href="#label-new-machine-learning-interviews"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🏷️注意：这个仓库正在持续开发中，非常欢迎所有反馈和贡献😊</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在生产中部署深度学习模型可能具有挑战性，因为它远远超出了具有良好性能的训练模型的范围。</font><font style="vertical-align: inherit;">为了部署生产级深度学习系统，需要设计和开发几个不同的组件（如下所示）：</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/components.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/components.png" title="" width="95%" height="95%" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库旨在成为构建将在实际应用中部署的生产级深度学习系统的工程指南。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里介绍的材料借用</font></font><a href="https://fullstackdeeplearning.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自全栈深度学习训练营</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（由</font><font style="vertical-align: inherit;">加州大学伯克利分校的</font></font><a href="https://people.eecs.berkeley.edu/~pabbeel/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pieter Abbeel 、OpenAI 的</font></font></a><font style="vertical-align: inherit;"></font><a href="http://josh-tobin.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Josh Tobin</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">Turnitin 的</font></font><a href="https://sergeykarayev.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sergey Karayev ）、 </font></font></a><font style="vertical-align: inherit;"><a href="https://www.linkedin.com/in/robert-crowe/" rel="nofollow"><font style="vertical-align: inherit;">Robert Crowe</font></a><font style="vertical-align: inherit;">的</font></font><a href="https://conferences.oreilly.com/tensorflow/tf-ca/public/schedule/detail/79327" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TFX 研讨会</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及</font><a href="https://www.linkedin.com/in/cfregly/" rel="nofollow"><font style="vertical-align: inherit;">Chris Fregly</font></a><font style="vertical-align: inherit;">的</font><a href="https://pipeline.ai/" rel="nofollow"><font style="vertical-align: inherit;">Pipeline.ai</font></a><font style="vertical-align: inherit;">的</font><a href="https://www.meetup.com/Advanced-KubeFlow/" rel="nofollow"><font style="vertical-align: inherit;">Advanced KubeFlow Meetup</font></a><font style="vertical-align: inherit;">。</font></font><a href="https://www.linkedin.com/in/robert-crowe/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://pipeline.ai/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://www.meetup.com/Advanced-KubeFlow/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://www.linkedin.com/in/cfregly/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习项目</font></font></h1><a id="user-content-machine-learning-projects" class="anchor" aria-label="永久链接：机器学习项目" href="#machine-learning-projects"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有趣的😳事实：</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">85% 的人工智能项目都会失败</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><sup><a href="#fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></a></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">潜在原因包括：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术上不可行或范围不明确</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">永远不要跳跃到生产</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不明确的成功标准（指标）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队管理不善</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. ML 项目生命周期</font></font></h2><a id="user-content-1-ml-projects-lifecycle" class="anchor" aria-label="永久链接：1. ML 项目生命周期" href="#1-ml-projects-lifecycle"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/lifecycle.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/lifecycle.png" title="" width="95%" height="95%" style="max-width: 100%;"></a></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解您所在领域的最新技术的重要性：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助理解什么是可能的</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有助于知道下一步要尝试什么</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2. ML 项目的心智模型</font></font></h2><a id="user-content-2-mental-model-for-ml-project" class="anchor" aria-label="永久链接：2. ML 项目的心智模型" href="#2-mental-model-for-ml-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定义机器学习项目并确定其优先级时需要考虑的两个重要因素：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重大影响：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道的复杂部分</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“廉价预测”有价值的地方</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动化复杂的手动流程很有价值</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低成本：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成本由以下因素驱动：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据可用性</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">性能要求：成本往往会随着精度要求而超线性扩展</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题难度：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一些难题包括：无监督学习、强化学习和某些类别的监督学习</font></font></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/prioritize.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/prioritize.png" title="" width="90%" height="90%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全栈管道</font></font></h1><a id="user-content-full-stack-pipeline" class="anchor" aria-label="永久链接：全栈管道" href="#full-stack-pipeline"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下图展示了生产级深度学习系统中不同组件的高级概述：</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/infra_tooling.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/infra_tooling.png" title="" width="100%" height="100%" style="max-width: 100%;"></a>
</p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
接下来，我们将详细介绍每个模块，并推荐适合每个组件的工具集和框架以及从业者的最佳实践。 
</font></font><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 数据管理</font></font></h2><a id="user-content-1-data-management" class="anchor" aria-label="永久链接： 1. 数据管理" href="#1-data-management"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.1 数据来源</font></font></h3><a id="user-content-11-data-sources" class="anchor" aria-label="永久链接：1.1 数据来源" href="#11-data-sources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有监督的深度学习需要大量的标记数据</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记自己的数据是昂贵的！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是一些数据资源：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源数据（很好的开始，但不是优势）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据增强（计算机视觉的必备条件，NLP 的选项）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">合成数据（几乎总是值得开始，尤其是在 NLP 中）</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.2 数据标记</font></font></h3><a id="user-content-12--data-labeling" class="anchor" aria-label="永久链接：1.2 数据标签" href="#12--data-labeling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要：单独的软件堆栈（标签平台）、临时劳动力和质量控制</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签劳动力来源：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">众包（Mechanical Turk）：便宜且可扩展，可靠性较差，需要质量控制</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">雇用自己的注释者：需要较少的质量控制、昂贵、扩展缓慢</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据标注服务公司：
</font></font><ul dir="auto">
<li><a href="https://www.figure-eight.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图八</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签平台：
</font></font><ul dir="auto">
<li><a href="https://diffgram.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Diffgram</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：训练数据软件（计算机视觉）</font></font></li>
<li><a href="https://prodi.gy/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Prodigy</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：一种由主动学习（由 Spacy 开发人员）、文本和图像提供支持的注释工具</font></font></li>
<li><a href="https://thehive.ai/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HIVE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：人工智能即计算机视觉服务平台</font></font></li>
<li><a href="https://supervise.ly/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监督</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：整个计算机视觉平台</font></font></li>
<li><a href="https://labelbox.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签盒</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：计算机视觉</font></font></li>
<li><a href="https://scale.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scale</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> AI 数据平台（计算机视觉和 NLP）</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3. </font><font style="vertical-align: inherit;">数据存储</font></font></h3><a id="user-content-13-data-storage" class="anchor" aria-label="永久链接：1.3。 数据存储" href="#13-data-storage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据存储选项：
</font></font><ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对象存储</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：存储二进制数据（图像、声音文件、压缩文本）
</font></font><ul dir="auto">
<li><a href="https://aws.amazon.com/s3/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚马逊S3</font></font></a></li>
<li><a href="https://ceph.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ceph</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对象存储</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：存储元数据（文件路径、标签、用户活动等）。
</font></font><ul dir="auto">
<li><a href="https://www.postgresql.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Postgres</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是大多数应用程序的正确选择，具有一流的 SQL 和对非结构化 JSON 的强大支持。</font></font></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据湖</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：聚合无法从数据库获得的特征（例如日志）
</font></font><ul dir="auto">
<li><a href="https://aws.amazon.com/redshift/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚马逊红移</font></font></a></li>
</ul>
</li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征存储</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：存储、访问和共享机器学习特征（特征提取的计算成本可能很高，而且几乎不可能扩展，因此不同模型和团队重用特征是高性能 ML 团队的关键）。
</font></font><ul dir="auto">
<li><a href="https://github.com/gojek/feast"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FEAST</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（谷歌云，开源）</font></font></li>
<li><a href="https://eng.uber.com/michelangelo/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米开朗基罗调色板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（Uber）</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议：在训练时，将数据复制到本地或网络</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件系统</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(NFS) 中。</font></font><sup><a href="#fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></a></sup></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.4. </font><font style="vertical-align: inherit;">数据版本控制</font></font></h3><a id="user-content-14-data-versioning" class="anchor" aria-label="永久链接：1.4。 数据版本控制" href="#14-data-versioning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于已部署的 ML 模型来说，这是“必须”的：</font></font><br>
<strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已部署的 ML 模型部分是代码，部分是数据</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><sup><a href="#fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></a></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">  无数据版本控制意味着无模型版本控制。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据版本控制平台：
</font></font><ul dir="auto">
<li><a href="https://dvc.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DVC</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：ML 项目的开源版本控制系统</font></font></li>
<li><a href="https://www.pachyderm.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pachyderm</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：数据的版本控制</font></font></li>
<li><a href="https://github.com/dolthub/dolt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dolt</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：一个 SQL 数据库，具有类似 Git 的数据和模式版本控制</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.5. </font><font style="vertical-align: inherit;">数据处理</font></font></h3><a id="user-content-15-data-processing" class="anchor" aria-label="永久链接：1.5。 数据处理" href="#15-data-processing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生产模型的训练数据可能来自不同的来源，包括</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库和对象存储中的存储数据</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志处理</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他分类器的输出</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务之间存在依赖关系，每个任务都需要在其依赖关系完成后启动。</font><font style="vertical-align: inherit;">例如，对新日志数据进行训练，需要在训练之前进行预处理步骤。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Makefile 不可扩展。</font><font style="vertical-align: inherit;">在这方面，“工作流程管理器”变得非常重要。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作流程编排：</font></font></strong>
<ul dir="auto">
<li><a href="https://github.com/spotify/luigi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路易吉 (Luigi)</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的 Spotify</font></font></li>
<li><a href="https://airflow.apache.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Airflow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> by Airbnb：动态、可扩展、优雅、可扩展（使用最广泛）
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有向无环图工作流程</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强大的条件执行：失败时重试</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pusher 支持带有 TensorFlow 服务的 docker 镜像</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整个工作流程在一个 .py 文件中</font></font></li>
</ul>
</li>
</ul>
</li>
</ul>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/airflow_pipe.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/airflow_pipe.png" title="" width="65%" height="65%" style="max-width: 100%;"></a>
   </p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2. 开发、培训和评估</font></font></h2><a id="user-content-2-development-training-and-evaluation" class="anchor" aria-label="永久链接：2. 开发、培训和评估" href="#2-development-training-and-evaluation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.1. </font><font style="vertical-align: inherit;">软件工程</font></font></h3><a id="user-content-21-software-engineering" class="anchor" aria-label="永久链接：2.1。 软件工程" href="#21-software-engineering"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获奖语言：Python</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编辑：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维姆</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Emacs</font></font></li>
<li><a href="https://code.visualstudio.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VS Code</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（作者推荐）：内置git staging和diff，Lint代码，通过ssh远程打开项目</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记本：非常适合作为项目的起点，但难以扩展（有趣的事实：Netflix 的笔记本驱动架构是一个例外，它完全基于</font></font><a href="https://nteract.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nteract</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套件）。
</font></font><ul dir="auto">
<li><a href="https://nteract.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nteract</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：适用于 Jupyter 笔记本的下一代基于 React 的 UI</font></font></li>
<li><a href="https://github.com/nteract/papermill"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Papermill</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：是一个</font></font><a href="https://nteract.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nteract</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库，用于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数化</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执行</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jupyter Notebooks。</font></font></li>
<li><a href="https://github.com/nteract/commuter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Commuter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：另一个</font></font><a href="https://nteract.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nteract</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目，它提供笔记本的只读显示（例如来自 S3 存储桶）。</font></font></li>
</ul>
</li>
<li><a href="https://streamlit.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Streamlit</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：带有小程序的交互式数据科学工具</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算建议</font></font><sup><a href="#fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></a></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">个人</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初创公司</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发：4x 图灵架构 PC</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练/评估：使用相同的 4x GPU PC。</font><font style="vertical-align: inherit;">进行大量实验时，要么购买共享服务器，要么使用云实例。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大公司：</font></font></em>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发：为每个 ML 科学家购买 4 台图灵架构 PC 或让他们使用 V100 实例</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训/评估：使用云实例并进行适当的配置和故障处理</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云提供商：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GCP：将 GPU 连接到任何实例的选项 + 具有 TPU</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚马逊AWS：</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.2. </font><font style="vertical-align: inherit;">资源管理</font></font></h3><a id="user-content-22-resource-management" class="anchor" aria-label="永久链接：2.2。 资源管理" href="#22-resource-management"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为程序分配免费资源</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源管理选项：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">老派集群作业调度程序（例如</font></font><a href="https://slurm.schedmd.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slurm</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作负载管理器）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人+库伯内特斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库贝流</font></font></li>
<li><a href="https://polyaxon.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Polyaxon</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（付费功能）</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.3. </font><font style="vertical-align: inherit;">深度学习框架</font></font></h3><a id="user-content-23-dl-frameworks" class="anchor" aria-label="永久链接：2.3。 深度学习框架" href="#23-dl-frameworks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除非有充分的理由不这样做，否则请使用 Tensorflow/Keras 或 PyTorch。</font></font><sup><a href="#fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></a></sup></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下图显示了不同框架之间如何代表</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“开发”</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“生产”</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的比较。</font></font></li>
</ul>
  <p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/frameworks.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/frameworks.png" title="" width="95%" height="95%" style="max-width: 100%;"></a>
   </p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.4. </font><font style="vertical-align: inherit;">实验管理</font></font></h3><a id="user-content-24-experiment-management" class="anchor" aria-label="永久链接：2.4。 实验管理" href="#24-experiment-management"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发、培训和评估策略：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总是从</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简单开始</font></font></strong>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小批量训练小模型。</font><font style="vertical-align: inherit;">仅当它有效时，才能扩展到更大的数据和模型以及超参数调整！</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实验管理工具：</font></font></li>
<li><a href="https://www.tensorflow.org/tensorboard" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量板</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供 ML 实验所需的可视化和工具</font></font></li>
</ul>
</li>
<li><a href="https://losswise.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Losswise</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（机器学习监控）</font></font></li>
<li><a href="https://www.comet.ml/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comet</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：让您跟踪 ML 项目的代码、实验和结果</font></font></li>
<li><a href="https://www.wandb.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">权重和偏差</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：通过轻松协作记录和可视化研究的每个细节</font></font></li>
<li><a href="https://www.mlflow.org/docs/latest/tracking.html#tracking" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLFlow Tracking</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：用于记录参数、代码版本、指标和输出文件以及结果的可视化。
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">python 一行代码自动跟踪实验</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实验的并排比较</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超参数调优</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持基于 Kubernetes 的作业</font></font></li>
</ul>
</li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.5. </font><font style="vertical-align: inherit;">超参数调优</font></font></h3><a id="user-content-25-hyperparameter-tuning" class="anchor" aria-label="永久链接：2.5。 超参数调优" href="#25-hyperparameter-tuning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网格搜索</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随机搜索</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贝叶斯优化</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HyperBand 和异步连续减半算法 (ASHA)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于人群的培训</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台：</font></font></p>
<ul dir="auto">
<li><a href="http://tune.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RayTune</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Ray Tune 是一个用于任意规模超参数调整的 Python 库（重点关注深度学习和深度强化学习）。</font><font style="vertical-align: inherit;">支持任何机器学习框架，包括 PyTorch、XGBoost、MXNet 和 Keras。</font></font></li>
<li><a href="https://github.com/kubeflow/katib"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Katib</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Kubernete 用于超参数调优和神经架构搜索的本机系统，灵感来自 [Google vizier]( </font></font><a href="https://static.googleusercontent.com/media/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://static.googleusercontent.com/media/research.google.com/ja//pubs/archive/bcb15507f4b52991a0783013df4222240e942381.pdf</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 和支持多种 ML/DL 框架（例如 TensorFlow、MXNet 和 PyTorch）。</font></font></li>
<li><a href="https://maxpumperla.com/hyperas/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hyperas</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Keras 的 hyperopt 的简单包装器，使用简单的模板符号来定义要调整的超参数范围。</font></font></li>
<li><a href="https://sigopt.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SIGOPT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：可扩展的企业级优化平台</font></font></li>
<li><a href="https://docs.wandb.com/library/sweeps" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自 [Weights &amp; Biases] ( </font></font><a href="https://www.wandb.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.wandb.com/ ) 的</font></font></a><font style="vertical-align: inherit;"><a href="https://docs.wandb.com/library/sweeps" rel="nofollow"><font style="vertical-align: inherit;">扫描</font></a><font style="vertical-align: inherit;">：开发人员未明确指定参数。</font><font style="vertical-align: inherit;">相反，它们是通过机器学习模型来近似和学习的。</font></font></li>
<li><a href="https://github.com/keras-team/keras-tuner"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Keras Tuner</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Keras 的超参数调优器，专门用于带有 TensorFlow 2.0 的 tf.keras。</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.6。</font><font style="vertical-align: inherit;">分布式训练</font></font></h3><a id="user-content-26-distributed-training" class="anchor" aria-label="永久链接：2.6。 分布式训练" href="#26-distributed-training"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据并行：迭代时间过长时使用（tensorflow和PyTorch都支持）
</font></font><ul dir="auto">
<li><a href="https://ray.readthedocs.io/en/latest/distributed_training.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">射线分布式训练</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型并行性：当模型不适合单个 GPU 时</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他解决方案：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">霍罗沃德</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3. 故障排除[待定]</font></font></h2><a id="user-content-3-troubleshooting-tbd" class="anchor" aria-label="永久链接：3. 故障排除 [待定]" href="#3-troubleshooting-tbd"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4. 测试和部署</font></font></h2><a id="user-content-4-testing-and-deployment" class="anchor" aria-label="永久链接：4. 测试和部署" href="#4-testing-and-deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.1. </font><font style="vertical-align: inherit;">测试和 CI/CD</font></font></h3><a id="user-content-41-testing-and-cicd" class="anchor" aria-label="永久链接：4.1。 测试和 CI/CD" href="#41-testing-and-cicd"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习生产软件需要比传统软件更多样化的测试套件：</font></font></p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/testing.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/testing.png" title="" width="75%" height="75%" style="max-width: 100%;"></a>
   </p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单元和集成测试：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试类型：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训系统测试：测试培训管道</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证测试：在验证集上测试预测系统</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能测试：在几个重要的例子上测试预测系统</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续集成：在将每个新代码更改推送到存储库后运行测试</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于持续集成的 SaaS：
</font></font><ul dir="auto">
<li><a href="https://argoproj.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Argo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：开源 Kubernetes 本机工作流引擎，用于编排并行作业（包括工作流、事件、CI 和 CD）。</font></font></li>
<li><a href="https://circleci.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CircleCI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：包含语言的支持、自定义环境、灵活的资源分配，由 instacart、Lyft 和 StackShare 使用。</font></font></li>
<li><a href="https://travis-ci.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特拉维斯·西尔</font></font></a></li>
<li><a href="https://buildkite.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Buildkite</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：快速稳定的构建，开源代理几乎可以在任何机器和架构上运行，自由使用自己的工具和服务</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jenkins：老派构建系统</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.2. </font><font style="vertical-align: inherit;">网络部署</font></font></h3><a id="user-content-42-web-deployment" class="anchor" aria-label="永久链接：4.2。 网络部署" href="#42-web-deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由预测系统</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><strong><font style="vertical-align: inherit;">服务系统</font></strong><font style="vertical-align: inherit;">组成</font></font><strong><font style="vertical-align: inherit;"></font></strong>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预测系统：处理输入数据，做出预测</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务系统（Web服务器）：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">考虑规模来提供预测</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 REST API 服务预测 HTTP 请求</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调用预测系统响应</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务选项：
</font></font><ul dir="auto">
<li>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署到虚拟机，通过添加实例进行扩展</font></font></li>
</ol>
</li>
<li>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为容器部署，通过编排进行扩展</font></font></li>
</ol>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集装箱
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器编排：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubernetes（现在最流行）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">梅索斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马拉松</font></font></li>
</ul>
</li>
</ul>
</li>
<li>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将代码部署为“无服务器函数”</font></font></li>
</ol>
</li>
<li>
<ol start="4" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型服务</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决方案进行部署</font></font></li>
</ol>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型服务：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ML 模型的专门 Web 部署</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">批量请求 GPU 推理</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构架：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量流服务</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MXNet 模型服务器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快船（伯克利）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SaaS解决方案
</font></font><ul dir="auto">
<li><a href="https://www.seldon.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Seldon</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：在 Kubernetes 上的任何框架中构建和扩展模型</font></font></li>
<li><a href="https://algorithmia.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法</font></font></a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">决策：CPU 还是 GPU？
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU推断：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果满足要求，CPU推理是优选的。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过添加更多服务器或无服务器进行扩展。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPU推理：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TF 发球或 Clipper</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自适应批处理很有用</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（奖励）部署 Jupyter Notebooks：
</font></font><ul dir="auto">
<li><a href="https://github.com/kubeflow/fairing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubeflow Fairing</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个混合部署包，可让您部署</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jupyter 笔记本</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码！</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.5 服务网格和流量路由</font></font></h3><a id="user-content-45-service-mesh-and-traffic-routing" class="anchor" aria-label="永久链接：4.5 服务网格和流量路由" href="#45-service-mesh-and-traffic-routing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从整体应用程序向分布式微服务架构的过渡可能具有挑战性。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网格</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（由微服务网络组成）降低了此类部署的复杂性，并减轻了开发团队的压力。
</font></font><ul dir="auto">
<li><a href="https://istio.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Istio</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：一种服务网格，可轻松创建已部署服务的网络，具有负载平衡、服务间身份验证、监控功能，并且服务代码中只需很少或无需更改代码。</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.4. </font><font style="vertical-align: inherit;">监控：</font></font></h3><a id="user-content-44-monitoring" class="anchor" aria-label="永久链接：4.4。 监控：" href="#44-monitoring"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监测目的：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">停机、错误和分配变化警报</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捕获服务和数据回归</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云提供商的解决方案很不错</font></font></li>
<li><a href="https://kiali.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kiali</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：Istio 的可观察控制台，具有服务网格配置功能。</font><font style="vertical-align: inherit;">它回答了这些问题：微服务如何连接？</font><font style="vertical-align: inherit;">他们的表现如何？</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们完了吗？</font></font></h4><a id="user-content-are-we-done" class="anchor" aria-label="永久链接：我们完成了吗？" href="#are-we-done"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/post-deploy.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/post-deploy.png" title="" width="65%" height="65%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.5. </font><font style="vertical-align: inherit;">在嵌入式和移动设备上部署</font></font></h3><a id="user-content-45-deploying-on-embedded-and-mobile-devices" class="anchor" aria-label="永久链接：4.5。 在嵌入式和移动设备上部署" href="#45-deploying-on-embedded-and-mobile-devices"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要挑战：内存占用和计算限制</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决方案：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">量化</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缩小模型尺寸
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动网络</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">知识蒸馏
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DistillBERT（用于 NLP）</font></font></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">嵌入式和移动框架：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量流精简版</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyTorch 移动版</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">核心机器学习</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习套件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">弗里茨</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放VINO</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号转换：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放神经网络交换 (ONNX)：深度学习模型的开源格式</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.6. </font><font style="vertical-align: inherit;">一体化解决方案</font></font></h3><a id="user-content-46-all-in-one-solutions" class="anchor" aria-label="永久链接：4.6。 一体化解决方案" href="#46-all-in-one-solutions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量流扩展 (TFX)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米开朗基罗（优步）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谷歌云人工智能平台</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚马逊 SageMaker</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">海王星</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">弗洛伊德</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸空间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">坚定的人工智能</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多米诺数据实验室</font></font></li>
</ul>
<p align="center" dir="auto">
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/infra-cmp.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/infra-cmp.png" title="" width="100%" height="100%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量流扩展 (TFX)</font></font></h1><a id="user-content-tensorflow-extended-tfx" class="anchor" aria-label="永久链接：Tensorflow Extended (TFX)" href="#tensorflow-extended-tfx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[待定]</font></font></p>
<p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/tfx_config.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/tfx_config.png" title="" width="95%" height="95%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Airflow 和 KubeFlow ML 管道</font></font></h1><a id="user-content-airflow-and-kubeflow-ml-pipelines" class="anchor" aria-label="永久链接：Airflow 和 KubeFlow ML 管道" href="#airflow-and-kubeflow-ml-pipelines"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[待定]</font></font></p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/images/kubeflow_pipe.png"><img src="https://github.com/alirezadir/Production-Level-Deep-Learning/raw/master/images/kubeflow_pipe.png" title="" width="45%" height="45%" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他有用的链接：</font></font></h2><a id="user-content-other-useful-links" class="anchor" aria-label="固定链接：其他有用的链接：" href="#other-useful-links"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://www.slideshare.net/xamat/lessons-learned-from-building-practical-deep-learning-systems" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从构建实用的深度学习系统中吸取的经验教训</font></font></a></li>
<li><a href="https://ai.google/research/pubs/pub43146" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习：技术债务的高息信用卡</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><a href="https://github.com/alirezadir/Production-Level-Deep-Learning/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a></h2><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考：</font></font></h2><a id="user-content-references" class="anchor" aria-label="永久链接： 参考资料：" href="#references"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a name="user-content-fsdl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[1]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://fullstackdeeplearning.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全栈深度学习训练营</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2019 年 11 月。</font></font></p>
<p dir="auto"><a name="user-content-pipe"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font><a href="https://pipeline.ai/" rel="nofollow"><font style="vertical-align: inherit;">Pipeline.ai</font></a><font style="vertical-align: inherit;">的</font></font><a href="https://www.meetup.com/Advanced-KubeFlow/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级 KubeFlow 研讨会</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2019 年。</font></font><a href="https://pipeline.ai/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><a name="user-content-pipe"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[3]</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://cdn.oreillystatic.com/en/assets/1/event/298/TFX_%20Production%20ML%20pipelines%20with%20TensorFlow%20Presentation.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TFX：生产中的真实世界机器学习</font></font></a></p>
</article></div>
