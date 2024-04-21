<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 id="user-content-python-outlier-detection-pyod" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 异常值检测 (PyOD)</font></font></h1><a id="user-content-python-outlier-detection-pyod" class="anchor" aria-label="永久链接：Python 异常值检测 (PyOD)" href="#python-outlier-detection-pyod"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署、文档、统计数据和许可证</font></font></strong></p>
<p dir="auto"><a href="https://pypi.org/project/pyod/" rel="nofollow"><img src="https://camo.githubusercontent.com/2d79e47c5fbf3382c3d8b3a8c8835f1f4108d3488af7af5979abc313b1b79458/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f70796f642e7376673f636f6c6f723d627269676874677265656e" alt="PyPI版本" data-canonical-src="https://img.shields.io/pypi/v/pyod.svg?color=brightgreen" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://anaconda.org/conda-forge/pyod" rel="nofollow"><img src="https://camo.githubusercontent.com/f4879f12806d50adf7a5744ec3c941b18a20b94b444759bfb482ae9d10bd236a/68747470733a2f2f616e61636f6e64612e6f72672f636f6e64612d666f7267652f70796f642f6261646765732f76657273696f6e2e737667" alt="水蟒版本" data-canonical-src="https://anaconda.org/conda-forge/pyod/badges/version.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://pyod.readthedocs.io/en/latest/?badge=latest" rel="nofollow"><img src="https://camo.githubusercontent.com/660b367e97e4dddf90a1fbfe2089f81cfc0eb31d7b157fa1602e32fb1b34f51b/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f70796f642f62616467652f3f76657273696f6e3d6c6174657374" alt="文件状态" data-canonical-src="https://readthedocs.org/projects/pyod/badge/?version=latest" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/stargazers"><img src="https://camo.githubusercontent.com/b70804dc371600df4d16f001a99e6e4d79dda026226cf068cccd0e4e2c9e2b98/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f797a68616f3036322f70796f642e737667" alt="GitHub 星星" data-canonical-src="https://img.shields.io/github/stars/yzhao062/pyod.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/network"><img src="https://camo.githubusercontent.com/42a367f0a650dd69da1196bc6df32bf398597e240493495ece31a55783a96208/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f726b732f797a68616f3036322f70796f642e7376673f636f6c6f723d626c7565" alt="GitHub 分叉" data-canonical-src="https://img.shields.io/github/forks/yzhao062/pyod.svg?color=blue" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://pepy.tech/project/pyod" rel="nofollow"><img src="https://camo.githubusercontent.com/298beef1458c119789663d6640d3bc59b823931b3495ca461508c2fabed1c67f/68747470733a2f2f706570792e746563682f62616467652f70796f64" alt="下载" data-canonical-src="https://pepy.tech/badge/pyod" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/actions/workflows/testing.yml"><img src="https://github.com/yzhao062/pyod/actions/workflows/testing.yml/badge.svg" alt="测试" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://coveralls.io/github/yzhao062/pyod" rel="nofollow"><img src="https://camo.githubusercontent.com/71c2efb6545398227aedc50853f9b0c6dd5d633bd8b46abfa629b267b6fe5a8b/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f6769746875622f797a68616f3036322f70796f642f62616467652e737667" alt="覆盖状态" data-canonical-src="https://coveralls.io/repos/github/yzhao062/pyod/badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://codeclimate.com/github/yzhao062/Pyod/maintainability" rel="nofollow"><img src="https://camo.githubusercontent.com/6930fb9d59b55ba8817efb26ada61dd2d4ee84cda81f6a34ffb35731f8e351c2/68747470733a2f2f6170692e636f6465636c696d6174652e636f6d2f76312f6261646765732f62646333643864303435343237346337353363342f6d61696e7461696e6162696c697479" alt="可维护性" data-canonical-src="https://api.codeclimate.com/v1/badges/bdc3d8d0454274c753c4/maintainability" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/blob/master/LICENSE"><img src="https://camo.githubusercontent.com/6fd13e074a273b08d3cf336191e5f324f365c7f02a61e8584c9f62b2f2446587/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f797a68616f3036322f70796f642e737667" alt="执照" data-canonical-src="https://img.shields.io/github/license/yzhao062/pyod.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/Minqi824/ADBench"><img src="https://camo.githubusercontent.com/25f8aa095029a6b0bab02f2d85df8bb64e6023c0d34e4d7537fb8723a5fab997/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f414442656e63682d62656e63686d61726b5f726573756c74732d70696e6b" alt="基准" data-canonical-src="https://img.shields.io/badge/ADBench-benchmark_results-pink" style="max-width: 100%;"></a></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-read-me-first" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">先读我的内容</font></font></h2><a id="user-content-read-me-first" class="anchor" aria-label="永久链接：先读我的内容" href="#read-me-first"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎使用 PyOD，这是一个用于检测多变量数据异常的多功能 Python 库。无论您要处理小型项目还是大型数据集，PyOD 都提供一系列算法来满足您的需求。</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于时间序列异常值检测</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请使用</font></font><a href="https://github.com/datamllab/tods"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODS</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于图形异常值检测</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请使用</font></font><a href="https://pygod.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyGOD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">性能比较和数据集</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：我们有 45 页的最全面的</font></font><a href="https://www.andrew.cmu.edu/user/yuezhao2/papers/22-neurips-adbench.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常检测基准论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。完全</font></font><a href="https://github.com/Minqi824/ADBench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源的 ADBench</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 57 个基准数据集上比较了 30 种异常检测算法。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解有关异常检测的更多信息</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@</font></font><a href="https://github.com/yzhao062/anomaly-detection-resources"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常检测资源</font></font></a></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分布式系统上的 PyOD</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：您还可以</font></font><a href="https://www.databricks.com/blog/2023/03/13/unsupervised-outlier-detection-databricks.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 databricks 上运行 PyOD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-about-pyod" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于PyOD</font></font></h2><a id="user-content-about-pyod" class="anchor" aria-label="永久链接：关于 PyOD" href="#about-pyod"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 成立于 2017 年，已成为检测</font><font style="vertical-align: inherit;">多元数据中</font><strong><font style="vertical-align: inherit;">异常/异常对象的</font></strong><font style="vertical-align: inherit;">首选</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 库</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这个令人兴奋但具有挑战性的领域通常被称为</font><a href="https://en.wikipedia.org/wiki/Anomaly_detection" rel="nofollow"><font style="vertical-align: inherit;">异常值检测</font></a></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font><a href="https://en.wikipedia.org/wiki/Anomaly_detection" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://en.wikipedia.org/wiki/Anomaly_detection" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常检测</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 包含 50 多种检测算法，从经典的 LOF (SIGMOD 2000) 到尖端的 ECOD 和 DIF (TKDE 2022 和 2023)。自2017年以来，PyOD已成功应用于众多学术研究和商业产品，</font></font><a href="https://pepy.tech/project/pyod" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载量超过1700万次</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。它也得到了机器学习社区的广泛认可，有各种专门的帖子/教程，包括</font></font><a href="https://www.analyticsvidhya.com/blog/2019/02/outlier-detection-python-pyod/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Analytics Vidhya</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://www.kdnuggets.com/2019/02/outlier-detection-methods-cheat-sheet.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDnuggets</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://towardsdatascience.com/anomaly-detection-for-dummies-15f148e559c1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Towards Data Science</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 的特点是</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">统一、用户友好的界面</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多种型号</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，从经典技术到最新的深度学习方法。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高性能和高效率</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，利用</font></font><a href="https://github.com/numba/numba"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">numba</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/joblib/joblib"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">joblib</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行 JIT 编译和并行处理。</font></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过SUOD 框架实现</font><strong><font style="vertical-align: inherit;">快速训练和预测</font></strong></font><a href="#fn1" id="user-content-fnref1"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 5 行代码进行异常值检测</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div id="user-content-cb1" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># Example: Training an ECOD detector</span>
<span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">models</span>.<span class="pl-s1">ecod</span> <span class="pl-k">import</span> <span class="pl-v">ECOD</span>
<span class="pl-s1">clf</span> <span class="pl-c1">=</span> <span class="pl-v">ECOD</span>()
<span class="pl-s1">clf</span>.<span class="pl-en">fit</span>(<span class="pl-v">X_train</span>)
<span class="pl-s1">y_train_scores</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-s1">decision_scores_</span>  <span class="pl-c"># Outlier scores for training data</span>
<span class="pl-s1">y_test_scores</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-en">decision_function</span>(<span class="pl-v">X_test</span>)  <span class="pl-c"># Outlier scores for test data</span></pre><div class="zeroclipboard-container">
    
  </div></div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择正确的算法：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .不确定从哪里开始？考虑这些强大且可解释的选项：</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/yzhao062/pyod/blob/master/examples/ecod_example.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ECOD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用 ECOD 进行异常值检测的示例</font></font></li>
<li><a href="https://github.com/yzhao062/pyod/blob/master/examples/iforest_example.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">隔离森林</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用隔离森林进行异常值检测的示例</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，探索</font></font><a href="https://github.com/yzhao062/MetaOD"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MetaOD</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取数据驱动的方法。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用 PyOD</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<p dir="auto"><a href="http://www.jmlr.org/papers/volume20/19-011/19-011.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发表在</font></font><a href="http://www.jmlr.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Journal of Machine Learning Research (JMLR)</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（MLOSS track）上。如果您在科学出版物中使用 PyOD，我们希望引用以下论文：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{zhao2019pyod,
    author  = {Zhao, Yue and Nasrullah, Zain and Li, Zheng},
    title   = {PyOD: A Python Toolbox for Scalable Outlier Detection},
    journal = {Journal of Machine Learning Research},
    year    = {2019},
    volume  = {20},
    number  = {96},
    pages   = {1-7},
    url     = {http://jmlr.org/papers/v20/19-011.html}
}</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Zhao, Y., Nasrullah, Z. and Li, Z., 2019. PyOD: A Python Toolbox for Scalable Outlier Detection. Journal of machine learning research (JMLR), 20(96), pp.1-7.</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关异常检测的更广泛视角，请参阅我们的 NeurIPS 论文</font></font><a href="https://viterbi-web.usc.edu/~yzhao010/papers/22-neurips-adbench.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADBench：异常检测基准论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://viterbi-web.usc.edu/~yzhao010/papers/23-neurips-adgym.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADGym：深度异常检测的设计选择</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{han2022adbench,
    title={Adbench: Anomaly detection benchmark},
    author={Han, Songqiao and Hu, Xiyang and Huang, Hailiang and Jiang, Minqi and Zhao, Yue},
    journal={Advances in Neural Information Processing Systems},
    volume={35},
    pages={32142--32159},
    year={2022}
}

@article{jiang2023adgym,
    title={ADGym: Design Choices for Deep Anomaly Detection},
    author={Jiang, Minqi and Hou, Chaochuan and Zheng, Ao and Han, Songqiao and Huang, Hailiang and Wen, Qingsong and Hu, Xiyang and Zhao, Yue},
    journal={Advances in Neural Information Processing Systems},
    volume={36},
    year={2023}
}</code></pre><div class="zeroclipboard-container">
     
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><a href="#api-cheatsheet--reference"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 备忘单和参考</font></font></a></li>
<li><a href="#adbench-benchmark-and-datasets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADBench 基准测试和数据集</font></font></a></li>
<li><a href="#model-save--load"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型保存和加载</font></font></a></li>
<li><a href="#fast-train-with-suod"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD 快速列车</font></font></a></li>
<li><a href="#thresholding-outlier-scores"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常值阈值</font></font></a></li>
<li><a href="#implemented-algorithms"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现的算法</font></font></a></li>
<li><a href="#quick-start-for-outlier-detection"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常值检测快速入门</font></font></a></li>
<li><a href="#how-to-contribute"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何贡献</font></font></a></li>
<li><a href="#inclusion-criteria"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纳入标准</font></font></a></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-installation" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 旨在使用</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pip</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">conda</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻松安装。由于更新和增强频繁，我们建议使用最新版本的 PyOD：</font></font></p>
<div id="user-content-cb5" dir="auto"><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install pyod            <span class="pl-c"><span class="pl-c">#</span> normal install</span>
pip install --upgrade pyod  <span class="pl-c"><span class="pl-c">#</span> or update if needed</span></pre><div class="zeroclipboard-container">
    
  </div></div></div>
<div id="user-content-cb6" dir="auto"><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>conda install -c conda-forge pyod</pre><div class="zeroclipboard-container">
    
  </div></div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，您可以克隆并运行 setup.py 文件：</font></font></p>
<div id="user-content-cb7" dir="auto"><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/yzhao062/pyod.git
<span class="pl-c1">cd</span> pyod
pip install <span class="pl-c1">.</span></pre><div class="zeroclipboard-container">
    
  </div></div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所需的依赖项</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 3.8 或更高版本</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作业库</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">绘图库</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">numpy&gt;=1.19</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字&gt;=0.51</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scipy&gt;=1.5.1</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">scikit_learn&gt;=0.22.0</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选依赖项（请参阅下面的详细信息）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合（可选，models/combination.py和FeatureBagging所需）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">keras/tensorflow（可选，AutoEncoder 和其他深度学习模型所需）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">suod（可选，运行 SUOD 模型所需）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">xgboost（可选，XGBOD 必需）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pythresh（可选，阈值处理所需）可选</font></font></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-api-cheatsheet-reference" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 备忘单和参考</font></font></h2><a id="user-content-api-cheatsheet--reference" class="anchor" aria-label="永久链接：API 备忘单和参考" href="#api-cheatsheet--reference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整的 API 参考可在</font></font><a href="https://pyod.readthedocs.io/en/latest/pyod.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到。以下是所有探测器的快速备忘单：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">fit(X)</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：安装探测器。在无监督方法中参数 y 被忽略。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Decision_function(X)</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用拟合检测器预测 X 的原始异常分数。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预测（X）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用拟合的检测器确定样本是否为异常值作为二进制标签。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Predict_proba(X)</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：使用拟合检测器估计样本为异常值的概率。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Predict_confidence(X)</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：基于每个样本评估模型的置信度（适用于predict和predict_proba）</font></font><a href="#fn2" id="user-content-fnref2"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拟合模型的关键属性</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Decision_scores_</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：训练数据的离群值。分数越高通常表明行为越异常。异常值通常具有较高的分数。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">labels_</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：训练数据的二进制标签，其中 0 表示正常值，1 表示异常值/异常。</font></font></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-adbench-benchmark-and-datasets" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADBench 基准测试和数据集</font></font></h2><a id="user-content-adbench-benchmark-and-datasets" class="anchor" aria-label="永久链接：ADBench 基准测试和数据集" href="#adbench-benchmark-and-datasets"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们刚刚发布了 45 页、最全面的</font></font><a href="https://arxiv.org/abs/2206.09426" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADBench：异常检测基准</font></font></a><a href="#fn3" id="user-content-fnref3"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。完全</font></font><a href="https://github.com/Minqi824/ADBench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源的 ADBench</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 57 个基准数据集上比较了 30 种异常检测算法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADBench</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的组织结构</font><font style="vertical-align: inherit;">如下：</font></font></p>
<p dir="auto"><a href="https://github.com/Minqi824/ADBench/blob/main/figs/ADBench.png?raw=true"><img src="https://github.com/Minqi824/ADBench/raw/main/figs/ADBench.png?raw=true" alt="基准图" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了更简单的可视化，我们</font><font style="vertical-align: inherit;">通过</font><a href="https://github.com/yzhao062/pyod/blob/master/examples/compare_all_models.py"><font style="vertical-align: inherit;">compare_all_models.py</font></a></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对选定的模型进行比较</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://github.com/yzhao062/pyod/blob/master/examples/compare_all_models.py"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/blob/development/examples/ALL.png?raw=true"><img src="https://github.com/yzhao062/pyod/raw/development/examples/ALL.png?raw=true" alt="全部比较" style="max-width: 100%;"></a></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-model-save-load" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型保存和加载</font></font></h2><a id="user-content-model-save--load" class="anchor" aria-label="永久链接：模型保存和加载" href="#model-save--load"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 在模型持久性方面采用了与 sklearn 类似的方法。</font><font style="vertical-align: inherit;">有关说明，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://scikit-learn.org/stable/modules/model_persistence.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型持久性。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简而言之，我们建议使用 joblib 或 pickle 来保存和加载 PyOD 模型。</font><font style="vertical-align: inherit;">有关示例，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/yzhao062/pyod/blob/master/examples/save_load_model_example.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“examples/save_load_model_example.py”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 。简而言之，简单如下：</font></font></p>
<div id="user-content-cb8" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">joblib</span> <span class="pl-k">import</span> <span class="pl-s1">dump</span>, <span class="pl-s1">load</span>

<span class="pl-c"># save the model</span>
<span class="pl-en">dump</span>(<span class="pl-s1">clf</span>, <span class="pl-s">'clf.joblib'</span>)
<span class="pl-c"># load the model</span>
<span class="pl-s1">clf</span> <span class="pl-c1">=</span> <span class="pl-en">load</span>(<span class="pl-s">'clf.joblib'</span>)</pre><div class="zeroclipboard-container">
     
  </div></div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">众所周知，保存神经网络模型存在挑战。检查</font></font><a href="https://github.com/yzhao062/pyod/issues/328#issuecomment-917192704" data-hovercard-type="issue" data-hovercard-url="/yzhao062/pyod/issues/328/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#328</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/yzhao062/pyod/issues/88#issuecomment-615343139" data-hovercard-type="issue" data-hovercard-url="/yzhao062/pyod/issues/88/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#88</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取临时解决方法。</font></font></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-fast-train-with-suod" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD 快速列车</font></font></h2><a id="user-content-fast-train-with-suod" class="anchor" aria-label="永久链接：SUOD 快速列车" href="#fast-train-with-suod"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速训练和预测：利用SUOD框架</font></font></strong><font style="vertical-align: inherit;"></font><a href="#fn4" id="user-content-fnref4"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4，</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在PyOD中使用大量检测模型进行训练和预测</font><font style="vertical-align: inherit;">。请参阅</font></font><a href="https://www.andrew.cmu.edu/user/yuezhao2/papers/21-mlsys-suod.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD 论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/yzhao062/pyod/blob/master/examples/suod_example.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD 示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div id="user-content-cb9" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">models</span>.<span class="pl-s1">suod</span> <span class="pl-k">import</span> <span class="pl-v">SUOD</span>

<span class="pl-c"># initialized a group of outlier detectors for acceleration</span>
<span class="pl-s1">detector_list</span> <span class="pl-c1">=</span> [<span class="pl-v">LOF</span>(<span class="pl-s1">n_neighbors</span><span class="pl-c1">=</span><span class="pl-c1">15</span>), <span class="pl-v">LOF</span>(<span class="pl-s1">n_neighbors</span><span class="pl-c1">=</span><span class="pl-c1">20</span>),
                 <span class="pl-v">LOF</span>(<span class="pl-s1">n_neighbors</span><span class="pl-c1">=</span><span class="pl-c1">25</span>), <span class="pl-v">LOF</span>(<span class="pl-s1">n_neighbors</span><span class="pl-c1">=</span><span class="pl-c1">35</span>),
                 <span class="pl-v">COPOD</span>(), <span class="pl-v">IForest</span>(<span class="pl-s1">n_estimators</span><span class="pl-c1">=</span><span class="pl-c1">100</span>),
                 <span class="pl-v">IForest</span>(<span class="pl-s1">n_estimators</span><span class="pl-c1">=</span><span class="pl-c1">200</span>)]

<span class="pl-c"># decide the number of parallel process, and the combination method</span>
<span class="pl-c"># then clf can be used as any outlier detection model</span>
<span class="pl-s1">clf</span> <span class="pl-c1">=</span> <span class="pl-v">SUOD</span>(<span class="pl-s1">base_estimators</span><span class="pl-c1">=</span><span class="pl-s1">detector_list</span>, <span class="pl-s1">n_jobs</span><span class="pl-c1">=</span><span class="pl-c1">2</span>, <span class="pl-s1">combination</span><span class="pl-c1">=</span><span class="pl-s">'average'</span>,
           <span class="pl-s1">verbose</span><span class="pl-c1">=</span><span class="pl-c1">False</span>)</pre><div class="zeroclipboard-container">
    
  </div></div></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-thresholding-outlier-scores" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常值阈值</font></font></h2><a id="user-content-thresholding-outlier-scores" class="anchor" aria-label="永久链接：阈值异常值" href="#thresholding-outlier-scores"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置污染水平时可以采用更多基于数据的方法。通过使用阈值方法，可以用用于分离异常值和异常值的经过测试的技术来代替猜测任意值。请参阅</font></font><a href="https://github.com/KulikDM/pythresh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyThresh</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以更深入地了解阈值。</font></font></p>
<div id="user-content-cb10" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">models</span>.<span class="pl-s1">knn</span> <span class="pl-k">import</span> <span class="pl-v">KNN</span>
<span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">models</span>.<span class="pl-s1">thresholds</span> <span class="pl-k">import</span> <span class="pl-v">FILTER</span>

<span class="pl-c"># Set the outlier detection and thresholding methods</span>
<span class="pl-s1">clf</span> <span class="pl-c1">=</span> <span class="pl-v">KNN</span>(<span class="pl-s1">contamination</span><span class="pl-c1">=</span><span class="pl-v">FILTER</span>())</pre><div class="zeroclipboard-container">
    
  </div></div></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-implemented-algorithms" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现的算法</font></font></h2><a id="user-content-implemented-algorithms" class="anchor" aria-label="永久链接：实现的算法" href="#implemented-algorithms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 工具包由四个主要功能组组成：</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(i) 个体检测算法</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缩写</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">年</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考号</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ECOD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用经验累积分布函数进行无监督离群值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022年</font></font></td>
<td><a href="#fn5" id="user-content-fnref5"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ABOD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于角度的异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2008年</font></font></td>
<td><a href="#fn6" id="user-content-fnref6"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速ABOD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用近似法进行基于角度的快速异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2008年</font></font></td>
<td><a href="#fn7" id="user-content-fnref7"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">慢性阻塞性肺病</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COPOD：基于 Copula 的异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2020年</font></font></td>
<td><a href="#fn8" id="user-content-fnref8"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">疯狂的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中值绝对偏差 (MAD)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1993年</font></font></td>
<td><a href="#fn9" id="user-content-fnref9"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">9</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">求救</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随机异常值选择</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2012年</font></font></td>
<td><a href="#fn10" id="user-content-fnref10"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量管理中心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准蒙特卡罗差异异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2001年</font></font></td>
<td><a href="#fn11" id="user-content-fnref11"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率论</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">凯德</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用核密度函数进行异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2007年</font></font></td>
<td><a href="#fn12" id="user-content-fnref12"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12</font></font></sup></a></td>
</tr>
<tr>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概率概率</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">采样高斯模型</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过采样概率混合建模进行异常值分析，进行基于距离的快速异常值检测</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2013年</font></font></p></td>
<td><p dir="auto"><a href="#fn13" id="user-content-fnref13"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">13 </font></font></sup></a> <a href="#fn14" id="user-content-fnref14"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">14</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [第2章]</font></font></p></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主成分分析</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主成分分析（到特征向量超平面的加权投影距离之和）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2003年</font></font></td>
<td><a href="#fn15" id="user-content-fnref15"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">15</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关键主成分分析法</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">核主成分分析</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2007年</font></font></td>
<td><a href="#fn16" id="user-content-fnref16"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最小协方差行列式（使用马氏距离作为离群值）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1999年</font></font></td>
<td><a href="#fn17" id="user-content-fnref17"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17 </font></font></sup></a><a href="#fn18" id="user-content-fnref18"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">18</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">光盘</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用库克距离进行异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1977年</font></font></td>
<td><a href="#fn19" id="user-content-fnref19"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">19 号</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式空间向量机</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一类支持向量机</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2001年</font></font></td>
<td><a href="#fn20" id="user-content-fnref20"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低密度脂蛋白</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于偏差的异常值检测 (LMDD)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1996年</font></font></td>
<td><a href="#fn21" id="user-content-fnref21"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">21</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">洛夫</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">局部离群因素</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2000年</font></font></td>
<td><a href="#fn22" id="user-content-fnref22"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">22</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COF</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于连接性的异常值因素</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2002年</font></font></td>
<td><a href="#fn23" id="user-content-fnref23"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（增量）COF</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于内存高效连接的离群因素（速度较慢，但&ZeroWidthSpace;&ZeroWidthSpace;降低存储复杂性）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2002年</font></font></td>
<td><a href="#fn24" id="user-content-fnref24"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">24</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CBLOF</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于聚类的局部离群因子</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2003年</font></font></td>
<td><a href="#fn25" id="user-content-fnref25"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">25</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基因定位</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LOCI：使用局部相关积分进行快速异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2003年</font></font></td>
<td><a href="#fn26" id="user-content-fnref26"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">26</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HBOS</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于直方图的异常值分数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2012年</font></font></td>
<td><a href="#fn27" id="user-content-fnref27"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">27</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">kNN</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">k 最近邻（使用到第 k 个最近邻的距离作为离群值）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2000年</font></font></td>
<td><a href="#fn28" id="user-content-fnref28"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">28</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平均KNN</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平均 kNN（使用到 k 个最近邻的平均距离作为离群值）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2002年</font></font></td>
<td><a href="#fn29" id="user-content-fnref29"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">29</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医学KNN</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中值 kNN（使用到 k 个最近邻的中值距离作为异常值得分）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2002年</font></font></td>
<td><a href="#fn30" id="user-content-fnref30"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">草皮</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">子空间异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2009年</font></font></td>
<td><a href="#fn31" id="user-content-fnref31"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">31</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于邻近度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杆</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于旋转的异常值检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2020年</font></font></td>
<td><a href="#fn32" id="user-content-fnref32"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">爱森林</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">隔离森林</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2008年</font></font></td>
<td><a href="#fn33" id="user-content-fnref33"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">33</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伊内</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用最近邻集成的基于隔离的异常检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn34" id="user-content-fnref34"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">34</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">差值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于异常检测的深度隔离森林</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年</font></font></td>
<td><a href="#fn35" id="user-content-fnref35"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">35</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FB</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征装袋</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2005年</font></font></td>
<td><a href="#fn36" id="user-content-fnref36"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSCP</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSCP：并行异常值集合的局部选择性组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019年</font></font></td>
<td><a href="#fn37" id="user-content-fnref37"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XGBOD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于极端增强的异常值检测</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（监督）</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn38" id="user-content-fnref38"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">38</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">洛达</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻量级在线异常检测器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2016年</font></font></td>
<td><a href="#fn39" id="user-content-fnref39"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">39</font></font></sup></a></td>
</tr>
<tr>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常值集成神经网络</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD自动编码器</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD：加速大规模无监督异构异常值检测</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（加速）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全连接自动编码器（使用重建误差作为异常值得分）</font></font></p></td>
<td><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2021年</font></font></p></td>
<td><p dir="auto"><a href="#fn40" id="user-content-fnref40"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">40 </font></font></sup></a> <a href="#fn41" id="user-content-fnref41"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">41</font></font></sup></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [第3章]</font></font></p></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VAE</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变分自动编码器（使用重建误差作为离群值）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2013年</font></font></td>
<td><a href="#fn42" id="user-content-fnref42"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">42</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">β-VAE</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变分自动编码器（所有通过改变伽玛和容量定制的损失项）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn43" id="user-content-fnref43"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">43</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SO_GAAL</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单目标生成对抗主动学习</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019年</font></font></td>
<td><a href="#fn44" id="user-content-fnref44"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">44</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MO_GAAL</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多目标生成对抗主动学习</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019年</font></font></td>
<td><a href="#fn45" id="user-content-fnref45"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">45</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深SVDD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深度一类分类</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn46" id="user-content-fnref46"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">46</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿诺甘</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用生成对抗网络进行异常检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2017年</font></font></td>
<td><a href="#fn47" id="user-content-fnref47"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">47</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿拉德</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对抗性学习异常检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn48" id="user-content-fnref48"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">48</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于图的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">R图</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 R 图检测异常值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2017年</font></font></td>
<td><a href="#fn49" id="user-content-fnref49"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">49</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于图的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">月球</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LUNAR：通过图神经网络统一局部异常值检测方法</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022年</font></font></td>
<td><a href="#fn50" id="user-content-fnref50"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50</font></font></sup></a></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(ii) 离群值集合和离群值检测器组合框架</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缩写</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">年</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考号</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FB</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征装袋</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2005年</font></font></td>
<td><a href="#fn51" id="user-content-fnref51"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSCP</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSCP：并行异常值集合的局部选择性组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019年</font></font></td>
<td><a href="#fn52" id="user-content-fnref52"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XGBOD</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于极端增强的异常值检测</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（监督）</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn53" id="user-content-fnref53"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">53</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">洛达</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻量级在线异常检测器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2016年</font></font></td>
<td><a href="#fn54" id="user-content-fnref54"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">54</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苏奥德</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SUOD：加速大规模无监督异构异常值检测</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（加速）</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2021年</font></font></td>
<td><a href="#fn55" id="user-content-fnref55"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">55</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值集合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伊内</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用最近邻集成的基于隔离的异常检测</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2018年</font></font></td>
<td><a href="#fn56" id="user-content-fnref56"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">56</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平均的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过平均分数进行简单组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn57" id="user-content-fnref57"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">57</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加权平均</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过对分数与检测器权重进行平均来进行简单组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn58" id="user-content-fnref58"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">58</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最大化</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过取最大分数进行简单组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn59" id="user-content-fnref59"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">59</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">澳奥姆</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最大值的平均值</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn60" id="user-content-fnref60"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">60</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MOA</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平均值最大化</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn61" id="user-content-fnref61"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">61</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中位数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过取分数的中位数进行简单组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn62" id="user-content-fnref62"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">62</font></font></sup></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多数票</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过获得标签的多数票进行简单组合（可以使用权重）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2015年</font></font></td>
<td><a href="#fn63" id="user-content-fnref63"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">63</font></font></sup></a></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(iii) 异常值检测分数阈值方法</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缩写</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于内核的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AUCP</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">曲线下面积百分比</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.AUCP" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AUCP</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计矩</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自举</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.BOOT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于正态性</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">周</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">肖文内准则</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.CHAU" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">周</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLF</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练有素的线性分类器</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.CLF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLF</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于集群的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集群</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于聚类</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.CLUST" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集群</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于内核的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续专业发展</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变化点检测</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.CPD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续专业发展</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于转型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分解</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分解</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.DECOMP" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分解</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于正态性</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据服务网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与正常距离的偏移</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.DSN" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据服务网络</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于曲线</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EB</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">椭圆边界</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.EB" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EB</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于内核的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">烟气脱硫</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">固定梯度下降</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.FGD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">烟气脱硫</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于过滤器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">筛选</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于过滤</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.FILTER" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">筛选</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于曲线</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">短波频率调制</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最小全宽</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.FWFM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">短波频率调制</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计测试</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全球可持续发展</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">广义极端学生化偏差</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.GESD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全球可持续发展</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于过滤器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">希斯特</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于直方图</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.HIST" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">希斯特</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于分位数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IQR</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">四分位间区域</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.IQR" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IQR</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计矩</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卡奇</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Karcher 均值（黎曼质量中心）</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.KARCH" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卡奇</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计矩</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">疯狂的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中值绝对偏差</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.MAD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">疯狂的</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计测试</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCST</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蒙特卡洛夏皮罗测试</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.MCST" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCST</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于集成的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">梅塔</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">元模型训练分类器</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.META" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">梅塔</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于转型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摩尔</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">弗里德里希的舒缓剂</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.MOLL" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摩尔</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于统计测试</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">四甲基偶氮唑盐</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">改良 Thompson Tau 测试</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.MTT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">四甲基偶氮唑盐</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式空间向量机</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一类支持向量机</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.OCSVM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式空间向量机</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于分位数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量管理中心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准蒙特卡罗差异</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.QMCD" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量管理中心</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">再生率</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于回归</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.REGR" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">再生率</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经网络</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VAE</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变分自动编码器</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.VAE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VAE</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于曲线</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拓扑绕数</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.WIND" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于转型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YJ</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杨约翰逊转变</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.YJ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YJ</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于正态性</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">零分数</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Z 分数</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.models.html#module-pyod.models.thresholds.ZSCORE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">零分数</font></font></a></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(四) 实用功能</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成数据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">综合数据生成；正常数据由多元高斯生成，异常值由均匀分布生成</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.utils.html#module-pyod.utils.data.generate_data" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成数据</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成数据簇</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集群中的综合数据生成；可以使用多个集群创建更复杂的数据模式</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.utils.html#pyod.utils.data.generate_data_clusters" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成数据簇</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">统计数据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮尔森</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算两个样本的加权皮尔逊相关性</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.utils.html#module-pyod.utils.stat_models.wpearsonr" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮尔森</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公用事业</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取标签n</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过将 1 分配给前 n 个异常值分数，将原始异常值分数转换为二进制标签</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.utils.html#module-pyod.utils.utility.get_label_n" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取标签n</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公用事业</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">precision_n_scores 精度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算精度@等级n</font></font></td>
<td><a href="https://pyod.readthedocs.io/en/latest/pyod.utils.html#module-pyod.utils.utility.precision_n_scores" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">precision_n_scores 精度</font></font></a></td>
</tr>
</tbody>
</table>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-quick-start-for-outlier-detection" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异常值检测快速入门</font></font></h2><a id="user-content-quick-start-for-outlier-detection" class="anchor" aria-label="永久链接：异常值检测快速入门" href="#quick-start-for-outlier-detection"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 通过一些特色帖子和教程得到了机器学习社区的广泛认可。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Analytics Vidhya</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://www.analyticsvidhya.com/blog/2019/02/outlier-detection-python-pyod/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PyOD 库在 Python 中学习异常值检测的精彩教程</font></font></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDnuggets</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://www.kdnuggets.com/2019/02/outlier-detection-methods-cheat-sheet.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离群值检测方法的直观可视化</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><a href="https://www.kdnuggets.com/2019/06/overview-outlier-detection-methods-pyod.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyOD 离群值检测方法概述</font></font></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迈向数据科学</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://towardsdatascience.com/anomaly-detection-for-dummies-15f148e559c1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">傻瓜式异常检测</font></font></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算机视觉新闻（2019 年 3 月）</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a href="https://rsipvision.com/ComputerVisionNews-2019March/18/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于异常值检测的 Python 开源工具箱</font></font></a></p>
<p dir="auto"><a href="https://github.com/yzhao062/pyod/blob/master/examples/knn_example.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“examples/knn_example.py”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示了使用 kNN 检测器的基本 API。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">值得注意的是，所有其他算法的 API 都是一致/相似的</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行示例的更详细说明可以在</font></font><a href="https://github.com/yzhao062/pyod/blob/master/examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例目录</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到。</font></font></p>
<ol dir="auto">
<li><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始化 kNN 检测器、拟合模型并进行预测。</font></font></p>
<div id="user-content-cb11" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">models</span>.<span class="pl-s1">knn</span> <span class="pl-k">import</span> <span class="pl-v">KNN</span>   <span class="pl-c"># kNN detector</span>

<span class="pl-c"># train kNN detector</span>
<span class="pl-s1">clf_name</span> <span class="pl-c1">=</span> <span class="pl-s">'KNN'</span>
<span class="pl-s1">clf</span> <span class="pl-c1">=</span> <span class="pl-v">KNN</span>()
<span class="pl-s1">clf</span>.<span class="pl-en">fit</span>(<span class="pl-v">X_train</span>)

<span class="pl-c"># get the prediction label and outlier scores of the training data</span>
<span class="pl-s1">y_train_pred</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-s1">labels_</span>  <span class="pl-c"># binary labels (0: inliers, 1: outliers)</span>
<span class="pl-s1">y_train_scores</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-s1">decision_scores_</span>  <span class="pl-c"># raw outlier scores</span>

<span class="pl-c"># get the prediction on the test data</span>
<span class="pl-s1">y_test_pred</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-en">predict</span>(<span class="pl-v">X_test</span>)  <span class="pl-c"># outlier labels (0 or 1)</span>
<span class="pl-s1">y_test_scores</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-en">decision_function</span>(<span class="pl-v">X_test</span>)  <span class="pl-c"># outlier scores</span>

<span class="pl-c"># it is possible to get the prediction confidence as well</span>
<span class="pl-s1">y_test_pred</span>, <span class="pl-s1">y_test_pred_confidence</span> <span class="pl-c1">=</span> <span class="pl-s1">clf</span>.<span class="pl-en">predict</span>(<span class="pl-v">X_test</span>, <span class="pl-s1">return_confidence</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)  <span class="pl-c"># outlier labels (0 or 1) and confidence in the range of [0,1]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from pyod.models.knn import KNN   # kNN detector

# train kNN detector
clf_name = 'KNN'
clf = KNN()
clf.fit(X_train)

# get the prediction label and outlier scores of the training data
y_train_pred = clf.labels_  # binary labels (0: inliers, 1: outliers)
y_train_scores = clf.decision_scores_  # raw outlier scores

# get the prediction on the test data
y_test_pred = clf.predict(X_test)  # outlier labels (0 or 1)
y_test_scores = clf.decision_function(X_test)  # outlier scores

# it is possible to get the prediction confidence as well
y_test_pred, y_test_pred_confidence = clf.predict(X_test, return_confidence=True)  # outlier labels (0 or 1) and confidence in the range of [0,1]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div></div></li>
<li><p dir="auto"><font style="vertical-align: inherit;"></font><a href="mailto:p@n"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 ROC 和 Precision @ Rank n ( p@n</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> )</font><font style="vertical-align: inherit;">评估预测。</font></font></p>
<div id="user-content-cb12" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">pyod</span>.<span class="pl-s1">utils</span>.<span class="pl-s1">data</span> <span class="pl-k">import</span> <span class="pl-s1">evaluate_print</span>

<span class="pl-c"># evaluate and print the results</span>
<span class="pl-en">print</span>(<span class="pl-s">"<span class="pl-cce">\n</span>On Training Data:"</span>)
<span class="pl-en">evaluate_print</span>(<span class="pl-s1">clf_name</span>, <span class="pl-s1">y_train</span>, <span class="pl-s1">y_train_scores</span>)
<span class="pl-en">print</span>(<span class="pl-s">"<span class="pl-cce">\n</span>On Test Data:"</span>)
<span class="pl-en">evaluate_print</span>(<span class="pl-s1">clf_name</span>, <span class="pl-s1">y_test</span>, <span class="pl-s1">y_test_scores</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from pyod.utils.data import evaluate_print

# evaluate and print the results
print(&quot;\nOn Training Data:&quot;)
evaluate_print(clf_name, y_train, y_train_scores)
print(&quot;\nOn Test Data:&quot;)
evaluate_print(clf_name, y_test, y_test_scores)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div></div></li>
<li><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看示例输出和可视化。</font></font></p>
<div id="user-content-cb13" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-v">On</span> <span class="pl-v">Training</span> <span class="pl-v">Data</span>:
<span class="pl-v">KNN</span> <span class="pl-v">ROC</span>:<span class="pl-c1">1.0</span>, <span class="pl-s1">precision</span> @ <span class="pl-s1">rank</span> <span class="pl-s1">n</span>:<span class="pl-c1">1.0</span>

<span class="pl-v">On</span> <span class="pl-v">Test</span> <span class="pl-v">Data</span>:
<span class="pl-v">KNN</span> <span class="pl-v">ROC</span>:<span class="pl-c1">0.9989</span>, <span class="pl-s1">precision</span> @ <span class="pl-s1">rank</span> <span class="pl-s1">n</span>:<span class="pl-c1">0.9</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="On Training Data:
KNN ROC:1.0, precision @ rank n:1.0

On Test Data:
KNN ROC:0.9989, precision @ rank n:0.9" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div></div>
<div id="user-content-cb14" dir="auto"><div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">visualize</span>(<span class="pl-s1">clf_name</span>, <span class="pl-v">X_train</span>, <span class="pl-s1">y_train</span>, <span class="pl-v">X_test</span>, <span class="pl-s1">y_test</span>, <span class="pl-s1">y_train_pred</span>,
    <span class="pl-s1">y_test_pred</span>, <span class="pl-s1">show_figure</span><span class="pl-c1">=</span><span class="pl-c1">True</span>, <span class="pl-s1">save_figure</span><span class="pl-c1">=</span><span class="pl-c1">False</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="visualize(clf_name, X_train, y_train, X_test, y_test, y_train_pred,
    y_test_pred, show_figure=True, save_figure=False)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div></div></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可视化（</font></font><a href="https://raw.githubusercontent.com/yzhao062/pyod/master/examples/KNN.png" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">knn_figure</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）：</font></font></p>
<p dir="auto"><a href="https://raw.githubusercontent.com/yzhao062/pyod/master/examples/KNN.png" rel="nofollow"><img src="https://raw.githubusercontent.com/yzhao062/pyod/master/examples/KNN.png" alt="kNN 示例图" style="max-width: 100%;"></a></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 id="user-content-reference" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考</font></font></h2><a id="user-content-reference" class="anchor" aria-label="永久链接：参考" href="#reference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<section>
<hr>
<ol dir="auto">
<li id="user-content-fn1"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵Y.，胡X.，程成C.，王成C.，万成.，王文.，杨J.，白红.，李Z.，肖成.， Wang, Y.、Qiao, Z.、Sun, J. 和 Akoglu, L. (2021)。 SUOD：加速大规模无监督异构异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习和系统会议（MLSys）</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn2"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Perini, L.、Vercruyssen, V.、Davis, J. 量化异常检测器在示例预测中的置信度。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欧洲机器学习和数据库知识发现联合会议 (ECML-PKDD)</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font><font style="vertical-align: inherit;">2020 年。</font></font><a href="#fnref2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn3"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Han, S.、Hu, X.、Huang, H.、Jiang, M. 和 Zhu, Y.，2022。ADBench：异常检测基准。 arXiv 预印本 arXiv：2206.09426。</font></font><a href="#fnref3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn4"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵Y.，胡X.，程成C.，王成C.，万成.，王文.，杨J.，白红.，李Z.，肖成.， Wang, Y.、Qiao, Z.、Sun, J. 和 Akoglu, L. (2021)。 SUOD：加速大规模无监督异构异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习和系统会议（MLSys）</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn5"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Li, Z.、Zhao, Y.、Hu, X.、Botta, N.、Ionescu, C. 和 Chen, HG ECOD：使用经验累积分布函数的无监督离群值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 知识与数据工程汇刊 (TKDE)</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2022 年</font></font><a href="#fnref5"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。↩</font></font></a></p></li>
<li id="user-content-fn6"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kriegel, HP 和 Zimek, A.，2008 年 8 月。高维数据中基于角度的异常值检测。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD '08</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 444-452 页。 ACM。</font></font><a href="#fnref6"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn7"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kriegel, HP 和 Zimek, A.，2008 年 8 月。高维数据中基于角度的异常值检测。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD '08</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 444-452 页。 ACM。</font></font><a href="#fnref7"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn8"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Li, Z.、Zhao, Y.、Botta, N.、Ionescu, C. 和 Hu, X. COPOD：基于 Copula 的异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 国际数据挖掘会议 (ICDM)</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2020。</font></font><a href="#fnref8"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn9"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Iglewicz, B. 和 Hoaglin, DC，1993。如何检测和处理异常值（第 16 卷）。阿斯克出版社。</font></font><a href="#fnref9"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn10"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janssens, JHM、Huszár, F.、Postma, EO 和 van den Herik, HJ, 2012。随机异常值选择。技术报告 TiCC TR 2012-001，蒂尔堡大学蒂尔堡认知与交流中心，荷兰蒂尔堡。</font></font><a href="#fnref10"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn11"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fang, KT 和 Ma, CX, 2001。随机抽样、拉丁超立方体和均匀设计的环绕式 L2 差异。复杂性杂志，17(4)，第 608-624 页。</font></font><a href="#fnref11"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn12"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Latecki, LJ、Lazarevic, A. 和 Pokrajac, D.，2007 年 7 月。使用核密度函数进行离群值检测。在模式识别中的机器学习和数据挖掘国际研讨会（第 61-75 页）。施普林格、柏林、海德堡。</font></font><a href="#fnref12"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn13"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sugiyama, M. 和 Borgwardt, K.，2013。通过采样进行基于距离的快速异常值检测。神经信息处理系统的进展，26。</font></font><a href="#fnref13"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn14"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC, 2015。异常值分析。数据挖掘（第 237-263 页）。施普林格、查姆. </font></font><a href="#fnref14"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn15"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shyu, ML, Chen, SC, Sarinnapakorn, K. 和 Chang, L., 2003。一种基于主成分分类器的新颖异常检测方案。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">佛罗里达州科勒尔盖布尔斯迈阿密大学电气与计算机工程系</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref15"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn16"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hoffmann, H., 2007。用于新颖性检测的内核 PCA。模式识别，40(3)，第 863-874 页。</font></font><a href="#fnref16"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn17"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hardin, J. 和 Rocke, DM，2004。使用最小协方差行列式估计器在多聚类设置中进行异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算统计与数据分析</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，44(4)，第 625-638 页。</font></font><a href="#fnref17"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn18"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rousseeuw, PJ 和 Driessen, KV，1999。最小协方差行列式估计器的快速算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术计量学</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，41(3)，第 212-223 页。</font></font><a href="#fnref18"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn19"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cook, RD, 1977。线性回归中影响观察的检测。技术计量学，19(1)，第 15-18 页。</font></font><a href="#fnref19"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn20"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scholkopf, B.、Platt, JC、Shawe-Taylor, J.、Smola, AJ 和 Williamson, RC，2001。估计高维分布的支持。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">神经计算</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，13(7)，第 1443-1471 页。</font></font><a href="#fnref20"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn21"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Arning, A.、Agrawal, R. 和 Raghavan, P.，1996 年 8 月。大型数据库中偏差检测的线性方法。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（第 1141 卷，第 50 期，第 972-981 页）中。</font></font><a href="#fnref21"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn22"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Breunig, MM、Kriegel, HP、Ng, RT 和 Sander, J.，2000 年 5 月。 LOF：识别基于密度的局部异常值。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM Sigmod 记录</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，29(2)，第 93-104 页。</font></font><a href="#fnref22"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn23"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tang, J.、Chen, Z.、Fu, AWC 和 Cheung, DW，2002 年 5 月。增强低密度模式异常值检测的有效性。载于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚太知识发现和数据挖掘会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 535-548 页。施普林格、柏林、海德堡。</font></font><a href="#fnref23"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn24"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tang, J.、Chen, Z.、Fu, AWC 和 Cheung, DW，2002 年 5 月。增强低密度模式异常值检测的有效性。载于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚太知识发现和数据挖掘会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 535-548 页。施普林格、柏林、海德堡。</font></font><a href="#fnref24"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn25"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">He, Z.、Xu, X. 和 Deng, S.，2003。发现基于集群的局部异常值。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式识别字母</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，24(9-10)，第 1641-1650 页。</font></font><a href="#fnref25"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn26"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Papadimitriou, S.、Kitakawa, H.、Gibbons, PB 和 Faloutsos, C.，2003 年 3 月。 LOCI：使用局部相关积分进行快速异常值检测。 ICDE </font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">'03</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 315-326 页。 IEEE。</font></font><a href="#fnref26"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn27"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Goldstein, M. 和 Dengel, A.，2012。基于直方图的离群值评分 (hbos)：一种快速无监督异常检测算法。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KI-2012：海报和演示轨道</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 59-63 页。</font></font><a href="#fnref27"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn28"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ramaswamy, S.、Rastogi, R. 和 Shim, K.，2000 年 5 月。从大型数据集中挖掘异常值的有效算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM Sigmod 记录</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，29(2)，第 427-438 页。</font></font><a href="#fnref28"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn29"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Angiulli, F. 和 Pizzuti, C.，2002 年 8 月。高维空间中的快速异常值检测。欧洲</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据挖掘和知识发现原理会议，</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 15-27 页。</font></font><a href="#fnref29"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn30"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Angiulli, F. 和 Pizzuti, C.，2002 年 8 月。高维空间中的快速异常值检测。欧洲</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据挖掘和知识发现原理会议，</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 15-27 页。</font></font><a href="#fnref30"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn31"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kriegel, HP、Kröger, P.、Schubert, E. 和 Zimek, A.，2009 年 4 月。高维数据轴平行子空间中的异常值检测。载于</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亚太知识发现和数据挖掘会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 831-838 页。施普林格、柏林、海德堡。</font></font><a href="#fnref31"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn32"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Almardeny, Y.、Boujnah, N. 和 Cleary, F.，2020。一种新颖的多元数据异常值检测方法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 知识与数据工程汇刊</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref32"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn33"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">刘 FT、丁 KM 和周 ZH，2008 年 12 月。隔离森林。国际</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据挖掘会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，第 413-422 页。 IEEE。</font></font><a href="#fnref33"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn34"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bandaragoda, TR、Ting, KM、Albrecht, D.、Liu, FT、Zhu, Y. 和 Wells, JR，2018，使用最近邻集成的基于隔离的异常检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算智能</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，34(4)，第 968-998 页。</font></font><a href="#fnref34"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn35"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Xu, H., Pang, G., Wang, Y., Wang, Y., 2023。用于异常检测的深度隔离森林。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 知识与数据工程汇刊</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref35"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn36"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lazarevic, A. 和 Kumar, V.，2005 年 8 月。用于异常值检测的特征装袋。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD '05</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。 2005. </font></font><a href="#fnref36"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn37"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵 Y.、纳斯鲁拉 Z.、Hryniewicki, MK 和李 Z.，2019 年 5 月。 LSCP：并行异常值集合中的局部选择性组合。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019 年 SIAM 国际数据挖掘会议 (SDM) 论文集</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font><font style="vertical-align: inherit;">第 585-593 页。工业与应用数学学会。</font></font><a href="#fnref37"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn38"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵，Y. 和 Hryniewicki，MK XGBOD：通过无监督表示学习改进有监督异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 国际神经网络联合会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2018 </font></font><a href="#fnref38"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 ↩</font></font></a></p></li>
<li id="user-content-fn39"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pevný, T., 2016。Loda：轻量级在线异常检测器。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，102(2)，第 275-304 页。</font></font><a href="#fnref39"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn40"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵Y.，胡X.，程成C.，王成C.，万成.，王文.，杨J.，白红.，李Z.，肖成.， Wang, Y.、Qiao, Z.、Sun, J. 和 Akoglu, L. (2021)。 SUOD：加速大规模无监督异构异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习和系统会议（MLSys）</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref40"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn41"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC, 2015。异常值分析。数据挖掘（第 237-263 页）。施普林格、查姆. </font></font><a href="#fnref41"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn42"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kingma, DP 和 Welling, M.，2013。自动编码变分贝叶斯。 arXiv 预印本 arXiv：1312.6114。</font></font><a href="#fnref42"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn43"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伯吉斯，克里斯托弗·P.，等人。 “了解 beta-VAE 中的解缠结。” arXiv 预印本 arXiv:1804.03599 (2018)。</font></font><a href="#fnref43"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn44"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Liu, Y., Li, Z., Zhou, C., Jiang, Y., Sun, J., Wang, M. and He, X., 2019。用于无监督异常值检测的生成对抗主动学习。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 知识与数据工程汇刊</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref44"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn45"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Liu, Y., Li, Z., Zhou, C., Jiang, Y., Sun, J., Wang, M. and He, X., 2019。用于无监督异常值检测的生成对抗主动学习。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 知识与数据工程汇刊</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref45"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn46"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ruff, L.、Vandereulen, R.、Goernitz, N.、Deecke, L.、Siddiqui, SA、Binder, A.、Müller, E. 和 Kloft, M.，2018 年 7 月。深度一类分类。国际</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（第 4393-4402 页）。 PMLR。</font></font><a href="#fnref46"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn47"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Schlegl, T.、Seeböck, P.、Waldstein, SM、Schmidt-Erfurth, U. 和 Langs, G.，2017 年 6 月。使用生成对抗网络进行无监督异常检测，以指导标记发现。医学影像信息处理国际会议（第 146-157 页）。施普林格、查姆. </font></font><a href="#fnref47"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn48"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zenati, H.、Romain, M.、Foo, CS、Lecouat, B. 和 Chandrasekhar, V.，2018 年 11 月。对抗性学习异常检测。 2018 年 IEEE 国际数据挖掘会议 (ICDM)（第 727-736 页）。 IEEE。</font></font><a href="#fnref48"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn49"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">You, C.、Robinson, DP 和 Vidal, R.，2017。子空间并集中基于可证明的自我表示的异常值检测。 IEEE 计算机视觉和模式识别会议论文集。</font></font><a href="#fnref49"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn50"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Goodge, A.、Hooi, B.、Ng, SK 和 Ng, WS，2022 年 6 月。 Lunar：通过图神经网络统一局部异常值检测方法。 AAAI 人工智能会议论文集。</font></font><a href="#fnref50"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn51"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lazarevic, A. 和 Kumar, V.，2005 年 8 月。用于异常值检测的特征装袋。在</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD '05</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。 2005. </font></font><a href="#fnref51"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn52"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵 Y.、纳斯鲁拉 Z.、Hryniewicki, MK 和李 Z.，2019 年 5 月。 LSCP：并行异常值集合中的局部选择性组合。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2019 年 SIAM 国际数据挖掘会议 (SDM) 论文集</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font><font style="vertical-align: inherit;">第 585-593 页。工业与应用数学学会。</font></font><a href="#fnref52"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn53"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵，Y. 和 Hryniewicki，MK XGBOD：通过无监督表示学习改进有监督异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 国际神经网络联合会议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，2018 </font></font><a href="#fnref53"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 ↩</font></font></a></p></li>
<li id="user-content-fn54"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pevný, T., 2016。Loda：轻量级在线异常检测器。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，102(2)，第 275-304 页。</font></font><a href="#fnref54"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn55"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵Y.，胡X.，程成C.，王成C.，万成.，王文.，杨J.，白红.，李Z.，肖成.， Wang, Y.、Qiao, Z.、Sun, J. 和 Akoglu, L. (2021)。 SUOD：加速大规模无监督异构异常值检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习和系统会议（MLSys）</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#fnref55"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn56"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bandaragoda, TR、Ting, KM、Albrecht, D.、Liu, FT、Zhu, Y. 和 Wells, JR，2018，使用最近邻集成的基于隔离的异常检测。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算智能</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，34(4)，第 968-998 页。</font></font><a href="#fnref56"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn57"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref57"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn58"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref58"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn59"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref59"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn60"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref60"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn61"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref61"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn62"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref62"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
<li id="user-content-fn63"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggarwal, CC 和 Sathe, S.，2015。离群值集合的理论基础和算法。</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM SIGKDD 探索通讯</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，17(1)，第 24-47 页。</font></font><a href="#fnref63"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">↩</font></font></a></p></li>
</ol>
</section>
</article></div>
